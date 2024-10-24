<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emagreça 10 kg em 30 Dias</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Emagreça 10 kg em 30 Dias</h1>
        <nav>
            <ul>
                <li><a href="#introducao">Introdução</a></li>
                <li><a href="#alimentacao">Alimentação</a></li>
                <li><a href="#exercicios">Exercícios</a></li>
                <li><a href="#motivacao">Motivação</a></li>
                <li><a href="#comunidade">Comunidade</a></li>
            </ul>
        </nav>
    </header>

    <section id="introducao">
        <h2>Introdução</h2>
        <p>Bem-vindo ao programa "Emagreça 10 kg em 30 Dias"! Aqui você receberá dicas de dieta, exercícios e motivação para atingir seu objetivo de forma saudável.</p>
    </section>

    <section id="alimentacao">
        <h2>Módulo de Alimentação</h2>
        <p>Recomendações de dieta para cada semana, incluindo refeições balanceadas e dicas de controle calórico.</p>
        <button id="btnDietaSemana1">Ver Semana 1</button>
        <div id="dietaSemana1" class="hidden">
            <h3>Semana 1</h3>
            <p>Início da sua jornada com alimentos de baixa caloria e muita hidratação.</p>
        </div>
    </section>

    <section id="exercicios">
        <h2>Módulo de Exercícios</h2>
        <p>Plano de exercícios progressivos, começando com caminhadas leves e evoluindo para treinos intensos.</p>
        <button id="btnExercicioSemana1">Ver Semana 1</button>
        <div id="exercicioSemana1" class="hidden">
            <h3>Semana 1</h3>
            <p>Caminhadas diárias e alongamentos para iniciantes.</p>
        </div>
    </section>

    <section id="motivacao">
        <h2>Módulo de Motivação</h2>
        <p>Dicas diárias de motivação e mensagens de sucesso para manter você focado.</p>
    </section>

    <section id="comunidade">
        <h2>Comunidade</h2>
        <p>Troque experiências com outras pessoas e acompanhe seus progressos.</p>
    </section>

    <footer>
        <p>&copy; 2024 Emagreça 10 kg em 30 Dias</p>
    </footer>

    <script src="app.js"></script>
</body>
</html>
/* styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 10px 0;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.hidden {
    display: none;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}
// app.js

document.getElementById("btnDietaSemana1").addEventListener("click", function() {
    var dieta = document.getElementById("dietaSemana1");
    dieta.classList.toggle("hidden");
});

document.getElementById("btnExercicioSemana1").addEventListener("click", function() {
    var exercicio = document.getElementById("exercicioSemana1");
    exercicio.classList.toggle("hidden");
});
