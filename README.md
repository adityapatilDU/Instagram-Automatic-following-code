<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    Instagram Auto Follow Script
</head>
<body>
    <h1>Instagram Auto Follow Script</h1>

  <p><strong>Description:</strong></p>
    <p>This script automates the process of logging into Instagram and following a list of user profiles from an Excel sheet. Using <strong>Selenium WebDriver</strong>, it opens Instagram, logs in with the provided credentials, and follows the usernames listed in the provided Excel file. The script pauses randomly between 2 to 6 seconds between each follow action to mimic human behavior and avoid being flagged as a bot. Every 10 users, the script takes a 10-second break to simulate natural usage patterns.</p>

   <h2>Key Features:</h2>
    <ul>
        <li><strong>Login to Instagram:</strong> Automatically logs into Instagram using the specified username and password.</li>
        <li><strong>Follow Users:</strong> Reads a list of Instagram usernames from an Excel file and follows each user if not already followed.</li>
        <li><strong>Randomized Delays:</strong> Introduces random delays between actions to avoid detection.</li>
        <li><strong>Breaks:</strong> Every 10 actions, the script pauses for 10 seconds, simulating human-like behavior.</li>
    </ul>

   <h2>Dependencies:</h2>
    <ul>
        <li><strong>Selenium:</strong> For automating the web browser.</li>
        <li><strong>Pandas:</strong> For reading the Excel file containing usernames.</li>
        <li><strong>openpyxl:</strong> For handling .xlsx files in Pandas.</li>
    </ul>

   <h2>Installation:</h2>
    <p>To use this script, make sure you have the following dependencies installed:</p>
    <pre>
pip install selenium
pip install pandas
pip install openpyxl
    </pre>

  <h2>Usage:</h2>
    <ol>
        <li>Replace the <code>username</code> and <code>password</code> variables with your Instagram credentials.</li>
        <li>Update the <code>excel_file_path</code> to point to your Excel file containing the list of usernames.</li>
        <li>Run the script, and it will follow the specified accounts on Instagram.</li>
    </ol>

  <h2>How to Run:</h2>
    <ol>
        <li>Ensure that you have the ChromeDriver downloaded and located at the specified path (in the script).</li>
        <li>Execute the script in your terminal or IDE of choice.</li>
        <li>Monitor the terminal for the list of followed users and any errors.</li>
    </ol>

   <h2>Important Notes:</h2>
    <ul>
        <li>Make sure the <code>excel_file_path</code> points to a valid Excel file containing Instagram usernames in Column B.</li>
        <li>Use this script responsibly. Avoid spamming or violating Instagram's terms of service.</li>
        <li>Ensure that you have the correct version of <strong>ChromeDriver</strong> that matches your Chrome browser version.</li>
    </ul>

   <h2>License:</h2>
    <p>This project is open-source and available under the MIT License.</p>

   <h2>Contributing:</h2>
    <p>If you'd like to contribute to this project, feel free to fork it, submit issues, and create pull requests. Contributions are welcome!</p>

  <footer>
        <p>Created by <strong>Your Name</strong>. Follow me on GitHub.</p>
    </footer>
</body>
</html>
