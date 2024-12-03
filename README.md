# RonWeasleyToken
html_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RonWeasleyToken (RWT)</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            text-align: center;
        }
        header {
            background-color: #ff5722;
            color: white;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
        }
        section {
            padding: 20px;
        }
        img {
            max-width: 300px;
            height: auto;
            border-radius: 10px;
        }
        a {
            text-decoration: none;
            color: #ff5722;
            font-weight: bold;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>RonWeasleyToken (RWT)</h1>
        <p>Your gateway to magical crypto!</p>
    </header>
    <section>
        <h2>About the Token</h2>
        <p>RonWeasleyToken (RWT) is a community-driven meme token inspired by the Wizarding World. Join the magic!</p>
        <img src="3319587E-7C6D-4AE4-9EA0-F00B1D8FAFC4.jpeg" alt="Ron Weasley Token">
    </section>
    <section>
        <h2>Links</h2>
        <p><a href="https://t.me/ronweasleytoken" target="_blank">Join Telegram</a></p>
        <p><a href="https://twitter.com/RonWeasleyToken" target="_blank">Follow on Twitter</a></p>
        <p><a href="https://phantom.app/tokens/solana/8dBuNFudWYxPQik3peWkovGjR9HyUDvQeYWZkgVmpump?referralId=bqnnekdv4kp" target="_blank">View on Phantom</a></p>
        <p><a href="https://pump.fun/coin/8dBuNFudWYxPQik3peWkovGjR9HyUDvQeYWZkgVmpump" target="_blank">Check Pump.fun</a></p>
        <p><strong>Token Address:</strong> 8dBuNFudWYxPQik3peWkovGjR9HyUDvQeYWZkgVmpump</p>
    </section>
    <footer>
        <p>&copy; 2024 RonWeasleyToken. All Rights Reserved.</p>
    </footer>
</body>
</html>
"""

# Сохранение файла
file_path = "/mnt/data/RonWeasleyToken.html"
with open(file_path, "w") as file:
    file.write(html_content)

file_path
