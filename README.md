# personal-details
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal details</title>
</head>
<body>
    <!-- The container div holds the entire form -->
    <div id="container">
        <!-- The formlabel div displays the form title -->
        <div id="formlabel">Personal details</div>
  
        <!-- The form starts here with action="details" and method="get" -->
  <form action="details" method="get">
            <!-- Salutation Dropdown -->
            <label for="salutation">Salutation<br/>
                <select>
                    <option>--None--</option>
                    <option>Mr.</option>
                    <option>Mrs.</option>
                </select>
            </label><br/>
  
            <!-- First Name and Last Name Inputs -->
  <label for="name"><br/>
                First Name: <input type="text" name="name" placeholder="abcd"><br/>
                <br/>
                Last Name: <input type="text" name="name" placeholder="abcd">
            </label><br/>
  
            <!-- Gender Radio Buttons -->
   <label for="gender"><br/>
                Gender:
   <input type="radio" name="gender"> Male 
                <input type="radio" name="gender"> Female 
            </label><br/>
          
            <!-- Email Input -->
   <label for="email"><br/>
                Email:<input type="email" name="email" value="abc@gmail.com" >
            </label><br/>
  
            <!-- Date of Birth Input -->
  <label for="Dob"><br/>
                Date of birth:<input type="date" name="Dob" >
            </label><br/>
          
            <!-- Address Textarea -->
   <label for="Address"><br/>
                Address:<br/>
                <textarea name="Address" cols="30" rows="5"></textarea>
            </label><br/>
  
            <!-- Submit Button -->
   <label for="submit"><br/>
                <input type="submit">
            </label>
        </form>
    </div>
</body>
</html>
<!-- The HTML form contains various form elements for capturing personal details like salutation, first name, last name, gender, email, date of birth, and address.
The <div id="container"> is used to hold the entire form content. It acts as a container to group all the form elements together.
The <div id="formlabel"> is used to display the title "Personal details" above the form.
The <form action="details" method="get"> tag defines the form and specifies that the form data will be sent to the URL "details" using the HTTP GET method when the form is submitted.
The <select> tag is used to create a dropdown for the salutation with options "Mr." and "Mrs.".
The <input type="text"> tags are used to create text input fields for first name and last name. The placeholder attribute provides an example text that appears inside the input field before the user enters any value.
The <input type="radio"> tags are used to create radio buttons for gender. The name attribute groups the radio buttons together so that only one option can be selected at a time.
The <input type="email"> tag is used to create an email input field that validates the user's email address. The value attribute sets the default value for the email input.
The <input type="date"> tag is used to create a date input field for the date of birth.
The <textarea> tag is used to create a multiline text input field for the address.
The <input type="submit"> tag is used to create a submit button to submit the form.
Overall, this HTML form is designed to collect personal details from the user and demonstrate the usage of various form elements. -->
