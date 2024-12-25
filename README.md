# Khabibelrey.fr-
Site web qui représente KHABIB
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khabib Nurmagomedov</title>
    <style>
        /* Global Style */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Khabib_Nurmagomedov_with_the_UFC_Lightweight_Belt.jpg/640px-Khabib_Nurmagomedov_with_the_UFC_Lightweight_Belt.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            scroll-behavior: smooth;
        }

        /* Overlay to improve text readability */
        body::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
            z-index: -1;
        }

        /* Header Style */
        header {
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            padding: 1rem 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }

        header h1 {
            margin: 0;
            animation: fadeIn 2s ease-in-out;
        }

        /* Navigation Menu */
        nav {
            margin-top: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.2rem;
            padding: 5px 10px;
            transition: background-color 0.3s, transform 0.3s;
        }

        nav ul li a:hover {
            background-color: white;
            color: black;
            transform: scale(1.1);
            border-radius: 5px;
        }

        /* Section Style */
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
            animation: fadeInUp 1s ease-in-out;
        }

        h2 {
            color: #ffcc00;
            margin-top: 0;
        }

        p {
            line-height: 1.6;
        }

        .image {
            text-align: center;
            margin: 20px 0;
        }

        .image img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.7);
        }

        /* Animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Khabib Nurmagomedov</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#career">Career</a></li>
                <li><a href="#legacy">Legacy</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <div class="container" id="about">
        <h2>About Khabib</h2>
        <p>
            Khabib Nurmagomedov, also known as "The Eagle," is a former professional mixed martial artist from Russia. 
            He is widely regarded as one of the greatest fighters in MMA history. Khabib competed in the lightweight division of the UFC, 
            where he became the undefeated champion with a record of 29-0.
        </p>
    </div>

    <!-- Career Section -->
    <div class="container" id="career">
        <h2>Career Achievements</h2>
        <p>
            - UFC Lightweight Champion<br>
            - Undefeated record of 29-0<br>
            - Defeated notable fighters such as Conor McGregor, Dustin Poirier, and Justin Gaethje.<br>
        </p>
        <div class="image">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/66/Khabib_at_UFC_242.jpeg/800px-Khabib_at_UFC_242.jpeg" alt="Khabib Nurmagomedov during UFC">
        </div>
    </div>

    <!-- Legacy Section -->
    <div class="container" id="legacy">
        <h2>Legacy</h2>
        <p>
            In 2020, after his victory against Justin Gaethje, Khabib announced his retirement from MMA, fulfilling a promise 
            he made to his mother. His legacy remains unmatched, and he continues to inspire fighters around the world.
        </p>
    </div>
</body>
</html>