# Advanced HTML5 Elements 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        /* Basic styles for table and form */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px;
            text-align: left;
        }

        form {
            margin-top: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
        }

        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>Introduction to HTML5</li>
            <li>Understanding Forms</li>
            <li>Multimedia Elements</li>
            <li>Using Tables in HTML</li>
            <li>Working with External Media</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Image from Pexels</h2>
        <img src="https://images.pexels.com/photos/3556155/pexels-photo-3556155.jpeg" alt="Beautiful landscape" width="500">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Table of Contacts</h2>
        <table>
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
                    <td>John Doe</td>
                    <td>123 Main St, City</td>
                    <td>(555) 123-4567</td>
                    <td>johndoe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak St, City</td>
                    <td>(555) 987-6543</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Mark Johnson</td>
                    <td>789 Pine St, City</td>
                    <td>(555) 456-7890</td>
                    <td>markjohnson@example.com</td>
                </tr>
                <tr>
                    <td>Alice Brown</td>
                    <td>101 Maple St, City</td>
                    <td>(555) 234-5678</td>
                    <td>alicebrown@example.com</td>
                </tr>
                <tr>
                    <td>Tom Lee</td>
                    <td>202 Cedar St, City</td>
                    <td>(555) 678-1234</td>
                    <td>tomlee@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post" id="registration-form">
            <!-- Name -->
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>

            <!-- Email -->
            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <!-- Password -->
            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6">

            <!-- Date -->
            <label for="dob">Date of Birth</label>
            <input type="date" id="dob" name="dob" required>

            <!-- Gender Radio Buttons -->
            <fieldset>
                <legend>Gender</legend>
                <label for="male">
                    <input type="radio" id="male" name="gender" value="male" required> Male
                </label>
                <label for="female">
                    <input type="radio" id="female" name="gender" value="female"> Female
                </label>
                <label for="other">
                    <input type="radio" id="other" name="gender" value="other"> Other
                </label>
            </fieldset>

            <!-- Newsletter Subscription -->
            <label for="newsletter">Subscribe to our newsletter</label>
            <input type="checkbox" id="newsletter" name="newsletter" value="yes">

            <!-- Country Dropdown -->
            <label for="country">Select Your Country</label>
            <select id="country" name="country" required>
                <option value="">--Please select--</option>
                <option value="us">United States</option>
                <option value="ca">Canada</option>
                <option value="uk">United Kingdom</option>
                <option value="au">Australia</option>
                <option value="in">India</option>
            </select>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        /* Basic styles for table and form */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px;
            text-align: left;
        }

        form {
            margin-top: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
        }

        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>Introduction to HTML5</li>
            <li>Understanding Forms</li>
            <li>Multimedia Elements</li>
            <li>Using Tables in HTML</li>
            <li>Working with External Media</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Image from Pexels</h2>
        <img src="https://images.pexels.com/photos/3556155/pexels-photo-3556155.jpeg" alt="Beautiful landscape" width="500">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Table of Contacts</h2>
        <table>
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
                    <td>John Doe</td>
                    <td>123 Main St, City</td>
                    <td>(555) 123-4567</td>
                    <td>johndoe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak St, City</td>
                    <td>(555) 987-6543</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Mark Johnson</td>
                    <td>789 Pine St, City</td>
                    <td>(555) 456-7890</td>
                    <td>markjohnson@example.com</td>
                </tr>
                <tr>
                    <td>Alice Brown</td>
                    <td>101 Maple St, City</td>
                    <td>(555) 234-5678</td>
                    <td>alicebrown@example.com</td>
                </tr>
                <tr>
                    <td>Tom Lee</td>
                    <td>202 Cedar St, City</td>
                    <td>(555) 678-1234</td>
                    <td>tomlee@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post" id="registration-form">
            <!-- Name -->
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>

            <!-- Email -->
            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <!-- Password -->
            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6">

            <!-- Date -->
            <label for="dob">Date of Birth</label>
            <input type="date" id="dob" name="dob" required>

            <!-- Gender Radio Buttons -->
            <fieldset>
                <legend>Gender</legend>
                <label for="male">
                    <input type="radio" id="male" name="gender" value="male" required> Male
                </label>
                <label for="female">
                    <input type="radio" id="female" name="gender" value="female"> Female
                </label>
                <label for="other">
                    <input type="radio" id="other" name="gender" value="other"> Other
                </label>
            </fieldset>

            <!-- Newsletter Subscription -->
            <label for="newsletter">Subscribe to our newsletter</label>
            <input type="checkbox" id="newsletter" name="newsletter" value="yes">

            <!-- Country Dropdown -->
            <label for="country">Select Your Country</label>
            <select id="country" name="country" required>
                <option value="">--Please select--</option>
                <option value="us">United States</option>
                <option value="ca">Canada</option>
                <option value="uk">United Kingdom</option>
                <option value="au">Australia</option>
                <option value="in">India</option>
            </select>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Advanced HTML5 Elements and Forms</title>
    <style>
        /* Basic styles for table and form */
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px;
            text-align: left;
        }

        form {
            margin-top: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
        }

        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
        }

        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>Introduction to HTML5</li>
            <li>Understanding Forms</li>
            <li>Multimedia Elements</li>
            <li>Using Tables in HTML</li>
            <li>Working with External Media</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Image from Pexels</h2>
        <img src="https://images.pexels.com/photos/3556155/pexels-photo-3556155.jpeg" alt="Beautiful landscape" width="500">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Table of Contacts</h2>
        <table>
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
                    <td>John Doe</td>
                    <td>123 Main St, City</td>
                    <td>(555) 123-4567</td>
                    <td>johndoe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak St, City</td>
                    <td>(555) 987-6543</td>
                    <td>janesmith@example.com</td>
                </tr>
                <tr>
                    <td>Mark Johnson</td>
                    <td>789 Pine St, City</td>
                    <td>(555) 456-7890</td>
                    <td>markjohnson@example.com</td>
                </tr>
                <tr>
                    <td>Alice Brown</td>
                    <td>101 Maple St, City</td>
                    <td>(555) 234-5678</td>
                    <td>alicebrown@example.com</td>
                </tr>
                <tr>
                    <td>Tom Lee</td>
                    <td>202 Cedar St, City</td>
                    <td>(555) 678-1234</td>
                    <td>tomlee@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post" id="registration-form">
            <!-- Name -->
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>

            <!-- Email -->
            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <!-- Password -->
            <label for="password">Password</label>
            <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6">

            <!-- Date -->
            <label for="dob">Date of Birth</label>
            <input type="date" id="dob" name="dob" required>

            <!-- Gender Radio Buttons -->
            <fieldset>
                <legend>Gender</legend>
                <label for="male">
                    <input type="radio" id="male" name="gender" value="male" required> Male
                </label>
                <label for="female">
                    <input type="radio" id="female" name="gender" value="female"> Female
                </label>
                <label for="other">
                    <input type="radio" id="other" name="gender" value="other"> Other
                </label>
            </fieldset>

            <!-- Newsletter Subscription -->
            <label for="newsletter">Subscribe to our newsletter</label>
            <input type="checkbox" id="newsletter" name="newsletter" value="yes">

            <!-- Country Dropdown -->
            <label for="country">Select Your Country</label>
            <select id="country" name="country" required>
                <option value="">--Please select--</option>
                <option value="us">United States</option>
                <option value="ca">Canada</option>
                <option value="uk">United Kingdom</option>
                <option value="au">Australia</option>
                <option value="in">India</option>
            </select>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

</body>
</html>

