<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta Kazim Ali ="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kazim Ali | Web Developer</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f5f7fa;
            color: #172033;
            line-height: 1.6;
        }

        header {
            background: #172033;
            color: white;
            padding: 22px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h2 {
            font-size: 22px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 14px;
        }

        .hero {
            min-height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
        }

        .hero h1 {
            font-size: 52px;
            margin-bottom: 15px;
        }

        .hero h1 span {
            color: #2563eb;
        }

        .hero p {
            max-width: 600px;
            font-size: 19px;
            color: #5b6475;
            margin-bottom: 28px;
        }

        .button {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 13px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 70px 8%;
            background: white;
        }

        section h2 {
            text-align: center;
            margin-bottom: 35px;
            font-size: 32px;
        }

        .cards {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .card {
            background: #f5f7fa;
            padding: 25px;
            border-radius: 12px;
            width: 280px;
            text-align: center;
        }

        .card h3 {
            margin-bottom: 10px;
        }

        .card p {
            color: #5b6475;
        }

        .contact {
            text-align: center;
        }

        footer {
            background: #172033;
            color: white;
            text-align: center;
            padding: 22px;
        }

        @media (max-width: 600px) {
            .hero h1 {
                font-size: 38px;
            }

            nav {
                display: none;
            }
        }
    </style>
</head>

<body>

    <header>
        <h2>Kazim Ali</h2>

        <nav>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>

        <div class="hero">
            <h1>Hi, I'm <span>Kazim Ali</span></h1>

            <p>
                I create clean, modern and responsive websites
                for businesses, brands and individuals.
            </p>

            <a class="button" href="#contact">Let's Work Together</a>
        </div>

        <section id="about">
            <h2>About Me</h2>

            <div class="contact">
                <p>
                I'm a basic website developer building skills in some parts of my skills related to
                professional websites. Follow me on this journey.
                </p>
            </div>
        </section>

        <section id="services">
            <h2>What I Do</h2>

            <div class="cards">

                <div class="card">
                    <h3>Web Design</h3>
                    <p>Modern and clean website designs.</p>
                </div>

                <div class="card">
                    <h3>Responsive Websites</h3>
                    <p>Websites that work smoothly on all screen sizes.</p>
                </div>

                <div class="card">
                    <h3>Landing Pages</h3>
                    <p>Professional pages for businesses and personal brands.</p>
                </div>

            </div>
        </section>

        <section id="contact">
            <h2>Let's Work Together</h2>

            <div class="contact">
                <p>Have a project in mind? I'd love to hear about it.</p>
                <br>
                <a class="button" href="itskazimali555email.com">
                    Contact Me
                </a>
            </div>
        </section>

    </main>

    <footer>
        <p>© Kazim Ali . All rights reserved.</p>
    </footer>

</body>
</html>