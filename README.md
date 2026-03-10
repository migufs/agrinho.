<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agro Forte, Futuro Sustentável: Equilíbrio entre Produção e Meio Ambiente</title>
    <link rel="stylesheet" href="styles.css">  <!-- Link para o CSS -->
</head>
<body>

    <header>
        <h1>Agro Forte, Futuro Sustentável: Equilíbrio entre Produção e Meio Ambiente</h1>
    </header>

    <main>
        <section>
            <h2>1. A Importância do Agro no Brasil e no Mundo</h2>
            <p>A agricultura e a pecuária são essenciais para abastecer a população mundial e impulsionar a economia. No Brasil, o agronegócio responde por uma grande parte do PIB e é responsável por uma significativa parcela das exportações.</p>
        </section>

        <section>
            <h2>2. O Conceito de Sustentabilidade no Agro</h2>
            <p>A sustentabilidade no agro envolve práticas que preservam o meio ambiente, respeitam os direitos dos trabalhadores e são economicamente viáveis.</p>
        </section>

        <section>
            <h2>3. Tecnologias para um Agro Sustentável</h2>
            <p>Inovações tecnológicas como a agricultura de precisão e o uso de biotecnologia têm sido grandes aliadas para otimizar a produção e minimizar os impactos ambientais.</p>
        </section>

        <section>
            <h2>4. Desafios e Oportunidades</h2>
            <p>A pressão para aumentar a produção e a escassez de recursos naturais são desafios constantes. Mas, o mercado está cada vez mais exigente com relação à responsabilidade ambiental.</p>
        </section>

        <section>
            <h2>5. A Educação Ambiental e o Papel dos Jovens</h2>
            <p>Estudantes desempenham um papel fundamental no futuro da agricultura sustentável. A educação ambiental é essencial para formar líderes que saibam balancear produção e conservação.</p>
        </section>

        <button id="loadArticle" onclick="showArticle()">Leia o artigo completo</button>  <!-- Botão com evento JavaScript -->

    </main>

    <footer>
        <p>Para mais informações sobre o tema, consulte o artigo completo sobre o Agro Sustentável.</p>
        <a href="https://www.exemplo.com/agro-forte-futuro-sustentavel" target="_blank">Clique aqui para ler</a>
    </footer>

    <script src="script.js"></script>  <!-- Link para o arquivo JavaScript -->
</body>
</html>

/* styles.css */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

header {
    background-color: #2E8B57; /* Verde escuro */
    color: white;
    text-align: center;
    padding: 20px;
}

h1 {
    font-size: 2.5em;
}

main {
    padding: 20px;
}

section {
    background-color: white;
    margin-bottom: 20px;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #2E8B57;
    font-size: 1.5em;
}

p {
    font-size: 1.1em;
}

button {
    background-color: #2E8B57;
    color: white;
    font-size: 1.2em;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 20px;
}

button:hover {
    background-color: #218c44;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

footer a {
    color: #2E8B57;
    text-decoration: none;
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}

// script.js

function showArticle() {
    alert("Você será redirecionado para o artigo completo sobre 'Agro Forte, Futuro Sustentável: Equilíbrio entre Produção e Meio Ambiente'.");
    // Redireciona o usuário após o alerta
    window.open("https://www.exemplo.com/agro-forte-futuro-sustentavel", "_blank");
}
