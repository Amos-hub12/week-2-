# week-2-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML Template</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <section>
        <h2>About This Page</h2>
This is the basic template of HTML, which includes everything, such as a header, a paragraph, a registration form, table, image, and external link, among others. 
</section>
<section>
<h2>Registration Form</h2>
<form action="/submit_form.php" method="post">
<label for="name">Name:</label>
            <input type="text" id="name" name="name"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
<label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone"><br><br>
            <input type="submit" value="Register">
        </form>
    </section>
    <section>
        <h2>User Information</h2>
<table border="1">
            <tr>
                <th>Name</th>
                <th>Email</th>
<th>Phone Number</th>
            </tr>
            <tr>
                <td>John Doe
john@example.com
                123-456-7890
            </tr>
            <tr>
<td>Jane Smith</td>
                <td>jane@example.com</td>
                <td>098-765-4321</td>
            </tr>
</table>
    </section>
    <section>
        <h2>Sample Image</h2>
        <img src="https://via.placeholder.com/150" alt="Sample Image">
    </section>
    <section>
        <h2>External Link</h2>
        <p>
</section>
</body>
</html>
