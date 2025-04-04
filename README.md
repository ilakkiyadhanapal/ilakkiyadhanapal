<!DOCTYPE html>

<html>

<head>

    <title>Portfolio</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background-color: #84a6e9;

        }



        header {

            background-color: #941919;

            color: #fff;

            text-align: center;

            padding: 2rem 0;

            position: relative; /* Add this */

        }



        .header-content h1 {

            font-size: 2.5rem;

        }



        /* Add styles for the round profile picture */

        .profile-picture {

            width: 100px; /* Adjust the size as needed */

            height: 100px;

            border-radius: 75%; /* Create a circular shape */

            object-fit: cover; /* To ensure the image fills the circular area */

            position: absolute; /* Add this */

            top: 75px; /* Adjust top position as needed */

            left: 75px; /* Adjust left position as needed */

        }



        nav {

            background-color: #333;

            color: #fff;

            text-align: center;

        }



        nav ul {

            list-style-type: none;

            padding: 0;

        }



        nav ul li {

            display: inline;

            margin: 0 20px;

        }



        nav ul li a {

            text-decoration: none;

            color: #fff;

        }



        .section-content {

            background-color: #fff;

            padding: 2rem;

            margin: 1rem;

            border-radius: 20px;

            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);

            text-align: justify;

        }



        .download-button {

            background-color: #333;

            color: #fff;

            padding: 0.5rem 1rem;

            text-decoration: none;

            border-radius: 20px;

            display: inline-block;

            margin-top: 10px;

            align-self: center;

        }



        .download-button:hover {

            background-color: #555;

        }



        footer {

            text-align: center;

            padding: 1rem 0;

            background-color: #333;

            color: #fff;

        }



        ul {

            list-style-type: disc;

            padding-left: 20px;

        }

    </style>

</head>

<body>

    <header>

        <div class="header-content">

            

             <h1>D.Ilakkiya</h1>

            <p>Bachelor of computerapplication</p>

        </div>

    </header>



    <nav>

        <ul>

            <li><a href="information">Information</a></li>

            <li><a href="#education">Education</a></li>

            <li><a href="#skills">Skills</a></li>

        

            <li><a href="#resume">Resume</a></li>

           

        </ul>

    </nav>



      <section id="information">
            <div class="section-content">
<h2>Information</h2>
            <p><strong>Name:</strong>D.Ilakkiya</p>
            <p><strong>date of birth:</strong>14-05-2006</p>
            <p><strong>phone no:</strong>8610349425</p>
            <p><strong>Email:</strong>ilakkiyadhanapal14@gmail.com</p>
            <p><strong>Address:</strong>17/5A SankarNagar, sirumugai road, mettupalayam</p>
            <p><strong>Pin code:</strong>641 104</p>



        </div>

    </section>



     <section id="education"> <div class="section-content">
<h2>Education</h2>
            <p><strong>Course:</strong>BCA</p>
            <p><strong>University Name:</strong>Bharathiyar University</p>
            <p>Batch:2023-2026</p>
        </section>

            

            

        </div>

    </section>



    <section id="skills">

        <div class="section-content">

            <h2>Skills</h2>

            <ul>

                <li>c</li>

                <li>HTML</li>

                <li>Python</li>

                 <li>java</li>

                <li>c++</li>

                           </ul>

        </div>

    </section>

  <section id="resume">

    

        <div class="section-content">

            <center>

            <h2>Resume</h2>

            <a href="file.pdf" target="_blank" class="download-button">Download CV</a>

        </center>

        </div>

        

    </section>



    <script>

        // Smooth scrolling to section when clicking on navigation links

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {

            anchor.addEventListener('click', function(e) {

                e.preventDefault();



                const targetId = this.getAttribute('href').substring(1);

                const targetElement = document.getElementById(targetId);



                if (targetElement) {

                    window.scrollTo({

                        top: targetElement.offsetTop,

                        behavior: 'smooth'

                    });

                }

            });

        });

    </script>

</body>

</html>
