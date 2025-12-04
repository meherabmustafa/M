
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Meherab Mustafa - Portfolio</title>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

    <style>
        body {
            font-family: "Times New Roman", serif;
            background-color: #121212;
            color: #f5f5f5;
            margin: 0;
            padding: 0;
            text-align: center;
            opacity: 0;
            transition: opacity 0.5s ease-in-out;
        }

        body.loaded { opacity: 1; }

        a { text-decoration: none !important; }

        .container { width: 80%; margin: auto; padding: 40px 0; }

        /* ✅ CLEAN HEADINGS — NO LINE, NO UNDERLINE, NO SHADOW */
        h1, h2 { 
            font-family: 'Kristen ITC', Arial, sans-serif; 
            color: #00bcd4;
            margin-top: 40px;
            margin-bottom: 20px;
            text-decoration: none !important;
            border: none !important;
            box-shadow: none !important;
        }

        h1 { font-size: 28px; }

        .name { font-size: 22px; color: #ffffff; margin: 5px 0; }

        /* ✅ ONLY typing cursor here */
        .animated-text {
            font-size: 18px;
            color: #00ffff;
            border-right: 2px solid #00ffff;
            white-space: nowrap;
            overflow: hidden;
            display: inline-block;
            animation: typing 3s steps(30, end) infinite, blink 0.75s step-end infinite;
        }

        @keyframes typing {
            0%,100% { width: 0; } 
            50% { width: 270px; } 
        }

        @keyframes blink { 50% { border-color: transparent; } }

        img {
            border-radius: 50%;
            margin: 20px 0;
            width: 180px;
        }

        .icons a {
            margin: 0 10px;
            font-size: 24px;
            color: #f5f5f5;
        }

        .icons a:hover { color: #00bcd4; }

        /* ✅ Soft CV button (no hard border look) */
        .cv-button {
            display: inline-block;
            padding: 10px 15px;
            background: #1f1f1f;
            color: #00bcd4;
            font-size: 18px;
            border-radius: 6px;
            margin: 5px;
        }

        .cv-button:hover {
            background-color: #00bcd4;
            color: #121212;
        }

        p {
            line-height: 1.8;
            text-align: justify;
            font-size: 10px;
        }

        .left-text { text-align: left; margin-top: 20px; }

        .contact { text-align: left; margin-top: 40px; }

        .edu-year {
            color: #00ffff;
            font-weight: bold;
            font-size: 12px;
        }

        .left-text li { font-size: 10px; margin-bottom: 12px; }
    </style>
</head>

<body>
<div class="container">

    <h1>HI THERE!</h1>

    <img src="profile.jpg.jpeg" alt="Profile Image">

    <div class="name">I’m Meherab Mustafa</div>
    <div class="animated-text">Bioscience Student & Researcher</div>

    <div class="icons" style="margin-top: 15px;">
        <a href="mailto:Meherabmustafa01@gmail.com"><i class="fa-solid fa-envelope"></i></a>
        <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-USERNAME" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
    </div>

    <div>
        <a href="cv.pdf" download class="cv-button">
            <i class="fa-solid fa-file-arrow-down"></i>
        </a>
    </div>

    <h2>About Me</h2>

    <p>
        Currently, I work as a Research Fellow at 
        <span class="edu-year">Bangladesh Space Research and Remote Sensing Organization (SPARRSO)</span>.
    </p>

    <p>
        Before joining SPARRSO, I worked as a Thesis Researcher at 
        <span class="edu-year">Bangladesh Council of Scientific and Industrial Research (BCSIR)</span>.
    </p>

    <h2>Education</h2>

    <div class="left-text">
        <p><span class="edu-year">2023-2025</span><br>Master of Science in Botany</p>
        <p><span class="edu-year">2018-2023</span><br>Bachelor of Science in Botany</p>
    </div>

    <h2>My Experience</h2>

    <ul class="left-text">
        <li><span class="edu-year">Research Fellow</span> — SPARRSO</li>
        <li><span class="edu-year">Thesis Researcher</span> — BCSIR</li>
    </ul>

    <h2>Contact Me</h2>

    <div class="contact">
        <a href="mailto:Meherabmustafa01@gmail.com" class="cv-button">Personal Email</a>
        <a href="mailto:meherab-2017114310@bot.du.ac.bd" class="cv-button">University Email</a><br><br>
        📞 +8801796498307
    </div>

</div>

<script>
    window.addEventListener('load', () => {
        document.body.classList.add('loaded');
    });
</script>

</body>
</html>

    
