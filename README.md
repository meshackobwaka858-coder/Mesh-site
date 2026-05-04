<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat with Meshack</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="app-container">
        <!-- Sidebar -->
        <aside class="sidebar">
            <div class="logo">
                <h2>Meshack</h2>
            </div>
            <div class="friend-list">
                <div class="friend active">General Chat</div>
                <div class="friend">Alex (Online)</div>
                <div class="friend">Sarah</div>
            </div>
        </aside>

        <!-- Main Chat Area -->
        <main class="chat-area">
            <header class="chat-header">
                <h3>General Chat</h3>
            </header>
            
            <div class="message-container" id="chatBox">
                <div class="message received">
                    <p>Welcome to Chat with Meshack! How are you?</p>
                </div>
            </div>

            <form class="input-area" id="messageForm">
                <input type="text" id="msgInput" placeholder="Type a message..." autocomplete="off">
                <button type="submit">Send</button>
            </form>
        </main>
    </div>
    <script src="script.js"></script>
</body>
</html># Mesh-site