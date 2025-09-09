<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Roy Academy</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
            color: #ffcc00;
        }

        .container {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }

        .subject {
            margin-bottom: 30px;
        }

        .subject h2 {
            border-bottom: 1px solid #333;
            padding-bottom: 10px;
        }

        .notes {
            list-style-type: none;
            padding: 0;
            display: none;
            margin-top: 10px;
        }

        .notes li {
            background-color: #1f1f1f;
            margin: 10px 0;
            padding: 15px;
            border-radius: 8px;
        }

        button.toggle-btn {
            background-color: #333;
            color: #ff0000;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            font-size: 1em;
            border-radius: 5px;
            margin-top: 10px;
        }

        button.toggle-btn:hover {
            background-color: #444;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #1f1f1f;
            margin-top: 40px;
        }
    </style>
</head>
<link rel="stylesheet" href="style.css">

<body>

    <header>
        <h1>Roy Academy</h1>
        <p>आंसर को आना ही पड़ेगा</p>
    </header>

    <div class="container">

        <div class="subject">
            <h2>Accounts Notes</h2>
            <button class="toggle-btn" onclick="toggleNotes('accounts-12')">Class 12</button>
            <ul class="notes" id="accounts-12">
                <li><button class="note-btn" onclick="window.open('about:blank', '_blank')">Book 1: Accounting for
                        Partnership Firms</button></li>
                <li><button class="note-btn" onclick="window.open('about:blank', '_blank')">Book 2: Accounting for
                        Companies</button></li>
                <li><button class="note-btn" onclick="window.open('about:blank', '_blank')">Book 3: Analysis of
                        Financial Statements</button></li>

            </ul>
            <button class="toggle-btn" onclick="toggleNotes('accounts-11')">Class 11</button>
            <ul class="notes" id="accounts-11">
                <li>Class 11 - All Chapters</li>
            </ul>
        </div>

        <div class="subject">
            <h2>Economics Notes</h2>
            <button class="toggle-btn" onclick="toggleNotes('eco-12')">Class 12</button>
            <ul class="notes" id="eco-12">
                <li>All Chapters of Class 12</li>
            </ul>
            <button class="toggle-btn" onclick="toggleNotes('eco-11')">Class 11</button>
            <ul class="notes" id="eco-11">
                <li>All Chapters of Class 11</li>
            </ul>
        </div>

        <div class="subject">
            <h2>Business Studies Notes</h2>
            <button class="toggle-btn" onclick="toggleNotes('bus-12')">Class 12</button>
            <ul class="notes" id="bus-12">
                <li>All Chapters of Class 12</li>
            </ul>
            <button class="toggle-btn" onclick="toggleNotes('bus-11')">Class 11</button>
            <ul class="notes" id="bus-11">
                <li>All Chapters of Class 11</li>
            </ul>
        </div>

        <div class="subject">
            <h2>Credits</h2>
            <p>Made by Sujel Gain</p>
        </div>

    </div>

    <footer>
        <p>&copy; 2025 Roy Academy. All rights reserved.</p>
    </footer>

    <script>
        function toggleNotes(id) {
            const notes = document.getElementById(id);
            if (notes.style.display === 'block') {
                notes.style.display = 'none';
            } else {
                notes.style.display = 'block';
            }
        }
    </script>

</body>

</html>

<!--
**sujalgain/sujalgain** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
