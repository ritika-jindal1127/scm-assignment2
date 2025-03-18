🌟 University Event Tracker

📌 Description

The University Event Tracker is a web-based application designed to help students and faculty keep track of upcoming university events. It provides an intuitive interface for browsing events, adding new ones, and staying updated with notifications.

🎨 Demo Preview (HTML & CSS)

Here is a simple HTML & CSS snippet from the project:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>University Event Tracker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px;
            transition: background 0.3s, color 0.3s;
        }
        h1 {
            color: #2c3e50;
        }
        .event-container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .event-card {
            background: white;
            padding: 20px;
            margin: 15px;
            width: 50%;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            transition: transform 0.3s ease-in-out;
        }
        .event-card:hover {
            transform: scale(1.03);
        }
        .btn {
            background-color: #3498db;
            color: white;
            padding: 12px 24px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #2980b9;
            transform: scale(1.05);
        }
        .dark-mode {
            background-color: #1e1e1e;
            color: white;
        }
        .dark-mode .event-card {
            background: #333;
            color: white;
            box-shadow: 0px 0px 10px rgba(255, 255, 255, 0.1);
        }
        .toggle-btn {
            background-color: #f39c12;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .toggle-btn:hover {
            background-color: #e67e22;
        }
    </style>
</head>
<body>
    <h1>Welcome to the University Event Tracker 🎓</h1>
    <button class="toggle-btn" onclick="toggleDarkMode()">Toggle Dark Mode</button>

    <div class="event-container">
        <div class="event-card">
            <h2>Tech Symposium</h2>
            <p><strong>Date:</strong> March 25, 2025</p>
            <p><strong>Location:</strong> University Auditorium</p>
            <p>Join us for an exciting tech symposium featuring industry experts.</p>
            <button class="btn">Register Now</button>
        </div>

        <div class="event-card">
            <h2>Entrepreneurship Workshop</h2>
            <p><strong>Date:</strong> April 10, 2025</p>
            <p><strong>Location:</strong> Innovation Lab</p>
            <p>Learn how to turn your ideas into a business with expert guidance.</p>
            <button class="btn">Register Now</button>
        </div>
    </div>

    <script>
        function toggleDarkMode() {
            document.body.classList.toggle("dark-mode");
        }
    </script>
</body>
</html>


📌 Output Preview: This code creates a basic webpage displaying an event with a registration button.

🔹 Features

📅 Event listing with dates & locations.

🎨 Clean UI using HTML & CSS.

📌 Responsive design for better usability.

🛠️ Easily customizable styles.
