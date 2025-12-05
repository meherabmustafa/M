
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Portfolio - Experience & Skills</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
    <style>
        /* Paste your CSS here exactly as you gave me */
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

        /* Headings */
        h1, h2 {
            font-family: 'Arial Black', Arial, sans-serif;
            color: #00bcd4;
            margin-top: 40px;
            margin-bottom: 15px;
            border-bottom: none !important;
            text-decoration: none !important;
        }
        h1 { font-size: 28px; }
        h2 { font-size: 24px; }

        /* Profile */
        .name { font-size: 22px; color: #ffffff; margin: 5px 0; }
        .animated-text {
            font-size: 18px;
            color: #00ffff;
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
            margin: 20px 0;
            width: 180px;
        }

        /* Icons */
        .icons a {
            margin: 0 10px;
            font-size: 24px;
            color: #f5f5f5;
            transition: color 0.3s, transform 0.3s;
        }
        .icons a:hover { color: #00bcd4; transform: scale(1.2); }

        /* CV button */
        .cv-button {
            display: inline-block;
            padding: 10px 15px;
            border: 1px solid #00bcd4;
            color: #00bcd4;
            font-size: 18px;
            border-radius: 5px;
            margin: 5px;
            transition: 0.3s all;
        }
        .cv-button:hover { background-color: #00bcd4; color: #121212; box-shadow: 0 4px 15px rgba(0,188,212,0.4); }

        /* Paragraphs */
        p { line-height: 1.6; text-align: justify; font-size: 12px; }

        .left-text { text-align: left; margin-top: 20px; }
        .contact { text-align: left; margin-top: 40px; }

        /* Highlight cyan */
        .edu-year { color: #00ffff; font-weight: bold; }

        ul.left-text li { font-size: 12px; margin-bottom: 12px; }

        /* Card style for Experience / Skills / Research Skills */
        .card {
            background: #1a1a1a;
            padding: 20px;
            margin: 20px 0;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0, 255, 0, 0.1);
            border-left: 6px solid #00ff66;
            transition: 0.3s;
            text-align: left;
        }

        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 25px rgba(0, 255, 0, 0.2);
        }

        .card-title {
            color: #00ff66;
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .card p {
            margin: 5px 0;
            line-height: 1.6;
            font-size: 13px;
            color: #e0e0e0;
        }

        @media screen and (max-width: 768px) {
            .container { width: 90%; padding: 20px 0; }
            h1 { font-size: 24px; }
            h2 { font-size: 22px; }
            .name { font-size: 20px; }
            .animated-text { font-size: 16px; }
            img { width: 140px; }
            .cv-button { padding: 8px 12px; font-size: 16px; }
            .icons a { font-size: 20px; }
            p, ul.left-text li { font-size: 11px; }
        }

        @media screen and (max-width: 480px) {
            img { width: 120px; }
            h1 { font-size: 22px; }
            h2 { font-size: 20px; }
            .name { font-size: 18px; }
            .animated-text { font-size: 14px; }
            .cv-button { padding: 6px 10px; font-size: 14px; }
            p, ul.left-text li { font-size: 10px; }
        }
    </style>
</head>
<body>

    <div class="container">

        <h1>Experience</h1>

        <div class="card">
            <div class="card-title">Thesis Researcher at BCSIR - Industrial Microbiology Lab</div>
            <p>Worked on microbial pigments and industrial microbiology research, developing expertise in lab techniques and scientific analysis.</p>
            <p><span class="edu-year">2023 - 2024</span></p>
        </div>

        <div class="card">
            <div class="card-title">Research Assistant at SPARRSO</div>
            <p>Conducted remote sensing data analysis and GIS mapping to support environmental monitoring projects.</p>
            <p><span class="edu-year">2024 - Present</span></p>
        </div>

        <h1>Skills</h1>

        <div class="card">
            <div class="card-title">Technical Skills</div>
            <ul class="left-text">
                <li>Remote Sensing & GIS (Google Earth Engine, QGIS)</li>
                <li>Programming (Python, R)</li>
                <li>Data Analysis and Visualization</li>
                <li>Laboratory Techniques in Microbiology</li>
            </ul>
        </div>

        <h1>Research Skills</h1>

        <div class="card">
            <div class="card-title">Research Competencies</div>
            <ul class="left-text">
                <li>Design and execution of laboratory experiments</li>
                <li>Scientific data collection and analysis</li>
                <li>Literature review and technical writing</li>
                <li>Remote sensing image processing and classification</li>
            </ul>
        </div>

    </div>

</body>
</html>
