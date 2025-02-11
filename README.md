# Valentines-2k25

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>404 Error</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin-top: 20%; }
        a { text-decoration: none; color: red; font-weight: bold; }
    </style>
</head>
<body>
    <h1>404 Error - Page Not Found</h1>
    <p><a href="valentine.html">Click here</a> if you're feeling lost...</p>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine?</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin-top: 20%; }
        .btn { padding: 10px 20px; margin: 10px; font-size: 18px; cursor: pointer; border: none; }
        .yes { background-color: green; color: white; }
        .no { background-color: red; color: white; }
    </style>
</head>
<body>
    <h1>Will you be my Valentine?</h1>
    <button class="btn yes" onclick="showYesMessage()">Yes</button>
    <button class="btn no" onclick="showNoMessage()">No</button>

    <div id="message"></div>

    <script>
        function showYesMessage() {
            document.body.innerHTML = '<h1>Yay! 🎉</h1><img src="https://media.giphy.com/media/3o7abKhOpu0NwenH3O/giphy.gif" alt="Dancing Dog"><p>Here’s a bouquet of flowers for you! 💐</p>';
        }

        function showNoMessage() {
            document.getElementById("message").innerHTML = "<h2>CHOOSE A</h2>";
            setTimeout(() => {
                window.location.reload();
            }, 1500);
        }
    </script>
</body>
</html>
