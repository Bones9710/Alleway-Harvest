# Alleway Harvest

Ce projet est un chatbot simple pour le site web d'Alleway Harvest. Il répond aux questions des visiteurs sur les produits, notamment la liqueur de guavaberry.

## 🚀 Fonctionnalités
- Répond aux questions sur les produits et les prix
- Donne des informations sur l'entreprise
- Facile à intégrer sur un site web

## 📜 Code du Chatbot
```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatbot Alleway Harvest</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        #chatbox { width: 80%; max-width: 500px; margin: auto; border: 1px solid #ccc; padding: 10px; border-radius: 10px; }
        #messages { height: 300px; overflow-y: scroll; border-bottom: 1px solid #ccc; padding: 5px; text-align: left; }
        input { width: 80%; padding: 10px; }
        button { padding: 10px; cursor: pointer; }
    </style>
</head>
<body>
    <h2>Chatbot Alleway Harvest</h2>
    <div id="chatbox">
        <div id="messages"></div>
        <input type="text" id="userInput" placeholder="Posez votre question..." />
        <button onclick="sendMessage()">Envoyer</button>
    </div>

    <script>
        async function sendMessage() {
            let userInput = document.getElementById("userInput").value;
            document.getElementById("messages").innerHTML += `<p><strong>Vous :</strong> ${userInput}</p>`;

            let responses = {
                "bonjour": "Bonjour ! Bienvenue chez Alleway Harvest. Comment puis-je vous aider ?",
                "liqueur": "Nous proposons des bouteilles de liqueur de guavaberry en rouge et jaune, 750 ml à 25 euros.",
                "produits": "Pour l'instant, nous vendons principalement de la liqueur de guavaberry, mais d'autres produits locaux seront bientôt ajoutés !",
                "contact": "Vous pouvez nous contacter via notre site ou nos réseaux sociaux."
            };

            let botResponse = responses[userInput.toLowerCase()] || "Je ne suis pas sûr de comprendre. Pouvez-vous reformuler ?";
            
            document.getElementById("messages").innerHTML += `<p><strong>Bot :</strong> ${botResponse}</p>`;
            document.getElementById("userInput").value = "";
        }
    </script>
</body>
</html>
```
