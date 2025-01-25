# QR-code-1st-project
This project is a responsive QR code component built with HTML and CSS, featuring a clean card-style layout with a QR code, title, and description. It adapts seamlessly to mobile and desktop screens, follows a defined style guide, and uses modern CSS for rounded corners, shadows, and responsive typography.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QR Code Component</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #d6e2f0;
            font-family: 'Outfit', sans-serif;
        }

        .card {
            background-color: #ffffff;
            border-radius: 16px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            max-width: 320px;
            text-align: center;
            padding: 16px;
        }

        .card img {
            width: 100%;
            max-width: 280px;
            border-radius: 8px;
            margin-bottom: 16px;
        }

        .card h1 {
            font-size: 1.5rem;
            color: #1f2937;
            margin-bottom: 8px;
        }

        .card p {
            font-size: 1rem;
            color: #6b7280;
            line-height: 1.5;
        }

        @media (min-width: 768px) {
            .card {
                max-width: 350px;
                padding: 24px;
            }

            .card h1 {
                font-size: 1.75rem;
            }

            .card p {
                font-size: 1.125rem;
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <img src="images/image-qr-code.png" alt="QR Code">
        <h1>Improve your front-end skills</h1>
        <p>Scan the QR code to visit our front-end challenges and take your coding skills to the next level!</p>
    </div>
</body>
</html>
