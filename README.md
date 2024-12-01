# kt4html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .upfloar-log {
            display: flex;
        }
        .upfloar-read-f {
            display: flex;
            margin-left: 45em;
            padding-top: 35px;
            
        }
        .upfloar-read {
            display: flex;
            padding-top: 35px;
        }
        .flex-up {
            display: flex;
            justify-content: space-between;
            width: 100%;
            height: 100px;
            
        }
        html, body {
            padding: 0;
            margin: 0;
            font-family: Verdana, Arial, sans-serif;
        }
        body {
            color: #000000;
            font-size: 1.1em;
            padding: 1em;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            
        }
        main {
            display: flex;
            flex-direction: column;
            flex: 11 auto;
            min-height: 100%;
            
        }
        article {
            flex: 2em;
            padding: 1em;
            
        }
        nav, aside {
            flex: 5;
        }
        nav {
            order: -1;
        }
        header, footer {
            flex: 002em;
            text-align: center;
            padding-left: 290px;
            padding-right: 300px;
            
        }
        .glav-gvadrat {
            width: 64em;
            display: flex;
            flex-wrap: wrap;
            
        }
        .box1, .box2, .box3, .box4, .box5, .box6 {
            display: flex;
            text-align: center;
            font-size: 1.1em;
            padding: 1.5em;
            width: 15em;
            height: 15em;
            margin: 10px;
        }
        .box1 { background: black; }
        .box2 { background: orange; }
        .box3 { background: gray; }
        .box4 { background: greenyellow; }
        .box5 { background: grey; }
        .box6 { background: blue; }

        @media screen and (max-width: 1900px) {
            .glav-gvadrat {
            width: 64em;
            display: flex;
            flex-wrap: wrap;
            margin-left: 12em;
        }
        }
        @media screen and (max-width: 1200px) {
            .upfloar-read-f {
                margin-left: 25em;
                padding-top: 35px;
            }
            
        }
        

        @media screen and (max-width: 980px) {
            .upfloar-read-f {
                margin-left: 39em;
                padding-top: 35px;
            }
            .upfloar-read {
                margin-left: 5em;
                margin-right: 5em;
                padding-top: 35px;
            }
            header, footer {
                margin-left: 4em;
                width: 20em;
                height: 15em;
            }
            .glav-gvadrat {
                margin-left: 10em;
                width: 60em;
                display: flex;
                flex-wrap: wrap;
            }
        }

        @media screen and (max-width: 780px) {
            .box1, .box2, .box3, .box4, .box5, .box6 {
                width: 20em;
                height: 20em;
                margin: 10px;
            }
            .glav-gvadrat {
                margin-left: 7em;
                width: 60em;
                display: flex;
                flex-wrap: wrap;
            }
        }

        @media screen and (max-width: 580px) {
            header, footer {
                margin-left: 3em;
                width: 25em;
                height: 15em;
            }
            .glav-gvadrat {
                margin-left: 15em;
                width: 35em;
                display: flex;
                flex-wrap: wrap;
            }
            .box1, .box2, .box3, .box4, .box5, .box6 {
                width: 25em;
                height: 25em;
                margin: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="flex-up">
        <div class="upfloar-log">
            <h1>Nicepage</h1>
        </div>
        <div class="upfloar-read-f">Home</div>
        <div class="upfloar-read">About Company</div>
    </div>

    <header>
        <h1>We'll help manage your business</h1>
        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa.</p>
    </header>

    <main>
        <article>
            <div class="glav-gvadrat">
                <div class="box1">Consultations</div>
                <div class="box2">Strategy</div>
                <div class="box3">Investment</div>
                <div class="box4">Marketing</div>
                <div class="box5">Startups</div>
                <div class="box6">Anti-Crisis</div>
            </div>
        </article>
        <nav></nav>
        <aside></aside>
    </main>
</body>
</html>


