<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>KALANGALALA SECONDARY SCHOOL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #e8f1f5;
        }

        nav {
            background-color: #0d5c75;
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: orange;
            color: black;
        }

        .content {
            padding: 20px;
            text-align: center;
        }

        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid #ccc;
        }

        th, td {
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #0d5c75;
            color: white;
        }
    </style>
</head>
<body>

<nav>
    <ul>
        <li><a href="{% url 'home' %}">Home</a></li>
        <li><a href="{% url 'about' %}">About Us</a></li>
        <li><a href="#">Teachers</a></li>
        <li><a href="#">Student's Administration</a></li>
    </ul>
</nav>

<div class="content">
    <h1>Karibu Shule Yetu!</h1>
    <p>Hii ni tovuti rasmi ya shule yetu mpya. Tuwakaribisha sana.</p>

    <h2>Walimu</h2>
    <table>
        <tr>
            <th>Jina la Mwalimu</th>
            <th>Idara</th>
        </tr>
        <tr>
            <td>Mwalimu Asha</td>
            <td>Hisabati</td>
        </tr>
        <tr>
            <td>Mwalimu John</td>
            <td>Kemia</td>
        </tr>
    </table>

    <h2>Student's Administration System</h2>
    <table>
        <tr>
            <th>Mwaka</th>
            <th>Jina la Mwanafunzi</th>
            <th>Nafasi</th>
        </tr>
        <tr>
            <td>2022</td>
            <td>Fatma Musa</td>
            <td>Head Girl</td>
        </tr>
        <tr>
            <td>2023</td>
            <td>Juma Said</td>
            <td>Head Boy</td>
        </tr>
    </table>
</div>

</body>
</html>
