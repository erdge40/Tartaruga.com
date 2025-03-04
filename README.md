# Tartaruga.com
Um site para ajudar contra a depressão está em demorar ainda 

------------------------------------------

<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tartaruga - Conversa Amiga</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #89CFF0, #F0E68C);
            color: #333;
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #2F4F4F;
            font-size: 36px;
        }

        p {
            font-size: 18px;
        }

        button {
            background-color: #2F4F4F;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 20px;
            cursor: pointer;
            border-radius: 10px;
            margin-top: 20px;
        }

        button:hover {
            background-color: #1E3636;
        }
    </style>
</head>
<body>
    <h1>🐢 Tartaruga - Conversa Amiga</h1>
    <p>Se precisar conversar, estou aqui para ajudar!</p>
    <button onclick="iniciarChat()">Iniciar Conversa</button>

    <script>
        function iniciarChat() {
            let nome = prompt("Qual é o seu nome?");
            if (!nome) nome = "amigo";
            
            let idade = prompt("Quantos anos você tem?");
            alert(`Olá, ${nome}! Se eu não me engano, você tem ${idade} anos.`);

            let resposta = prompt("O que você procura?");
            alert(`${resposta}? Entendi... Vamos conversar um pouco.`);

            if (resposta.toLowerCase() === "eu não sei") {
                alert("Olha, pra facilitar o serviço, eu vou fazer umas perguntinhas e você responde, tá?");
            }

            let perguntafuma = prompt("Você fuma? (sim/não)");
            alert(perguntafuma.toLowerCase() === "sim" ? "Não é legal, mas tudo bem." : "Ótimo!");

            let perguntatrauma = prompt("Você tem algum trauma? (sim/não)");
            alert(perguntatrauma.toLowerCase() === "sim" ? "Entendi, espero que você esteja bem!" : "Que bom!");

            let perguntalugar = prompt("Você está aonde?");
            if (perguntalugar.toLowerCase() === "casa") {
                alert("Beleza.");
            } else if (perguntalugar.toLowerCase() === "escola") {
                alert("Seu safado, mexendo no celular na aula kkk.");
            } else if (perguntalugar.toLowerCase() === "rua") {
                alert("Estranho, mas beleza.");
            } else if (perguntalugar.toLowerCase() === "ônibus") {
                alert("Bem, a nossa conversa só vai durar mais 15 ou 10 minutos, mas eu acho que dá pra terminar.");
            }

            let perguntasemata = prompt("Você já quis se matar? (sim/não)");
            alert(perguntasemata.toLowerCase() === "sim" ? "Pode relaxar, estou aqui para te ajudar." : "Tudo bem.");

            // **Novas perguntas**
            let perguntafeliz = prompt("Você tem se sentido feliz ultimamente? (sim/não)");
            alert(perguntafeliz.toLowerCase() === "não" ? "Poxa, espero que as coisas melhorem para você. Quer conversar sobre isso?" : "Muito bom! Continue assim.");

            let perguntacoisasboas = prompt("O que te faz feliz? (exemplo: ouvir música, jogar, desenhar)");
            alert(`Isso é ótimo! Sempre que estiver se sentindo mal, tente fazer mais disso: ${perguntacoisasboas}. Pode te ajudar bastante!`);

            let perguntasaudemental = prompt("Você sente que sua saúde mental está boa? (sim/não)");
            alert(perguntasaudemental.toLowerCase() === "não" ? "Se precisar de apoio, não tenha medo de falar com alguém de confiança." : "Ótimo! Cuidar da mente é tão importante quanto cuidar do corpo.");

            let perguntaanimais = prompt("Você gosta de animais? (sim/não)");
            alert(perguntaanimais.toLowerCase() === "sim" ? "Animais são ótimos companheiros, né? Se tiver um, cuide bem dele!" : "Tudo bem, cada um tem seus gostos.");

            let perguntatempo = prompt("Você sente que tem tempo suficiente para descansar e se divertir? (sim/não)");
            alert(perguntatempo.toLowerCase() === "não" ? "Tente organizar melhor seu tempo, descanso também é importante." : "Ótimo! Ter equilíbrio entre obrigações e lazer é essencial.");

            let perguntacomida = prompt("Você tem se alimentado bem? (sim/não)");
            alert(perguntacomida.toLowerCase() === "não" ? "Tente comer melhor, sua saúde agradece!" : "Ótimo! Alimentação saudável faz diferença.");

            let perguntarede = prompt("Você passa muito tempo nas redes sociais? (sim/não)");
            alert(perguntarede.toLowerCase() === "sim" ? "Tente dar umas pausas, às vezes o excesso pode fazer mal." : "Isso é bom! Muito tempo na internet pode ser cansativo.");

            let perguntametodos = prompt("Você tem algum método para lidar com momentos difíceis? (sim/não)");
            alert(perguntametodos.toLowerCase() === "não" ? "Talvez seja bom encontrar algo que te acalme, como ouvir música, sair um pouco ou conversar com alguém." : "Ótimo! Ter um método para lidar com dificuldades é essencial.");

            alert("Obrigado por responder! Se precisar conversar de novo, estou por aqui.");
        }
    </script>
</body>
</html>
