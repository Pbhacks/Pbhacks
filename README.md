<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your GitHub Portfolio</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #8a2be2; /* Violet Background */
            color: #fff;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
        }

        #header {
            height: 300px; /* Adjust the height as needed */
            background-image: url('https://placekitten.com/1200/300'); /* Replace with your scenic image link */
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
        }

        #about-me {
            padding: 20px;
        }

        #portfolio {
            padding: 20px;
        }

        #scroll-buttons {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
        }

        button {
            background-color: #4CAF50; /* Green */
            border: none;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin: 4px 2px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <div id="header">
        <h1>Welcome to Your GitHub Portfolio!</h1>
    </div>

    <div id="about-me">
        <h2>About Me</h2>
        <p>
            I'm [Your Name], a passionate [Your Profession/Title] based in [Your Location]. I love [Your Interests/Hobbies] and am constantly exploring new technologies to enhance my skills.
        </p>
        <!-- Add more about yourself as needed -->
    </div>

    <div id="portfolio">
        <h2>Portfolio Preview</h2>
        <div>
            <img src="https://placekitten.com/400/200" alt="Image 1">
            <img src="https://placekitten.com/400/201" alt="Image 2">
            <img src="https://placekitten.com/400/202" alt="Image 3">
        </div>
        <!-- Add more images or content for your portfolio -->
    </div>

    <div id="scroll-buttons">
        <button onclick="scrollToTop()">Scroll to Top</button>
        <button onclick="scrollToBottom()">Scroll to Bottom</button>
    </div>

    <script>
        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        function scrollToBottom() {
            window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
        }
    </script>
</body>

</html>
