
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Collaboration with Navrachana University</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            background-color: #1ad3e0;
        }

        .container {
            width: 40%;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 20px 10px 45px rgba(4, 255, 242, 0.2);
            text-align: center;
        }

        h2 {
            color: #003366;
        }

        label {
            display: block;
            text-align: left;
            margin: 10px 0 5px;
            font-weight: bold;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        textarea {
            height: 100px;
            resize: none;
        }

        .submit-btn {
            background-color: #003366;
            color: white;
            border: none;
            padding: 12px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
            width: 100%;
        }

        .submit-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Contact Us for Collaboration</h2>
        <p>We welcome collaboration opportunities with Navrachana University. Please fill out the form below.</p>

        <form action="submit_form.php" method="POST">
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>

            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>

            <label for="organization">Organization/Company</label>
            <input type="text" id="organization" name="organization" placeholder="Enter your organization name" required>

            <label for="message">Your Message</label>
            <textarea id="message" name="message" placeholder="Write your message here..." required></textarea>

            <button type="submit" class="submit-btn">Submit</button>
            <br>
            <br>
            <button class="submit-btn"style="text-decoration:none;"><a href="/Navrachana Home.html">Home</a></button>
        </form>
    </div>

</body>
</html>
