# perfectcup-membersonly-blog


a members only blog website done with HTML/CSS/Bootstrap/JavaScript/jQuery/PHP/AJAX


- visitors can view all contents of the website except the blog
- to view the blog you must create an account
- the account needs a first name, last name, an email, and a password

- first and last name need to be longer than 2 letters and doesnt accept numbers or special characters, only letters
              -if this is not met, displays: "First name needs to be longer than 2 characters"
- an email needs to be in the correct email format
              -if this is not met, displays: "Address is not valid"
- the password must be at least 4 characters
              -if this is not met, displays: "Password must be at least 4 characters"

The website has it's own mySQL database where it stores user account information

The passwords are hashed using the PHP BCYPT method

The website has a contact form, which is done using PHP Mailer library, SMTP protocol

The user can send a message which gets sent to the PHP Mailer defined email address

The user does not need to have a registered account to send a message

