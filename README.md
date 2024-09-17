<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Table</title>
    <style>
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid #dddddd;
            text-align: left;
            padding: 8px;
        }
        th {
            background-color: #f2f2f2;
            color: #333;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        .event-name {
            text-align: center;
        }
    </style>
</head>
<body>
    <table>
        <thead>
            <tr>
                <th colspan="3" class="event-name">Event Details</th>
            </tr>
            <tr>
                <th>Name of Event</th>
                <th>Date</th>
                <th>Location</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>San Juan Festival</td>
                <td>Jun 24, 2024</td>
                <td>Manila city, Metromanila</td>
            </tr>
            <tr>
                <td>Balayong Festival</td>
                <td>March 24, 2024</td>
                <td>Balayong park, Puerto Princesa</td>
            </tr>
            <tr>
                <td>Feast of Forest</td>
                <td>Feb 08, 2024</td>
                <td>Irawan, Puerto Princesa </td>
            </tr>
        </tbody>
    </table>
</body>
</html>
