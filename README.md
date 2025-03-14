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
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Fridah's Website</title>

    </head>
    <body style ="background-color:#f2f2f2;">
        <header>
            <h2 style ="color: #4dd2ff">Fridah Omoke- Web Development</h2>
            <hr/>
        </header>

        <h2> Ordered List</h2>
        <ol type ="I">
            <li>Item One</li>
            <li>Item Two</li>
            <li>Item Three</li>
            <li>Item Four</li>
            <li>Item Five</li>
        </ol>
        <h2>Peacock in H<sub>2</sub>0</h2>
        <img src ="C:\Users\User\OneDrive\Documents\Weeek 2- Web Development\pexels-rodrigo-a-36100054-15191393.jpg" alt="Peacock Image" width="500">

        <h2> Table of Contacts</h2>
        <table>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>

            <tr>
                <th>Seth viola</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>

            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>

            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>

            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </table>

        <h2> Registration Form</h2>
        <form action ="#" method="POST">
            <!-- Name Field-->
             <label for ="name"> Full Name:</label>
             <input type ="text" id="name" name="name" placeholder="Enter your full name" required>
             <br/>

             <!--Email field-->
             <label for ="email"> Email:</label>
             <input type="email" id="email" placeholder="Enter your email" required>
             <br/>

             <!--Password field-->
             <label for="password"> password</label>
             <input type="password" id="password" placeholder="Enter your password" required minilength ="6">
             <br/>

             <!--Dropdown field-->
             <label for ="country">Country:</label>
             <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="kenya">Kenya</option>
                <option value="Uganda">Uganda</option>
                <option value="Tanzania">Uganda</option>
             </select>
             <br/>

             <!--Radio buttons-->
             <label>Gender:</label>
             <input type="radio" id="male" name="gender" value="male" required>
             <label for="male">Male</label>
             <input type="radio" id="female" name="gender" value="female" required>
             <label for="female">Female</label>
             <br/>

             <!--Checkboxes-->
             <label>Interests:</label>
             <input type="checkbox" id="sports" name="interests" value="sports">
             <label for="sports">Sports</label>
             <input type="checkbox" id="music" name="interests" value="music">
             <label for="music">Music</label>
             <input type="checkbox" id="travel" name="interests" value="travel">
             <label for="travel">Travel</label>
             <br/>

             <!--submit button-->
             <button type="submit">Register</button>
        </form>

    </body>
</html>
