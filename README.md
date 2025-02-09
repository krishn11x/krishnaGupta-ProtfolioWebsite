# krishnaGupta-ProtfolioWebsite

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krishna - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(1, 1, 28);
            color: white;
            font-family: "Poppins", serif;

        }


        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(12, 12, 70);
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;

        }

        nav ul li a {
            text-decoration: none;
            color: white;

        }

        nav ul li a:hover {
            color: rgb(65, 65, 141);
            font-size: 1.023rem;
        }

        main hr {
            border: 0;
            height: 1.2px;
            background-color: #9c97f1;
            margin: 60px 84px;
        }

        .left {

            font-size: 1.5rem;

        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 80px 0;
        }

        .firstSection>div {
            width: 30%;

        }

        .leftSection {
            width: 30%;
            font-size: 2.4rem;
        }

        .rightSection img {
            width: 80%;

        }

        .purple {
            color: rgb(155, 89, 182);
        }

        .text-gray {
            color: gray;
        }

        #element {
            color: rgb(155, 89, 182);
        }

        .secondSection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondSection h1 {
            font-size: 1.9rem;

        }

        .secondSection .box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
            justify-content: space-around;

        }

        .secondSection .vertical {
            background: rgb(255, 255, 255);
            width: 1px;
            height: 93px;
            margin: 0 100px;

        }
        

        .vertical-title {}

        .vertical-desc {}
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Krishna's Portfolio</div>
            <div class="right"></div>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Services</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Contact me</a></li>

            </ul>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi, I am <span class="purple">Krishna</span>
                <div> And i am a passionate</div>

                <span id="element"></span>

            </div>
            <div class="rightSection">
                <img src="bg4.png" alt="">
            </div>


            </div>


        </section>
        <hr>
        <section class="secondSection">

            <span class="text-gray">What i have done till now</span>

            <h1>Past Experience</h1>


            <div class="box">
                <div class="vertical">
                    
                
                <div class="vertical-title">
                    HTML Developer (2010-2012)
                    </div>
                    <div class="vertical-desc">
                    
                    </div>
                </div>
                
                <div class="vertical">
                    node.js developer
                </div>

                <div class="vertical"></div>
                <div class="vertical"></div>
            </div>
        </section>
    </main>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

    <!-- Setup and start animation! -->
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Web Designer', 'Freelancer', 'Video Editor', 'Photographer', 'Content Creator', 'Digital Marketer',],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
