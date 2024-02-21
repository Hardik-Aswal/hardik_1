<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hardik Aswal</title>
    <style>
        /* General Styles */
        body {
            background-image: url('background_image.jpg');
            background-size: cover;
        }

        /* About Me Section */
        .about-me {
            border: 2pt solid black;
            background-color: lightcoral;
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 20px;
        }

        .profile-info {
            font-family: 'Times New Roman', serif;
            font-size: 13pt;
            font-weight: bold;
            text-align: left;
        }

        .profile-picture {
            width: 172px;
            height: 172px;
        }

        .description {
            font-family: sans-serif;
            color: blue;
        }

        /* Education Section */
        .education {
            background-color: lightblue;
            padding: 10px;
        }

        .education table {
            width: 100%;
            border-spacing: 10px;
        }

        .education th {
            text-align: left;
            text-decoration: underline;
        }

        .education td {
            text-align: center;
        }

        /* Courses Section */
        .courses {
            display: flex;
            justify-content: space-between;
        }

        .spring-semester, .autumn-semester {
            width: 45%;
            border: 3pt solid;
            padding: 10px;
        }

        .spring-semester {
            background-color: lightgreen;
        }

        .autumn-semester {
            background-color: lightpink;
        }

        .courses a {
            color: blue;
        }

        .courses a:visited {
            color: gray;
        }

        .courses a:hover {
            color: green;
        }

        .courses a:active {
            color: pink;
        }

        /* Hobbies Section */
        .hobbies {
            background-color: lavender;
            padding: 20px;
        }
    </style>
</head>
<body>

<section class="about-me">
    <div class="profile-info">
        <h1>Hardik Aswal</h1>
        <p class="description">A Second year undergrad student in Mnc Branch</p>
    </div>
    <img src="profile_picture.jpg" alt="Profile Picture" class="profile-picture">
</section>

<section class="education">
    <h2>EDUCATION</h2>
    <table>
      <tr>
        <th>Academic year</th>
        <th>Class</th>
        <th>School Name</th>
      </tr>
      <tr>
        <td>2020</td>
        <td>10th</td>
        <td>School XYZ</td>
      </tr>
      <tr>
        <td>2022</td>
        <td>12th</td>
        <td>School ABC</td>
      </tr>
      <tr>
        <td>2022</td>
        <td>JEE Main</td>
        <td>Coaching Institute</td>
      </tr>
      <tr>
        <td>2023</td>
        <td>First year</td>
        <td>IIT Goa</td>
      </tr>
    </table>
</section>

<section class="courses">
    <div class="spring-semester">
        <h2>Spring Semester Courses</h2>
        <ul>
            <li><a href="#" style="color: blue;">CS102</a> - Introduction to Computer Science <i style="font-style: italic;">Instructor: Prof. Smith</i></li>
            <li><a href="#" style="color: blue;">MA203</a> - Calculus <i style="font-style: italic;">Instructor: Prof. Johnson</i></li>
        </ul>
    </div>
    <div class="autumn-semester">
        <h2>Autumn Semester Courses</h2>
        <ol type="i">
            <li><a href="#" style="color: blue;">CS202</a> - Data Structures and Algorithms <i style="font-style: italic;">Instructor: Prof. Brown</i></li>
            <li><a href="#" style="color: blue;">EE201</a> - Electrical Engineering <i style="font-style: italic;">Instructor: Prof. Lee</i></li>
        </ol>
    </div>
</section>

<section class="hobbies">
    <h2>Hobbies & Interests</h2>
    <ul>
        <li>Badminton</li>
        <li>Chess</li>
        <li>Guitar</li>
        <li>Reading Books</li>
        <li>Competitive Programming</li>
    </ul>
</section>

</body>
</html>
