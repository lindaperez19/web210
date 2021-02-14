<html lang="en">
<head>
<!--
    Linda Perez
    WEB 210
    DQ 4
    February 14th, 2021
-->

    <title>Website Example - WEB 210</title>
    <meta charset="utf-8">
    <style>
        body {
            font-family: Verdana, Geneva, Tahoma, sans-serif;
        }

        #wrapper {
            width: 90%;
            border: thin solid black;
            margin: auto;
            background-color: darkslateblue;
        }

        header {
            color: floralwhite;
            padding: 12px;
            text-align: center;
        }

        h1 {
            font-size: 3m;
        }

        nav {
            display: flex;
            justify-content: center;
        }

        nav>div {
            background-color: #f1f1f1;
            margin: 10px;
            padding: 10px 20px;
            font-size: 20px;
        }

        main {
            display: flex;
        }

        main>div {
            background-color: lightslategray;
            margin: 10px;
            padding: 10px;
            color: white;
        }

        .left {
            flex: 2;
        }

        .right {
            flex: 1;
        }

        footer {
            padding: 10px;
            text-align: center;
            color: white;
            font-size: 1.1em;
        }

        @media only screen and (max-width: 510px) {
            #wrapper {
                width: 100%;
            }

            nav {
                flex-direction: column;
            }

            main {
                flex-direction: column;
            }
        }
    </style>
</head>


    <div id="wrapper">
        <header>
            <h1>Operable, Guideline 2.4 Navigable</h1>
        </header>
    
        <main>
            <div class="middle">
                <h2>Success Criterion 2.4.2 Page Titled: Web pages have titles that describe topic or purpose. </h2>

                <p><a href="https://youtu.be/SxAu5gEVo08">Learn about HTML with this video.</a></p>
                
                <p><a href="https://www.w3schools.com/bootstrap/">Click here for a Bootstrap tutorial with examples.</a></p>


        
            
        </main>
        <footer>
            <p>Copyright&copy;2021</p>
        </footer>
    </div><!-- end of wrapper -->
</body>


