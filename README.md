<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Two Roads to Freedom</title>
    <style>
        /* 
         * Museum Exhibit Theme
         * Using system serif fonts for a classic, historical feel.
         * Colors: Parchment background, dark charcoal text, deep crimson accents.
         */
        
        :root {
            --bg-color: #f7f5f0;
            --text-color: #2c2c2c;
            --accent-color: #8b1e1e;
            --border-color: #d4d0c8;
            --muted-text: #5a5a5a;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: Georgia, 'Times New Roman', Times, serif;
            line-height: 1.8;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            max-width: 900px;
            width: 90%;
            margin: 40px auto;
            padding: 40px;
            background-color: #ffffff;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
            border: 1px solid var(--border-color);
        }

        header {
            text-align: center;
            margin-bottom: 40px;
        }

        h1 {
            font-size: 3.5em;
            font-weight: normal;
            margin: 0 0 15px 0;
            color: #111;
            letter-spacing: 2px;
            text-transform: uppercase;
        }

        .intro-container {
            position: relative;
            padding: 20px 0;
        }

        .intro-container::before,
        .intro-container::after {
            content: '❖';
            display: block;
            color: var(--border-color);
            font-size: 1.2em;
            margin: 10px auto;
        }

        .intro {
            font-style: italic;
            font-size: 1.4em;
            color: var(--muted-text);
            max-width: 700px;
            margin: 0 auto;
            line-height: 1.6;
        }

        nav {
            border-top: 1px solid var(--border-color);
            border-bottom: 1px solid var(--border-color);
            padding: 20px 0;
            margin-bottom: 50px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 30px;
        }

        nav a {
            text-decoration: none;
            color: var(--text-color);
            text-transform: uppercase;
            font-size: 0.85em;
            letter-spacing: 1.5px;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: var(--accent-color);
        }

        main {
            text-align: center;
            padding: 40px 0;
            color: var(--muted-text);
        }

        .exhibit-placeholder {
            border: 1px dashed var(--border-color);
            padding: 40px;
            background-color: var(--bg-color);
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.8em;
            color: var(--muted-text);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2.2em;
            }
            .intro {
                font-size: 1.1em;
            }
            nav ul {
                gap: 15px;
                flex-direction: column;
            }
            .container {
                padding: 20px;
                margin: 20px auto;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Two Roads to Freedom</h1>
            <div class="intro-container">
                <p class="intro">Two peoples walked out of bondage - one crossed a sea, the other crossed a river in a storm.</p>
            </div>
        </header>

        <nav>
            <ul>
                <li><a href="#leaders">The Leaders</a></li>
                <li><a href="#crossing">The Crossing</a></li>
                <li><a href="#long-journey">The Long Journey</a></li>
                <li><a href="#comparison-breaks">Where the Comparison Breaks</a></li>
                <li><a href="#game">The Game</a></li>
                <li><a href="#sources">Sources</a></li>
            </ul>
        </nav>

        <main>
            <div class="exhibit-placeholder" id="exhibit-start">
                <p><em>Please select an exhibit from the navigation menu above to begin exploring the historical parallels between the American Revolution (1776) and the Exodus from Egypt.</em></p>
            </div>
        </main>

        <footer>
            <p>A Historical Comparison Project</p>
        </footer>
    </div>

</body>
</html>
