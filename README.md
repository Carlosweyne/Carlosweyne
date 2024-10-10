- 👋 Hi, I’m @Carlosweyne
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Carlosweyne/Carlosweyne is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site de Jogos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site de Jogos</h1>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Jogos</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="games">
            <h2>Jogos Disponíveis</h2>
            <div class="game-list">
                <!-- Jogo 1 -->
                <div class="game">
                    <h3>Jogo 1</h3>
                    <iframe src="URL_DO_JOGO_1" width="300" height="200" allowfullscreen></iframe>
                </div>
                <!-- Jogo 2 -->
                <div class="game">
                    <h3>Jogo 2</h3>
                    <iframe src="URL_DO_JOGO_2" width="300" height="200" allowfullscreen></iframe>
                </div>
                <!-- Adicione mais jogos conforme necessário -->
            </div>
        </section>
    </main>

    <footer>
        <p>© 2024 Meu Site de Jogos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

/* Cabeçalho */
header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    margin-top: 10px;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Seção de Jogos */
#games {
    padding: 20px;
    text-align: center;
}

.game-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.game {
    background-color: white;
    padding: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    width: 320px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.game h3 {
    margin-bottom: 10px;
}

/* Rodapé */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 15px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

