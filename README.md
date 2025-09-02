<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Feedback Registration Form</title>
</head>
<body>
    <h2>Feedback Registration</h2>
    <form action="/submit-feedback" method="post">
        <label for="name">Name:</label><br />
        <input type="text" id="name" name="name" required /><br /><br />
        
        <label for="email">Email:</label><br />
        <input type="email" id="email" name="email" required /><br /><br />
        
        <label for="feedback">Feedback:</label><br />
        <textarea id="feedback" name="feedback" rows="5" cols="30" required></textarea><br /><br />
        
        <input type="submit" value="Submit Feedback" />
    </form>
</body>
</html>
