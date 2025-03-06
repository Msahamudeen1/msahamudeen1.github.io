# msahamudeen1.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AIDROPS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            margin: 0;
            background-color: #f0f0f0;
            padding: 20px;
        }
        h1 {
            margin-bottom: 20px;
        }
        .button-container {
            display: grid;
            grid-template-columns: repeat(5, 1fr);
            gap: 10px;
            width: 80%;
            max-width: 800px;
        }
        .editable-button {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 10px;
            font-size: 16px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-align: center;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }
        .editable-button img {
            width: 50px;
            height: 50px;
            margin-bottom: 10px;
        }
        .editable-button:focus {
            outline: none;
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>AIDROPS</h1>
    <div class="button-container">
        <!-- Button 1 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 2 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.google.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 3 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.github.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Add more buttons as needed -->
        <!-- Button 4 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 5 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 6 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 7 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 8 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 9 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>

        <!-- Button 10 -->
        <button class="editable-button" contenteditable="true" onclick="window.location.href='https://www.example.com'">
            <img src="https://via.placeholder.com/50" alt="Button Icon">
            Edit this button
        </button>
    </div>

    <script>
        // Optional: Add JavaScript to handle the button clicks if needed
        document.querySelectorAll('.editable-button').forEach(button => {
            button.addEventListener('click', function(event) {
                if (this.isContentEditable) {
                    event.preventDefault(); // Prevent the link from opening if the button is being edited
                }
            });
        });
    </script>
</body>
</html>
