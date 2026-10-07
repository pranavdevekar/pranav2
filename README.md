<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
</head>
<body>

    <h1>Contact Form</h1>
    <p>Please fill out this form to send us a message:</p>

    <!-- The form container -->
    <form action="#" method="POST">
        
        <!-- Text input for Name -->
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>

        <!-- Email input -->
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <!-- Multi-line text area for Messages -->
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="30" placeholder="Type your message here..."></textarea>
        <br><br>

        <!-- Submit button -->
        <input type="submit" value="Submit">
        
    </form>

</body>
</html>
