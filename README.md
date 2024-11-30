<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sensor Readings Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8; /* Light gray background */
            color: #000; /* Black text */
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 700px;
            margin: 20px auto;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            border: 1px solid #ccc; /* Light gray border */
        }
        .box {
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 6px;
        }
        .readings-box {
            padding: 10px;
            font-size: 18px;
        }
        .readings-box div {
            margin: 10px 0;
        }
        .timestamp {
            font-size: 14px;
            color: #555; /* Dark gray for timestamps */
        }
        .latest-readings {
            font-weight: bold;
            font-size: 18px;
            padding: 10px;
            border-radius: 6px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
        }
        table, th, td {
            border: 1px solid #000; /* Black border */
        }
        th, td {
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #e0e0e0; /* Light gray header background */
            color: #000;
        }
        tr:nth-child(even) {
            background-color: #f0f0f0; /* Slightly lighter gray for alternating rows */
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box readings-box">
            <div>Temperature: <span class="timestamp"></span></div>
            <div>Pressure: <span class="timestamp"></span></div>
            <div>Humidity: <span class="timestamp"></span></div>
        </div>
        <div class="box latest-readings">
            <p>Latest 4 Readings:</p>
            <table>
                <tr>
                    <th>Timestamp</th>
                    <th>Temperature</th>
                    <th>Pressure</th>
                    <th>Humidity</th>
                </tr>
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
            </table>
        </div>
    </div>
</body>
</html>
