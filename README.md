<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
    <h2>registration form</h2>
    <form action="/submit" method="post">
        <>
            <label for="username">UserName:</label>
            <input type="text" id="username" required>
            <br>
             <label for="email">Email:</label>
            <input type="email" id="email"name="email" required>
            <br>
             <label for="password">Password:</label>
            <input type="password" id="password"
            name="'password" required>
            <br>
             <label for="confirm password">Confirm password:</label>
            <input type="confirm password" id="confirm password"
            name="confirm password" required>
        </div>
        <button type="submit">Register</button>
    </form>    
</body>
</html>
