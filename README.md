<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airport Management</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f8f9fa;
        }

        .navbar {
            background-color: #007bff;
            padding: 10px;
            text-align: center;
        }

        .navbar ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        .navbar ul li {
            display: inline;
            margin: 0 15px;
        }

        .navbar ul li a {
            color: white;
            text-decoration: none;
        }

        .navbar ul li a:hover {
            text-decoration: underline;
            color: #ffcc00;
        }

        .header {
            background-color: #343a40;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .content {
            padding: 20px;
        }

        .content-image {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 0 auto 20px;
        }

        .data-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }

        .data-table th, .data-table td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
        }

        .data-table th {
            background-color: #007bff;
            color: white;
        }

        .data-table tr:nth-child(even) {
            background-color: #f2f2f2;
        }

        .footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        @media (max-width: 600px) {
            .navbar ul li {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#flights">Flights</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header class="header">
        <h1>Welcome to Airport Management Portal</h1>
        <p>Streamlining Airport Operations with Efficiency</p>
    </header>

    <section class="content">
        <h3>Airport View</h3>
        <img src="Airpoart.jpg" alt="Airport View" class="content-image">

        <h2>Flight Schedule</h2>
        <table class="data-table">
            <tr>
                <th>Flight</th>
                <th>Destination</th>
                <th>Departure</th>
                <th>Status</th>
            </tr>
            <tr>
                <td>AI-101</td>
                <td>New York</td>
                <td>10:30 AM</td>
                <td>On Time</td>
            </tr>
            <tr>
                <td>BA-204</td>
                <td>London</td>
                <td>11:15 AM</td>
                <td>Delayed</td>
            </tr>
        </table>
    </section>

    <footer class="footer">
        <p>© 2025 Airport Management. All Rights Reserved.</p>
        <p>
            <a href="https://twitter.com" style="color: white; text-decoration: none;">Twitter</a> |
            <a href="https://facebook.com" style="color: white; text-decoration: none;">Facebook</a>
        </p>
    </footer>
</body>
</html>
