<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML Laboratory 1</title>

    <style>
        body {
            background-color: #fff7ed;
            font-family: "Segoe UI", Tahoma, sans-serif;
            margin: 40px;
            color: #2d2d2d;
        }

        h1 {
            color: #9a3412;
            text-align: center;
            letter-spacing: 1px;
        }

        h2 {
            color: #c2410c;
            margin-top: 35px;
        }

        p {
            line-height: 1.7;
            background-color: #ffffff;
            padding: 18px;
            border-left: 6px solid #fdba74;
            border-radius: 6px;
        }

        ul, ol {
            background-color: #ffffff;
            padding: 15px 35px;
            border-radius: 6px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.08);
            width: fit-content;
        }

        a {
            color: #ea580c;
            text-decoration: none;
            font-weight: 600;
        }

        a:hover {
            color: #9a3412;
            text-decoration: underline;
        }

        img {
            display: block;
            margin-top: 12px;
            border-radius: 8px;
        }

        table {
            background-color: #ffffff;
            border-collapse: collapse;
            margin-top: 12px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        th {
            background-color: #fed7aa;
        }

        th, td {
            padding: 12px;
            text-align: center;
        }
    </style>

    <script>
        window.onload = function () {
            alert("Hello World");
        };
    </script>
</head>
<body>
    <h1>Welcome to My HTML5 Web Page</h1>

    <p>
        HTML5 is a language used to build web pages.  
        <br> It relies on tags to arrange and present content online.  
        <br> Understanding basic HTML elements and page layout is essential for web development.  
        <br> This knowledge also introduces important ideas such as the DOM and web storage.
    </p>

    <h2>Unordered List</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

    <h2>Ordered List</h2>
    <ol>
        <li>Planning</li>
        <li>Designing</li>
        <li>Development</li>
    </ol>

    <h2>Hyperlink</h2>
    <a href="https://www.w3schools.com" target="_blank">Go to W3Schools Website</a>

    <h2>Image</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/W3Schools_logo.svg/960px-W3Schools_logo.svg.png" 
     alt="Sample Image" 
     width="150">

    <h2>Student Information</h2>
    <table border="1" cellpadding="5">
        <tr>
            <th>Full Name</th>
            <th>Program</th>
            <th>Year Level</th>
        </tr>
        <tr>
            <td>Catherine Doming</td>
            <td>BSIT</td>
            <td>3rd Year</td>
        </tr>
        <tr>
            <td>Zyra Mae Honor</td>
            <td>BSIT</td>
            <td>3rd Year</td>
        </tr>
    </table>

</body>
</html>
