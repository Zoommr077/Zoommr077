-<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seu Nome - Transforme Sua Vida</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Transforme Sua Vida com [Seu Nome]</h1>
        <p>Motivação, desenvolvimento pessoal e mentalidade para o sucesso.</p>
    </header>
    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#servicos">Serviços</a>
        <a href="#blog">Blog</a>
        <a href="#contato">Contato</a>
    </nav>
    <section id="sobre">
        <h2>Quem Sou</h2>
        <p>Olá! Sou [Seu Nome], mentor em desenvolvimento pessoal e motivação. Minha missão é ajudar você a desbloquear seu potencial e viver sua melhor versão.</p>
    </section>
    <section id="servicos">
        <h2>Serviços</h2>
        <ul>
            <li>Mentoria individual</li>
            <li>Cursos online</li>
            <li>Palestras para empresas</li>
        </ul>
    </section>
    <section id="blog">
        <h2>Blog</h2>
        <p>Confira dicas e conteúdos para transformar sua vida:</p>
        <ul>
            <li><a href="#">5 Passos Para Desenvolver Uma Mentalidade Positiva</a></li>
            <li><a href="#">Como Organizar Sua Rotina Para O Sucesso</a></li>
        </ul>
    </section>
    <section id="contato">
        <h2>Contato</h2>
        <p>Entre em contato para saber mais sobre meus serviços:</p>
        <form action="mailto:seuemail@exemplo.com" method="post" enctype="text/plain">
            <label for="nome">Nome:</label><br>
            <input type="text" id="nome" name="nome"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="mensagem">Mensagem:</label><br>
            <textarea id="mensagem" name="mensagem"></textarea><br>
            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 [Seu Nome]. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
