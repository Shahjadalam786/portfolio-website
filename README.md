# portfolio-website
This is portfolio website and Task3 for frontend development .
<br>
CodeAlpha Task 3 complete
<hr>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(13, 13, 37);
            color: white;
            font-family: poppins, sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 60px;
            background-color: rgb(20, 20, 82);
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
            color: rgb(130, 130, 209);
            font-size: 1.1rem;
        }

        main hr {
            border: 0;
            background: rgb(130, 130, 209);
            height: 1.2px;
            margin: 40px 84px;


        }

        .left {
            font-size: 1.6rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 20px 0;
        }

        .firstSection>div {
            width: 20%;
        }

        .leftSection {
            font-size: 1.7rem;
            margin: 20px;
        }

        .rightSection img {
            width: 115%;
            margin: 0;
        }

        .purple {
            color: rgba(22, 198, 241, 0.979);
        }

        #element {
            color: rgba(22, 198, 241, 0.979);
        }

        .text-grey {
            color: grey;
        }

        .secondSection {
            max-width: 78vw;
            margin: auto;
            height: 80vh;
        }

        .secondSection h1 {
            font-size: 1.5rem;
        }

        .secondSection .box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 140px;
        }

        .image-top {
            width: 40px;
            position: relative;
            top: -40px;
            left: -10px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;
        }

        .vertical-dsc {
            position: relative;
            top: 86px;
            color: grey;
            width: 150px;
            font-size: 9px;
        }
        footer{
            background-color: rgb(19, 3, 3);
        }
        .footer{
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }
        .footer ul{
            list-style: none;
        }
        .footer > div{
            width: 90px;
        }
        footer .footer-rights{
            text-align: center;
            color: gray;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Shahjad's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi, My name is <span class="purple">Shahjad Alam</span>
                <div>and I am a passionate</div>
                <div>Web Developer</div>
                <span id="element"></span>
                <div class="button">
                <div class="btn"></div>
                <div class="btn"></div>
                </div>
            </div>
            <div class="rightSection">
                <img src="wpp.png" alt="">

            </div>

        </section>
        <hr>
        <section class="secondSection">
            <span class="text-grey">What I have done so far</span>
            <h1>Work Experience</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="html.png" alt="">
                    <div class="vertical-title">HTML Developer (2022-2024)</div>
                    <div class="vertical-dsc">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Minus, distinctio fugiat commodi fuga, consequuntur et,
                        aliquam pariatur laudantium ab porro iusto eligendi omnis?
                        Dolorem natus, animi ut dignissimos qui asperiores.
                    </div>
                </div>

                <div class="vertical">
                    <img class="image-top" src="nodejs.png" alt="">
                    <div class="vertical-title">Node.js Developer (2022-2024)</div>
                    <div class="vertical-dsc">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Minus, distinctio fugiat commodi fuga, consequuntur et,
                        aliquam pariatur laudantium ab porro iusto eligendi omnis?
                        Dolorem natus, animi ut dignissimos qui asperiores.
                    </div>
                </div>

                <div class="vertical">
                    <img class="image-top" src="instagram.png" alt="">
                    <div class="vertical-title">Instagram Exception handling (2022-till now)</div>
                    <div class="vertical-dsc">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Minus, distinctio fugiat commodi fuga, consequuntur et,
                        aliquam pariatur laudantium ab porro iusto eligendi omnis?
                        Dolorem natus, animi ut dignissimos qui asperiores.
                    </div>
                </div>

                <div class="vertical">
                    <img class="image-top" src="facebook.png" alt="">
                    <div class="vertical-title">facebook page handling (2020-2024)</div>
                    <div class="vertical-dsc">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit.
                        Minus, distinctio fugiat commodi fuga, consequuntur et,
                        aliquam pariatur laudantium ab porro iusto eligendi omnis?
                        Dolorem natus, animi ut dignissimos qui asperiores.
                    </div>
                </div>

            </div>
        </section>
    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Shahjad's Developer Portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact</li>
                    <li>Projects</li>
                </ul>
            </div>
            <div class="footer-third">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact</li>
                    <li>Projects</li>
                </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact</li>
                    <li>Projects</li>
                </ul>
            </div>
        </div>
        <div class="footer-rights">
            Copyright&#169;shahjadportfolio.com | All right reserved
        </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Graphic Designer', 'Web Designer', 'Creator'],
            typeSpeed: 150,
        });
    </script>
</body>

</html>