<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Media Tech</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #555;
        }
        .hero {
            background-color: #ddd;
            padding: 50px;
            text-align: center;
        }
        .hero h1 {
            margin: 0;
            font-size: 3em;
        }
        .services {
            display: flex;
            justify-content: space-around;
            margin: 20px;
        }
        .service-box {
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            width: 30%;
            text-align: center;
        }
        .support {
            padding: 20px;
            background-color: #eee;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Media Tech</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About Us</a>
        <a href="#">Services</a>
        <a href="#">Support</a>
        <a href="#">Contact</a>
    </nav>

    <section class="hero">
        <h1>Welcome to Media Tech</h1>
        <p>We offer the best media and technology services for you!</p>
        <button>Get Started</button>
    </section>

    <section class="services">
        <div class="service-box">
            <h2>Service 1</h2>
            <p>Details about the first service.</p>
        </div>
        <div class="service-box">
            <h2>Service 2</h2>
            <p>Details about the second service.</p>
        </div>
        <div class="service-box">
            <h2>Service 3</h2>
            <p>Details about the third service.</p>
        </div>
    </section>

    <section class="support">
        <h2>Support</h2>
        <p>Need help? Contact us at support@mediatech.com or call 1-800-123-4567.</p>
        <p>Check our <a href="#">FAQs</a> for answers to common questions.</p>
    </section>

    <footer>
        <p>&copy; 2024 Media Tech</p>
    </footer>

    <!-- Example AI Chatbot Integration -->
    <script src="https://cdn.example.com/chatbot-widget.js"></script>
    <script>
      ChatbotWidget.init({
        apiKey: 'YOUR_API_KEY',
        welcomeMessage: 'How can I help you today?',
      });
    </script>

</body>
</html>
