
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Meherab Mustafa - Portfolio</title>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        /* Dark Theme */
        body {
            font-family: "Times New Roman", serif;
            background-color: #121212;
            color: #f5f5f5;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        a { text-decoration: none; transition: color 0.3s, background 0.3s; }

        .container { width: 80%; margin: auto; padding: 40px 0; }

        h1 { font-size: 28px; color: #00bcd4; margin-bottom: 10px; }

        .name { font-size: 22px; color: #ffffff; margin: 5px 0; }

        .animated-text {
            font-size: 18px;
            color: #00ffff; /* cyan */
            border-right: 2px solid #00ffff;
            white-space: nowrap;
            overflow: hidden;
            display: inline-block;
            animation: typing 3s steps(30, end) infinite, blink 0.75s step-end infinite;
        }

        @keyframes typing { 0%,100% { width: 0; } 50% { width: 270px; } }
        @keyframes blink { 50% { border-color: transparent; } }

        img {
            border-radius: 50%;
            margin-top: 20px;
            width: 180px;
        }

        .icons a {
            margin: 0 10px;
            font-size: 24px;
            color: #f5f5f5;
            transition: color 0.3s, transform 0.3s;
        }

        .icons a:hover { color: #00bcd4; transform: scale(1.2); }

        .cv-button {
            display: inline-block;
            padding: 10px 25px;
            border: 1px solid #00bcd4;
            color: #00bcd4;
            font-size: 15px;
            border-radius: 5px;
            margin: 5px;
            transition: 0.3s all;
        }

        .cv-button:hover { background-color: #00bcd4; color: #121212; box-shadow: 0 4px 15px rgba(0,188,212,0.4); }

        h2 {
            color: #00bcd4;
            margin-top: 60px;
            display: inline-block; /* underline removed */
            padding-bottom: 0;
        }

        p { font-size: 16px; line-height: 1.8; text-align: justify; }

        .left-text { text-align: left; margin-top: 20px; }

        .contact { text-align: left; margin-top: 40px; }

        /* Highlight color cyan */
        .highlight { color: #00ffff; font-weight: bold; }
        .edu-year { color: #00ffff; font-weight: bold; }

        @media screen and (max-width: 768px) {
            .container { width: 90%; padding: 20px 0; }
            h1 { font-size: 24px; }
            .name { font-size: 20px; }
            .animated-text { font-size: 16px; }
            img { width: 140px; }
            .cv-button { padding: 8px 18px; font-size: 14px; }
            .icons a { font-size: 20px; }
            p, ul.left-text li { font-size: 15px; }
            h2 { font-size: 20px; }
        }

        @media screen and (max-width: 480px) {
            img { width: 120px; }
            h1 { font-size: 22px; }
            .name { font-size: 18px; }
            .animated-text { font-size: 14px; }
            .cv-button { padding: 6px 15px; font-size: 13px; }
            h2 { font-size: 18px; }
            p, ul.left-text li { font-size: 14px; }
        }

    </style>
</head>

<body>
<div class="container">

    <h1>HI THERE!</h1>
    <div class="name">I’m Meherab Mustafa</div>
    <div class="animated-text">Bioscience Student & Researcher</div>
    <img src="profile.jpg" alt="Profile Image">

    <div class="icons" style="margin-top: 15px;">
        <a href="mailto:meherabmustafa01@gmail.com" target="_blank">
            <i class="fa-solid fa-envelope"></i>
        </a>
        <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
    </div>

    <div>
        <a href="cv.pdf" target="_blank" class="cv-button">Download CV</a>
    </div>

    <!-- About Me -->
    <h2>About Me</h2>
    <p>
        I have an ongoing desire to continually develop my knowledge base across all aspects of Biosciences.
        In this regard, I actively seek out both challenging and meaningful roles that allow me to utilize my
        technical abilities, creative thinking, and research capabilities.
    </p>

    <p>
        Currently, I work as a Research Fellow at Bangladesh Space Research and Remote Sensing Organization (SPARRSO).
        My role involves satellite images analysis, conducting environmental assessments and providing support to
        evidence-based solutions related to Forest Management and Land-Use Planning.
    </p>

    <p>
        Before joining SPARRSO, I worked as a Thesis Researcher at the Industrial Microbiology Laboratory of
        Bangladesh Council of Scientific and Industrial Research (BCSIR) where I engaged in laboratory-based research,
        developed techniques to optimize microbial processes and acquired practical experience in designing
        experiments, analyzing data and producing scientific reports.
    </p>

    <p>
        I am particularly interested in biotechnology, climate-smart agriculture, sustainable land systems,
        environmental development. I enjoy working on multidisciplinary projects, learning new technologies,
        and creating impactful scientific outputs.
    </p>

    <!-- Education -->
    <h2>Education</h2>
    <div class="left-text">
        <p><span class="edu-year">2023-2025</span><br>
        Master of Science in Botany<br>
        University: University of Dhaka, Dhaka-1000, Bangladesh<br>
        GPA: 4.00/4.00<br>
        Thesis: Biotechnological Exploration of Pigment Producing Indigenous Bacteria From Mangrove Environment
        </p>

        <p><span class="edu-year">2018-2023</span><br>
        Bachelor of Science in Botany<br>
        University: University of Dhaka, Dhaka-1000, Bangladesh<br>
        CGPA: 3.80/4.00
        </p>

        <p><span class="edu-year">2015-2017</span><br>
        Higher Secondary Certificate | Science<br>
        Institution: BPATC School and College, Dhaka, Bangladesh<br>
        GPA: 5.00/5.00
        </p>

        <p><span class="edu-year">2013-2015</span><br>
        Secondary School Certificate | Science<br>
        Institution: BPATC School and College, Dhaka, Bangladesh<br>
        GPA: 5.00/5.00
        </p>
    </div>

    <!-- Experience -->
    <h2>My Experience</h2>
    <ul class="left-text">
        <li><strong><span class="highlight">Research Fellow</span>, Forestry Department</strong><br>
            Institute: Bangladesh Space Research and Remote Sensing Organization (SPARRSO)<br>
            Duration: 22 October - Present
        </li>
        <li><strong><span class="highlight">Thesis Researcher</span>, Microbial Biotechnology Department</strong><br>
            Institute: Bangladesh Council of Scientific and Industrial Research (BCSIR)<br>
            Duration: 30 January, 2024 - 30 July, 2025
        </li>
    </ul>

    <!-- Skills -->
    <h2>My Skills</h2>
    <ul class="left-text">
        <li>MS Office (Excel, Word, Powerpoint)</li>
        <li>MEGA 12, Chromas, Originlab software</li>
    </ul>

    <!-- Research Skills -->
    <h2>Research Skills</h2>
    <ul class="left-text">
        <li>Conduct biochemical tests and molecular characterization</li>
        <li>Spectroscopic analysis (FTIR, UV-Vis, HPLC)</li>
        <li>Microscopic analysis, antimicrobial and antioxidant assays, fertility analysis</li>
        <li>Tree-cover mapping, biomass estimation, and forest health assessment</li>
        <li>Remote sensing and satellite data analysis</li>
        <li>GIS & Geospatial analysis</li>
    </ul>

    <!-- Contact -->
    <h2>Contact Me</h2>
    <div class="contact">
        Address: Krishibid Heights, Jahangirnagar Housing Society, B-block, Savar, Dhaka-1340, Bangladesh<br><br>

        <a href="mailto:meherabmustafa01@gmail.com" class="cv-button">meherabmustafa01@gmail.com</a>
        <a href="mailto:meherab-2017114310@bot.du.ac.bd" class="cv-button">meherab-2017114310@bot.du.ac.bd</a><br><br>

        📞 +8801796498307
    </div>

</div>
</body>
</html>
