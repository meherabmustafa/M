
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Meherab Mustafa - Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- ✅ FONT -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

    <!-- ✅ ICON -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #000;
            color: #fff;
        }

        section {
            padding: 40px 20px;
        }

        h1, h2 {
            font-family: 'Kristen ITC', 'Poppins', sans-serif;
            color: #00bcd4;
            margin-bottom: 12px;
        }

        /* ✅ HERO SECTION */
        .hero {
            text-align: center;
            padding-top: 60px;
        }

        .hero p {
            font-size: 14px;
            opacity: 0.9;
        }

        .hero img {
            width: 160px;
            border-radius: 50%;
            margin: 16px 0;
        }

        .animated-text {
            font-size: 18px;
            margin-top: 6px;
            color: #00bcd4;
            animation: glow 2s infinite alternate;
        }

        @keyframes glow {
            0% { opacity: 0.6; }
            100% { opacity: 1; }
        }

        /* ✅ CV ICON */
        .cv-icon {
            margin-top: 14px;
            display: inline-block;
            color: #00bcd4;
            font-size: 22px;
            text-decoration: none;
        }

        /* ✅ ABOUT ME */
        #about p {
            font-size: 8px;
            line-height: 1.6;
            opacity: 0.9;
        }

        .highlight {
            color: #00bcd4;
            font-weight: 600;
        }

        /* ✅ EXPERIENCE */
        .experience-item {
            margin-bottom: 18px;
        }

        .position {
            color: #00bcd4;
            font-size: 16px;
            font-weight: 600;
        }

        .duration {
            font-size: 12px;
            opacity: 0.8;
        }

        /* ✅ EDUCATION */
        .edu-item {
            margin-bottom: 18px;
        }

        .year, .institute {
            font-size: 15px;
            font-weight: 600;
            color: #00bcd4;
        }

        .degree, .subject {
            font-size: 13px;
            opacity: 0.9;
        }

        /* ✅ SKILLS */
        .skills span {
            display: inline-block;
            margin: 6px;
            padding: 6px 12px;
            border: 1px solid #00bcd4;
            border-radius: 20px;
            font-size: 13px;
        }

        /* ✅ FOOTER LINKS */
        .links {
            text-align: center;
            margin-top: 20px;
        }

        .links a {
            color: #00bcd4;
            margin: 0 12px;
            text-decoration: none;
            font-size: 18px;
        }

        /* ✅ MOBILE FIX */
        @media (max-width: 768px) {
            h1 {
                font-size: 26px;
            }

            .animated-text {
                font-size: 16px;
            }
        }
    </style>
</head>

<body>

    <!-- ✅ HERO -->
    <section class="hero">
        <p>Hi There</p>

        <img src="your-photo.jpg.jpeg" alt="My Photo">

        <h1>Meherab Mustafa</h1>

        <div class="animated-text">Bioscience Student & Researcher</div>

        <a class="cv-icon" href="cv.pdf" download>
            <i class="fas fa-download"></i>
        </a>
    </section>

    <!-- ✅ ABOUT ME -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am currently working as a research fellow at 
            <span class="highlight">SPARRSO</span> and a thesis researcher at 
            <span class="highlight">BCSIR</span>. My research interest focuses on microbiology, remote sensing and environmental analysis.
        </p>
    </section>

    <!-- ✅ EXPERIENCE -->
    <section class="experience">
        <h2>Experience</h2>

        <div class="experience-item">
            <div class="position">Research Fellow</div>
            <div class="duration">2024 - Present</div>
        </div>

        <div class="experience-item">
            <div class="position">Thesis Researcher</div>
            <div class="duration">2023 - 2024</div>
        </div>
    </section>

    <!-- ✅ EDUCATION -->
    <section class="education">
        <h2>Education</h2>

        <div class="edu-item">
            <div class="year">2023 - 2025</div>
            <div class="institute">MS in Bioscience</div>
            <div class="degree">Master of Science</div>
            <div class="subject">Biological Sciences</div>
        </div>

        <div class="edu-item">
            <div class="year">2018 - 2022</div>
            <div class="institute">BSc in Bioscience</div>
            <div class="degree">Bachelor of Science</div>
            <div class="subject">Biological Sciences</div>
        </div>
    </section>

    <!-- ✅ SKILLS -->
    <section class="skills">
        <h2>Skills</h2>
        <span>Remote Sensing</span>
        <span>Microbiology</span>
        <span>GIS</span>
        <span>Data Analysis</span>
        <span>Research Writing</span>
    </section>

    <!-- ✅ CONTACT LINKS -->
    <div class="links">
        <a href="mailto:yourmail@gmail.com"><i class="fas fa-envelope"></i></a>
        <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com" target="_blank"><i class="fab fa-github"></i></a>
    </div>

</body>
</html>
