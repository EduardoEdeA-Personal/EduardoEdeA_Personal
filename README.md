<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eduardo EDeA - Consultoria Fitness</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Eduardo EDeA - Consultoria Fitness</h1>
        <nav>
            <ul>
                <li><a href="#consultoria">Consultoria</a></li>
                <li><a href="#suplementacao">Suplementação</a></li>
                <li><a href="#materiais">Materiais de Academia</a></li>
                <li><a href="#produtos-digitais">Produtos Digitais</a></li>
                <li><a href="#pagamento">Pagamento</a></li>
                <li><a href="#gerador-treinos">Gerador de Treinos</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="consultoria">
        <h2>Consultoria Fitness</h2>
        <p>Transforme seu corpo com um acompanhamento profissional.</p>
        <button>Saiba mais</button>
    </section>
    
    <section id="suplementacao">
        <h2>Suplementação</h2>
        <p>Os melhores suplementos para potencializar seus resultados.</p>
        <button>Ver produtos</button>
    </section>
    
    <section id="materiais">
        <h2>Materiais de Academia</h2>
        <p>Equipamentos essenciais para seus treinos.</p>
        <button>Comprar agora</button>
    </section>
    
    <section id="produtos-digitais">
        <h2>Produtos Digitais</h2>
        <p>Ebooks, planos de treino e muito mais.</p>
        <button>Acesse já</button>
    </section>
    
    <section id="pagamento">
        <h2>Área de Pagamento</h2>
        <p>Facilidade e segurança para suas compras.</p>
        <button>Finalizar Compra</button>
    </section>
    
    <section id="gerador-treinos">
        <h2>Gerador de Treinos</h2>
        <p>Personalize seu treino de forma gratuita.</p>
        <button>Começar</button>
    </section>
    
    <footer>
        <h3>Siga-me nas redes sociais:</h3>
        <ul>
            <li><a href="https://www.youtube.com/@EduardoEDeA" target="_blank">YouTube</a></li>
            <li><a href="https://www.tiktok.com/@eduardoedea_personal" target="_blank">TikTok</a></li>
            <li><a href="https://www.instagram.com/eduardoedea_personal/" target="_blank">Instagram</a></li>
        </ul>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
}

header {
    background-color: #222;
    color: white;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
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

section {
    padding: 50px;
    background-color: white;
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

button {
    background-color: #ff7f00;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 16px;
    border-radius: 5px;
}

button:hover {
    background-color: #cc6600;
}

footer {
    background-color: #222;
    color: white;
    padding: 20px;
    margin-top: 20px;
}

/* Estilo para formulário de treino */
form {
    display: flex;
    flex-direction: column;
    max-width: 400px;
    margin: 0 auto;
}

input, select, textarea {
    margin-bottom: 10px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

/* Estilo para a área de upload de fotos */
#upload-fotos {
    padding: 20px;
    background: #fff;
    margin: 20px auto;
    border-radius: 10px;
    width: 50%;
    text-align: center;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

#upload-fotos input {
    margin-top: 10px;
}
