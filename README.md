<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capture Image and Enter Details</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Capture Image and Enter Details</h1>
    </header>

    <main>
        <section>
            <h2>Upload Image</h2>
            <input type="file" id="imageInput" accept="image/*" onchange="previewImage(event)">
            <br>
            <img id="imagePreview" src="" alt="Image Preview" style="display: none;">
        </section>

        <section>
            <h2>Enter Details</h2>
            <form id="detailsForm">
                <label for="numberInput">Number:</label>
                <input type="number" id="numberInput" name="number" required>
                <br>

                <label for="textInput">Characters:</label>
                <input type="text" id="textInput" name="text" required>
                <br>

                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>

