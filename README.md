<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background: radial-gradient(circle 400px at 45% 40%, rgba(102,51,153,1) 0%, rgba(0,0,0,1) 50%);
            color: white;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            text-align: center;
        }
        .neumorphic-container {
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
            backdrop-filter: blur(10px);
            background: linear-gradient(135deg, #302b63, #1e202f); /* Example gradient */
        }
        /* Additional gradient styles from second HTML for different sections */
        .neumorphic-container.research {
            background: linear-gradient(155deg, #312c64, #20232a);
        }
        .neumorphic-container.publications {
            background: linear-gradient(125deg, #322d65, #232634);
        }
    </style>
</head>
<body class="min-h-screen flex items-center justify-center">
    <div class="container">
        <section>
            <h1 class="text-6xl font-semibold">Jonas Ballweg</h1>
            <p class="text-xl">PhD Student</p>
            <p class="text-xl">Hong Kong University of Science and Technology (HKUST)</p>
            <p><a href="mailto:jonas.ballweg@tum.de" class="hover:text-purple-300 transition duration-300">jonas.ballweg@tum.de</a></p>
            <p><a href="https://www.linkedin.com/in/jonas-ballweg" class="hover:text-purple-300 transition duration-300">linkedin.com/in/jonas-ballweg</a></p>
            <p>Email: <a href="https://github.com/jonasballweg" class="hover:text-purple-300 transition duration-300">github.com/jonasballweg</a></p>
        </section>
        <section class="neumorphic-container research">
            <h2 class="text-4xl font-semibold">Research</h2>
            <p>I am a PhD student at HKUST, where I am part of the research group called ALPACAS (Algorithms, Logic, Program Analysis, Cryptocurrencies And Smart contracts). My supervisors are Amir K. Goharshady and Dimitris Papadopoulos.</p>
        </section>
        <section class="neumorphic-container publications">
            <h2 class="text-4xl font-semibold">Publications</h2>
            <ul>
                <li><a href="https://hal.science/hal-04268058/" class="hover:text-purple-300 transition duration-300">(IEEE Blockchain'2023) PureLottery: Fair Leader Election Without Decentralized Random Number Generation.</a></li>
            </ul>
        </section>
    </div>
</body>
</html>
