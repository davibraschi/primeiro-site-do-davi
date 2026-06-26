<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alura - Meu Portfólio</title>
    
    <!-- CSS: Estilo inspirado no padrão Alura -->
    <style>
        body {
            font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, Courier, monospace;
            background-color: #04152e; /* Fundo azul escuro clássico da Alura */
            color: #ffffff;
            text-align: center;
            margin: 0;
            padding: 40px 20px;
        }

        .container {
            max-width: 600px;
            margin: 0 auto;
            background-color: #0a2540; /* Card um pouco mais claro */
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            border: 1px solid #00d2df; /* Detalhe em ciano */
        }

        h1 {
            color: #00d2df; /* Cor de destaque para o título */
            font-size: 28px;
            margin-bottom: 10px;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
            color: #ccd6f6;
        }

        button {
            background-color: #1565c0;
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 16px;
            font-weight: bold;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            transition: background 0.3s ease;
        }

        button:hover {
            background-color: #00d2df;
            color: #04152e;
        }
    </style>
</head>
<body>

    <!-- HTML: Estrutura da Página -->
    <div class="container">
        <h1>Olá, Mundo! 🚀</h1>
        <p>Esse é o meu primeiro site desenvolvido para meu curso <strong>Alura</strong>.</p>
        <p>Eu aprendi a fazer sites e entender a estrutura do HTML, e a programação com JavaScript para criar sites.</p>
        
        <!-- Botão que ativa a interação ensinada na aula -->
        <button onclick="primeiraInteracao()">Iniciar Interação</button>
    </div>

    <!-- JavaScript: Lógica de Interação da Aula -->
    <script>
        function primeiraInteracao() {
            // Criação de variáveis simples, exatamente como ensinado no início da lógica
            let nomeEstudante = prompt("Qual é o seu nome, Dev?");
            
            // Verifica se o usuário digitou algo
            if (nomeEstudante != null && nomeEstudante != "") {
                alert("Parabéns, " + nomeEstudante + "! Você acabou de executar sua primeira linha de JavaScript no seu próprio site! 💻✨");
            } else {
                alert("Olá! Não se esqueça de digitar seu nome na próxima vez! 😉");
            }
        }
    </script>

</body>
</html>
