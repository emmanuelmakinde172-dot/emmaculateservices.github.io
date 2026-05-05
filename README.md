
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emmaculate | Portfolio</title>
    <style>
        :root {
            --primary: #2563eb;
            --dark: #1e293b;
            --light: #f8fafc;
        }
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background-color: var(--light);
            color: var(--dark);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }
        .container {
            padding: 2rem;
            background: white;
            border-radius: 12px;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
        }
        h1 { color: var(--primary); margin-bottom: 0.5rem; }
        p { font-size: 1.2rem; color: #64748b; }
        .btn {
            display: inline-block;
            margin-top: 1.5rem;
            padding: 0.75rem 1.5rem;
            background: var(--primary);
            color: white;
            text-decoration: none;
            border-radius: 6px;
            transition: opacity 0.2s;
        }
        .btn:hover { opacity: 0.9; }
    </style>
</head>
<body>
    <div class="container">
        <h1>emmaculate.github.io</h1>
        <p>Welcome to my professional space on the web.</p>
        <div id="status">Status: Site is Live 🚀</div>
        <a href="https://github.com/emmaculate" class="btn">View My GitHub</a>
    </div>
</body>
</html>