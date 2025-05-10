<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site cu Jocuri</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            padding: 10px;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        .game-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .game {
            background-color: #fff;
            width: 30%;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .game img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .game h3 {
            padding: 10px;
            font-size: 1.2em;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Site cu Jocuri</h1>
    </header>

    <nav>
        <a href="#">Acasă</a>
        <a href="#">Jocuri Populare</a>
        <a href="#">Despre Noi</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <section>
            <h2>Jocuri Populare</h2>
            <div class="game-section">
                <div class="game">
                    <img src="joc1.jpg" alt="Joc 1">
                    <h3>Jocul 1</h3>
                    <p>Descriere scurtă despre joc.</p>
                    <a href="#">Joacă acum</a>
                </div>
                <div class="game">
                    <img src="joc2.jpg" alt="Joc 2">
                    <h3>Jocul 2</h3>
                    <p>Descriere scurtă despre joc.</p>
                    <a href="#">Joacă acum</a>
                </div>
                <div class="game">
                    <img src="joc3.jpg" alt="Joc 3">
                    <h3>Jocul 3</h3>
                    <p>Descriere scurtă despre joc.</p>
                    <a href="#">Joacă acum</a>
                </div>
            </div>
        </section>

        <section>
            <h2>Contact</h2>
            <form action="#" method="post">
                <label for="name">Nume:</label>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Mesaj:</label><br>
                <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>

                <input type="submit" value="Trimite">
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Site cu Jocuri. Toate drepturile rezervate.</p>
    </footer>

</body>
</html>
