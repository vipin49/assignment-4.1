Aim

To create a student registration form using HTML with proper labels, input fields, validation, and a submit button.

Requirements

Full Name

Email Address

Password

Phone Number

Age

Submit Button

Source Code

Save the following code in a file named registration.html.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
</head>
<body>

    <h1>Student Registration Form</h1>

    <form action="#" method="get">

        <label for="fullName">Full Name:</label>
        <input
            type="text"
            id="fullName"
            name="fullName"
            placeholder="Enter your full name"
            required
        >
        <br><br>

        <label for="email">Email Address:</label>
        <input
            type="email"
            id="email"
            name="email"
            placeholder="Enter your email"
            required
        >
        <br><br>

        <label for="password">Password:</label>
        <input
            type="password"
            id="password"
            name="password"
            placeholder="Enter your password"
            minlength="8"
            required
        >
        <br><br>

        <label for="phone">Phone Number:</label>
        <input
            type="tel"
            id="phone"
            name="phone"
            placeholder="Enter 10-digit phone number"
            pattern="[0-9]{10}"
            maxlength="10"
            required
        >
        <br><br>

        <label for="age">Age:</label>
        <input
            type="number"
            id="age"
            name="age"
            placeholder="Enter your age"
            min="1"
            max="120"
            required
        >
        <br><br>

        <button type="submit">Submit Registration</button>

    </form>

</body>
</html>

Explanation

The <form> tag creates the student registration form.

The <label> tag provides a descriptive label for each input field.

The text input accepts the student's full name.

The email input accepts an email address and checks its format.

The password input hides the entered password.

The tel input accepts a phone number and validates 10 digits.

The number input accepts the student's age.

The required attribute makes all fields mandatory.

Every input has a unique id and a meaningful name.

The submit button submits the form.

Testing

Open registration.html in a web browser.

Verify that all five input fields and the submit button appear.

Try submitting the form with empty fields to check required-field validation.

Enter an invalid email address and verify browser validation.

Enter a phone number that is not 10 digits and verify browser validation.

Fill in valid details and click the submit button.

Result

The Student Registration Form was successfully created using HTML. It contains all the required input fields, associated labels, suitable input types, basic form validation, and a submit button.

Submission

registration.html — the student registration form.

registration-screenshot.png — a screenshot showing the form running in a web browser.