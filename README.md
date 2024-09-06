<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MealMatchMission - Waste Food Management System</title>
<!--     <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        h1 {
            font-size: 2.5em;
        }
        h2 {
            font-size: 2em;
        }
        h3 {
            font-size: 1.5em;
        }
        p {
            font-size: 1.1em;
            color: #555;
        }
        ul {
            list-style: disc inside;
            margin-left: 20px;
        }
        code {
            background-color: #eee;
            padding: 5px;
            border-radius: 5px;
        }
    </style> -->
</head>
<body>

    <h1>MealMatchMission</h1>
    <h2>Waste Food Management System</h2>

    <h3>Abstract:</h3>
    <p>
        Many organizations and events generate significant amounts of food waste that often end up in landfills, contributing to environmental issues. However, much of this food waste can be repurposed effectively. 
        Specifically, the goal is to establish a streamlined system for transporting food waste from various sources, such as events and restaurants, to charitable organizations that support individuals in need.
    </p>

    <h3>Mission:</h3>
    <p>Combat food waste and hunger by creating a sustainable and efficient system for redistributing excess food to those in need.</p>

    <h3>Vision:</h3>
    <p>We strive to create a world where food is valued, resources are used wisely, and every individual has access to nutritious meals.</p>

    <h3>Software Specification:</h3>
    <ul>
        <li>Frontend: HTML, CSS, JavaScript</li>
        <li>Backend: phpMyAdmin</li>
        <li>Database: MySQL</li>
    </ul>

    <h3>Modules:</h3>
    <h4>User:</h4>
    <ul>
        <li>Register/login into the system</li>
        <li>Get information about the organization</li>
        <li>Contact organization for donation</li>
        <li>Give the location to admin</li>
        <li>Provide feedback</li>
    </ul>

    <h4>Admin:</h4>
    <ul>
        <li>Login in the system</li>
        <li>Manage users</li>
        <li>Maintain application</li>
        <li>Receive the feedback</li>
    </ul>

    <h4>Delivery Boy:</h4>
    <ul>
        <li>Register/login in the system</li>
        <li>Take orders from users</li>
        <li>Contact the organization</li>
        <li>Receive the location from admin</li>
    </ul>

    <h3>Steps for Execution:</h3>
    <ol>
        <li>Download the project zip file.</li>
        <li>Extract the file and copy the folder.</li>
        <li>Paste inside root directory (for XAMPP <code>xampp/htdocs</code>, for WAMP <code>wamp/www</code>, for LAMP <code>var/www/Html</code>).</li>
        <li>Open PHPMyAdmin (<a href="http://localhost/phpmyadmin" target="_blank">http://localhost/phpmyadmin</a>).</li>
        <li>Create a database.</li>
        <li>Import <code>demo.sql</code> file (inside the database folder).</li>
        <li>Run the script <code>http://localhost/folderName</code>.</li>
    </ol>

</body>
</html>
