# Practical-11-Lists-and-Tables

<!DOCTYPE html>
<html>
<head>
    <title>Course List and Timetable</title>
    <style>
        body {
            font-family: Arial;
        }

        ul {
            list-style-type: square;
            color: blue;
        }

        table {
            border-collapse: collapse;
            width: 80%;
        }

        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: center;
        }

        th {
            background: navy;
            color: white;
        }

        tr:nth-child(even) {
            background: lightblue;
        }

        tr:hover {
            background: yellow;
        }
    </style>
</head>
<body>
    <h2>College Courses</h2>
    <ul>
        <li>BCA</li>
        <li>B.Tech</li>
        <li>B.Sc</li>
        <li>B.Com</li>
    </ul>

    <h2>Student Timetable</h2>
    <table>
        <tr>
            <th>Day</th>
            <th>9-10 AM</th>
            <th>10-11 AM</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>HTML</td>
            <td>CSS</td>
        </tr>
        <tr>
            <td>Tuesday</td>
            <td>Python</td>
            <td>Maths</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>Java</td>
            <td>English</td>
        </tr>
        <tr>
            <td>Thursday</td>
            <td>CSS</td>
            <td>Python</td>
        </tr>
    </table>
</body>
</html>
