<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Your Name - Resume</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #e5e7eb;
            color: #222;
            line-height: 1.5;
        }

        .resume {
            width: 850px;
            max-width: 95%;
            margin: 30px auto;
            background: white;
            padding: 45px 50px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.12);
        }

        /* Header */
        .header {
            text-align: center;
            border-bottom: 2px solid #222;
            padding-bottom: 20px;
            margin-bottom: 25px;
        }

        .header h1 {
            font-size: 34px;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 8px;
        }

        .header h3 {
            font-size: 18px;
            font-weight: normal;
            color: #555;
            margin-bottom: 10px;
        }

        .contact {
            font-size: 14px;
            color: #444;
        }

        .contact span {
            margin: 0 8px;
        }

        /* Sections */
        .section {
            margin-bottom: 24px;
        }

        .section-title {
            font-size: 18px;
            text-transform: uppercase;
            border-bottom: 1px solid #333;
            padding-bottom: 5px;
            margin-bottom: 12px;
            letter-spacing: 1px;
        }

        /* Education */
        .education-item {
            margin-bottom: 15px;
        }

        .education-item h3 {
            font-size: 16px;
        }

        .education-item p {
            font-size: 14px;
            color: #555;
        }

        .date {
            float: right;
            font-size: 14px;
            color: #555;
        }

        /* Skills */
        .skills {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 8px;
        }

        .skills p {
            font-size: 14px;
        }

        /* Projects */
        .project {
            margin-bottom: 16px;
        }

        .project h3 {
            font-size: 16px;
            margin-bottom: 4px;
        }

        .project p {
            font-size: 14px;
            color: #444;
        }

        /* Lists */
        ul {
            padding-left: 20px;
        }

        li {
            font-size: 14px;
            margin-bottom: 5px;
        }

        /* Personal Details */
        .personal-details p {
            font-size: 14px;
            margin-bottom: 5px;
        }

        /* Print Button */
        .print-btn {
            display: block;
            margin: 20px auto;
            padding: 10px 25px;
            background: #222;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 4px;
            font-size: 14px;
        }

        .print-btn:hover {
            background: #444;
        }

        /* Mobile */
        @media (max-width: 600px) {
            .resume {
                padding: 25px;
                margin: 10px auto;
            }

            .header h1 {
                font-size: 27px;
            }

            .date {
                float: none;
                display: block;
            }

            .skills {
                grid-template-columns: 1fr;
            }

            .contact span {
                display: block;
                margin: 3px 0;
            }
        }

        /* Print */
        @media print {
            body {
                background: white;
            }

            .resume {
                width: 100%;
                max-width: 100%;
                margin: 0;
                box-shadow: none;
            }

            .print-btn {
                display: none;
            }
        }
    </style>
</head>

<body>

    <div class="resume">

        <!-- Header -->
        <div class="header">

            <h1>Your Name</h1>

            <h3>Computer Science Student | Web Developer</h3>

            <div class="contact">
                <span>📞 +91 9876543210</span>
                <span>✉️ yourname@gmail.com</span>
                <span>📍 Uttar Pradesh, India</span>
            </div>

            <div class="contact">
                <span>LinkedIn: linkedin.com/in/yourname</span>
                <span>GitHub: github.com/yourname</span>
            </div>

        </div>


        <!-- Career Objective -->
        <div class="section">

            <h2 class="section-title">Career Objective</h2>

            <p>
                Motivated and enthusiastic Computer Science student looking
                for an opportunity to apply my technical skills and knowledge
                in a professional environment. Interested in web development,
                software development, and learning new technologies.
            </p>

        </div>


        <!-- Education -->
        <div class="section">

            <h2 class="section-title">Education</h2>

            <div class="education-item">

                <span class="date">2023 - 2027</span>

                <h3>Bachelor of Technology (B.Tech)</h3>

                <p>
                    Computer Science & Engineering
                </p>

                <p>
                    <strong>Your College Name</strong>,
                    Your University
                </p>

                <p>
                    CGPA: 8.2 / 10
                </p>

            </div>


            <div class="education-item">

                <span class="date">2022 - 2023</span>

                <h3>Class 12th</h3>

                <p>
                    Your School Name, CBSE Board
                </p>

                <p>
                    Percentage: 85%
                </p>

            </div>


            <div class="education-item">

                <span class="date">2020 - 2021</span>

                <h3>Class 10th</h3>

                <p>
                    Your School Name, CBSE Board
                </p>

                <p>
                    Percentage: 88%
                </p>

            </div>

        </div>


        <!-- Technical Skills -->
        <div class="section">

            <h2 class="section-title">Technical Skills</h2>

            <div class="skills">

                <p><strong>Languages:</strong> C, C++, Java, Python</p>

                <p><strong>Web:</strong> HTML, CSS, JavaScript</p>

                <p><strong>Database:</strong> MySQL</p>

                <p><strong>Tools:</strong> Git, GitHub, VS Code</p>

                <p><strong>Concepts:</strong> OOP, Data Structures</p>

                <p><strong>Operating System:</strong> Windows, Linux</p>

            </div>

        </div>


        <!-- Projects -->
        <div class="section">

            <h2 class="section-title">Projects</h2>


            <div class="project">

                <h3>1. Personal Portfolio Website</h3>

                <p>
                    Developed a responsive personal portfolio website using
                    HTML, CSS and JavaScript. The website includes sections
                    for About Me, Skills, Projects and Contact.
                </p>

                <p>
                    <strong>Technologies:</strong>
                    HTML, CSS, JavaScript
                </p>

            </div>


            <div class="project">

                <h3>2. Student Management System</h3>

                <p>
                    Created a student management system to store and manage
                    student records such as name, roll number, course and
                    marks.
                </p>

                <p>
                    <strong>Technologies:</strong>
                    Java, MySQL
                </p>

            </div>


            <div class="project">

                <h3>3. Online Quiz Application</h3>

                <p>
                    Developed an interactive quiz application where users
                    can answer multiple-choice questions and view their
                    final score.
                </p>

                <p>
                    <strong>Technologies:</strong>
                    HTML, CSS, JavaScript
                </p>

            </div>

        </div>


        <!-- Certifications -->
        <div class="section">

            <h2 class="section-title">Certifications</h2>

            <ul>
                <li>Web Development Fundamentals - Online Certification</li>
                <li>Programming in Java - Online Certification</li>
                <li>Introduction to Python - Online Certification</li>
            </ul>

        </div>


        <!-- Languages -->
        <div class="section">

            <h2 class="section-title">Languages</h2>

            <ul>
                <li>Hindi - Native</li>
                <li>English - Professional</li>
            </ul>

        </div>


        <!-- Personal Details -->
        <div class="section personal-details">

            <h2 class="section-title">Personal Details</h2>

            <p><strong>Date of Birth:</strong> DD/MM/YYYY</p>

            <p><strong>Nationality:</strong> Indian</p>

            <p><strong>Location:</strong> Uttar Pradesh, India</p>

            <p><strong>Hobbies:</strong> Coding, Reading, Travelling</p>

        </div>


        <!-- Declaration -->
        <div class="section">

            <h2 class="section-title">Declaration</h2>

            <p>
                I hereby declare that the information provided above is true
                and correct to the best of my knowledge.
            </p>

        </div>

    </div>


    <!-- Print / Download -->
    <button class="print-btn" onclick="window.print()">
        Print / Save as PDF
    </button>

</body>
</html>

