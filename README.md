# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device width, initial-scale=1.0">
    <title>Sample Page</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <h2>My Favorite Activities</h2>
    <ol type="I">
        <li>Reading</li>
        <li>Coding</li>
        <li>Traveling</li>
        <li>Swimming</li>
        <li>Gaming</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Beautiful Nature</h2>
    <img src="https://images.pexels.com/photos/34950/pexels-photo.jpg" alt="Nature from Pexels" width="600">

    <!-- Table of 5 Contacts -->
    <h2>Contact List</h2>
    <table border="1" cellpadding="10">
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Fred Chisaka</td>
                <td>Nairobi, Kenya</td>
                <td>+254700123456</td>
                <td>chisaka@plp.com</td>
            </tr>
            <tr>
                <td>Jon Snow</td>
                <td>Kisumu, Kenya</td>
                <td>+254701234567</td>
                <td>jon@snow.com</td>
            </tr>
            <tr>
                <td>Mary Wanjiku</td>
                <td>Nakuru, Kenya</td>
                <td>+254712345678</td>
                <td>mary@example.com</td>
            </tr>
            <tr>
                <td>Ali Yusuf</td>
                <td>Mombasa, Kenya</td>
                <td>+254723456789</td>
                <td>ali@example.com</td>
            </tr>
            <tr>
                <td>Grace Njeri</td>
                <td>Eldoret, Kenya</td>
                <td>+254734567890</td>
                <td>grace@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <!-- Name -->
        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

        <!-- Email -->
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password -->
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6"><br><br>

        <!-- Date -->
        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown -->
        <label for="country">Select Country:</label><br>
        <select id="country" name="country" required>
            <option value="">--Select--</option>
            <option value="kenya">Kenya</option>
            <option value="uganda">Uganda</option>
            <option value="tanzania">Tanzania</option>
        </select><br><br>

        <!-- Radio Buttons -->
        <p>Gender:</p>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <!-- Checkboxes -->
        <p>Select Interests:</p>
        <input type="checkbox" id="coding" name="interests" value="coding">
        <label for="coding">Coding</label><br>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label><br>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label><br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>

