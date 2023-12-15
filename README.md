<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Arial Italic', serif; 
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header.hero {
            background: url('bg.png') center/cover no-repeat;
            color: #f9f9f9;
            text-align: center;
            padding: 100px 20px;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
            color: black;
            border: 1px solid red; /* Red border for each letter */
            display: inline-block; /* Display as block to apply border to each letter */
            padding: 5px; /* Padding for spacing between border and text */
        }

        .hero p {
            font-size: 1.2em;
            margin-bottom: 40px;
            color: black;
            border: 1px solid red; /* Red border for each letter */
            display: inline-block; /* Display as block to apply border to each letter */
            padding: 5px; /* Padding for spacing between border and text */
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 20px 0;
            text-decoration: none;
            background-color: #006400; /* Dark Green */
            color: #fff;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #8FBC8F; /* Light Green on hover */
        }

        .internship-program {
            text-align: center;
            padding: 50px 20px;
        }

        .internship-program h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #006400; /* Dark Green for heading */
        }

        .internship-program p {
            font-size: 1.2em;
            margin-bottom: 10px;
            color: #555; /* Add color to paragraphs */
        }

        .internship-details {
            font-size: 1em;
            margin-bottom: 40px;
        }

        .apply-btn {
            background-color: #8FBC8F; /* Light Green Apply Button */
            color: #fff;
            text-decoration: none;
            padding: 8px 15px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .apply-btn:hover {
            background-color: #3CB371; /* Darker Light Green on hover */
        }

        .cta {
            text-align: center;
            background-color: #006400; /* Dark Green */
            color: #fff;
            padding: 50px 20px;
        }

        .contact {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
    </style>
    <title>VaultofCodes Internships</title>
</head>
<body>

    <header class="hero">
        <div class="hero-content">
            <h1>VaultofCodes Internships</h1>
            <p>Unlock your potential with our exciting internship programs.</p>
            <a href="https://vaultofcodes.com/pages/web-development-internship" class="btn">Web Development Internship</a>
            <a href="https://vaultofcodes.com/pages/app-development-internship" class="btn">App Development Internship</a>
            <a href="https://vaultofcodes.com/pages/python-programming-internship" class="btn">Python Programming Internship</a>
            <a href="https://vaultofcodes.com/pages/java-programming-internship" class="btn">Java Programming Internship</a>
            <a href="https://docs.google.com/forms/d/e/1FAIpQLSdswbRqtnCc4ruOsa968TXJP52ZWUPcl8C0B6sQW7_HkqgsZQ/viewform" class="btn">Canva Designing Internship</a>
          </div>
    </header>

    <section id="web-development" class="internship-program">
        <h2>Web Development Internship Program</h2>
        <p>Discover the exciting possibilities of web development. Master the most relevant technologies and create practical web products with the help of expert mentors.</p>
        <p class="internship-details">Duration: 2 months | Location: Virtual | Start Date: December 15, 2023</p>
        <a href="https://vaultofcodes.com/pages/web-development-internship" class="apply-btn">Apply Here</a>
    </section>

    <section id="app-development" class="internship-program">
        <h2>App Development Internship Program</h2>
        <p>Explore the craft of building mobile apps. Develop practical skills in app creation and keep up with the latest trends and innovations in mobile technology.</p>
        <p class="internship-details">Duration: 2 months | Location: Virtual | Start Date: January 1, 2024</p>
        <a href="https://vaultofcodes.com/pages/app-development-internship" class="apply-btn">Apply Here</a>
    </section>

    <section id="python-programming" class="internship-program">
        <h2>Python Programming Internship Program</h2>
        <p>Investigate the diverse capabilities of Python programming. Examine how it can be applied in different fields and address complex problems through programming tasks.</p>
        <p class="internship-details">Duration: 2 months | Location: Virtual | Start Date: January 1, 2024</p>
        <a href="https://vaultofcodes.com/pages/python-programming-internship" class="apply-btn">Apply Here</a>
    </section>

    <section id="java-programming" class="internship-program">
        <h2>Java Programming Internship Program</h2>
        <p>Learn the essential concepts of Java programming. Create reliable and fast applications, and acquire a strong base in one of the most popular programming languages.</p>
        <p class="internship-details">Duration: 2 months | Location: Virtual | Start Date: December 15, 2023</p>
        <a href="https://vaultofcodes.com/pages/java-programming-internship" class="apply-btn">Apply Here</a>
    </section>

    <section id="canva-designing" class="internship-program">
        <h2>Canva Designing Internship Program</h2>
        <p>Enhance your creative skills with Canva designing. Master the fundamentals of graphic design, produce eye-catching content, and communicate your vision through captivating visuals.</p>
        <p class="internship-details">Duration: 2 months | Location: Virtual | Start Date: April 1, 2024</p>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSdswbRqtnCc4ruOsa968TXJP52ZWUPcl8C0B6sQW7_HkqgsZQ/viewform" class="apply-btn">Apply Here</a>
    </section>

    <section class="cta">
        <p>Ready to elevate your skills?</p>
        <a href="#contact" class="btn">Contact Us</a>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>For inquiries and more information, reach out to us:</p>
        <p>Email: info@vaultofcodes.com</p>
        <p>Phone: (555) 123-4567</p>
    </section>

</body>
</html>
