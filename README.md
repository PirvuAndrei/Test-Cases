# Test-Cases

Below are some Test Case samples that I wrote.

*******

## Valid sign up

*******

TEST CASE 1

Title : Validate sign up with valid  email address.

Description: Check if the sign up works when a person uses a valid email address.

Steps to reproduce: 	
			1.Navigate to sign up page
			2.Provide a valid first name
			3.Provide a valid surname	
			4.Provide a valid email address
			5.Provide a valid password
			6.Provide a valid date of birth
			7.Provide a valid gender
			8.Click on "Sign up"

	
Expected result: -User registration is successful
		 -User is redirected to Newsfeed Page
		 -An email verification is sent to the user

					
Status: Ready to Test

Priority: High

*******

TEST CASE 2


Title : Validate sign up with valid phone number

Description: Check if the sign up works when a person uses a valid email address.

Steps to reproduce:	1.Navigate to sign up page
			2.Provide a valid first name
			3.Provide a valid surname
			4.Provide a valid phone number
			5.Provide a valid password
			6.Provide a valid date of birth
			7.Provide a valid gender
			8.Click on "Sign up" 	

	
Expected result:  -User registration is successful
		  -User is redirected to Newsfeed Page
		  -An OTP is sent to the user
				
Status: Ready to Test

Priority: High

*******

TEST CASE 3

Title :  Validate providing Female as gender

Description: Check if the sign up works when a person select the Female as gender. 

Steps to reproduce: 1.Navigate to sign up page
		    2.Check the "Female" gender box
		    3.Fill all other fields with valid data
		    4.Click on "Sign up"

	
Expected result:   -User registration is successful
		   -User is redirected to Newsfeed Page
					
Status: Ready to Test

Priority: Medium

*******

## Invalid Sign up

*******

TEST CASE 4

Title : Validate leaving password field empty

Description: Check if the sign up is invalid  when a person is not writing anything in password field.

Steps to reproduce: 1.Navigate to sign up page
		    2.Leave password field empty
		    3.Provide valid data in all other fields and submit

	
Expected result: -Sign up is not successful
		 -An error message appearing telling the user that enter a valid Phone number
		 -Phone number field should be highlighted
					
Status: Ready to Test

Priority: High

*******

TEST CASE 5

Title : Verify providing a Short mobile number "1234"

Description: Check if the sign up is invalid  when a person provides a phone number that is too short.

Steps to reproduce: 	1.Navigate to the Facebook sign-up page
			2.Provide the invalid data: Enter a short mobile number (e.g., "1234").
			3.Provide valid data in all other fields    
	
Expected result:  -Sign up is not successful
		  -An error message appearing telling the user that enter a valid Phone number
		  -Phone number field should be highlighted"""	
					
Status: Ready to Test

Priority: High

*******

TEST CASE 6

Title : Verify adding an Email With Wrong format e.g "abc342432#"

Description: Check if the sign up is invalid when a person provides a email in wrong format.

Steps to reproduce:  1.Navigate to the Facebook sign-up page
		     2.Provide the invalid data: Enter a email in wrong format (e.g., "abc342432#").
		     3.Provide valid data in all other fields

	
Expected result:  -Sign up is not successful
		  -An error message appearing telling the user that invalid email
		  -Email field should be highlighted

Status: Ready to Test

Priority: High


*******

TEST CASE 7

Title :  Validate leaving the first name field empty  

Description: Check if the sign up is invalid when a person is leaving the first name field empty

Steps to reproduce: 	1.Navigate to sign up page
			2.Leave first name field empty
			3.Provide valid data in all other fields and submit

	
Expected result:  -Sign up is not successful
		  -An error message appearing telling the user that he can't leave first name field empty
	          -Firstname field should be highlighted
					
Status: Ready to Test

Priority: Medium

*******

## Login

*******

TEST CASE 8

Title : Login with a valid email address and a valid password

Description: Check if the login  works when a person uses a valid email address and a valid password.

Steps to reproduce: 1.Enter the valid email address associated with the user account in the email address field.
		    2.Enter the valid password associated with the user account in the password field.
		    3.Click the "Login" button.
	
Expected result:   The system successfully authenticates the user and grants them access to the system's main page or dashboard.
				
Status: Ready to Test

Priority: High

*******

TEST CASE 9

Title : Login with valid user without verifying email or phone number

Description: Check if the login is not working  when a person uses a valid user without verifying email or phone number.

Steps to reproduce: 	1.Enter the user's valid phone number or email "Unverifyed"
			2.Enter the user's valid password 
			3.Click the "Login" button.
	
Expected result:	The system displays an error message stating that email or phone number verification is required before login.
					
Status: Ready to Test

Priority: High

*******

TEST CASE 10

Title :  Login with a valid password after forgotten password functionality

Description: Check if the login is working  when a person has forgotten their password and wants to use a new one. 	

Steps to reproduce:	1.Steps to reproduce: Click on the "Forgot Password"
			2.Enter the user's email address or phone number associated with the account
			3.Submit the request to reset the password.
			4.Click on the reset link
			5.Enter a new, valid password that meets the system's password complexity requirements
			6.Confirm the new password 
			7.Submit the new password.
			8.Navigate to login page
			9.Enter the newly created password in the login password field.
			10.Click the "Login" button.

	
Expected result:	The system should send a password reset email or SMS.
			The user successfully resets their password and logs in using the new password.	

					
Status: Ready to Test

Priority: High

*******

TEST CASE 11

Title : Login with an invalid email "wrong format"

Description: Check if the login is not working  when a person uses an invalid email which has a wrong format. 

Steps to reproduce:	1.Enter an email address with an invalid format (e.g., missing "@", invalid domain name, etc.) in the designated field.
			2.Enter a valid password (it doesn't matter if it's valid for a real account as the email itself is invalid).
			3.Click the "Login" button. 
	
Expected result: The system rejects the login attempt and displays a clear message indicating that the email format is invalid.
					
Status: Ready to Test

Priority: High


*******

TEST CASE 12

Title :  Login with an invalid email "not registerd"

Description: Check if the login is not working  when a person uses an invalid email which is not registered.

Steps to reproduce: 1.Enter an email address that is not registered in the system.
		    2.Enter a valid password (it doesn't matter if it's valid for a real account as the email itself is invalid).
		    3.Click the "Login" button.

Expected result:   The system rejects the login attempt and displays a clear message indicating that the email address is not registered.
				
Status: Ready to Test

Priority: High

*******

TEST CASE 13

Title : Login with invalid password with valid email

Description: Check if the login is not working  when a person has a valid email but the password is invalid.

Steps to reproduce:  1.Enter the valid email address associated with the user account.
		     2.Enter an invalid password (different from the actual password for this account).
		     3.Click the "Login" button.

	
Expected result:  The system rejects the login attempt and displays a clear message indicating that the password is incorrect.

					
Status: Ready to Test

Priority: High

*******

TEST CASE 14

Title : Login with invalid password with valid phone number

Description:  Check if the login is not working  when a person has a valid phone number but the password is invalid.

Steps to reproduce: 1.Enter the valid phone number associated with the user account.
		    2.Enter an invalid password (different from the actual password for this account).
		    3.Click the "Login" button.

	
Expected result: The system rejects the login attempt and displays a clear message indicating that the password is incorrect.
	
Status: Ready to Test

Priority: High

*******

TEST CASE 15

Title : Login with invalid password 3 times

Description: Check if the login is not working a when a person uses an invalid password 3 times.

Steps to reproduce: 	1.Enter the valid email address (or phone number) associated with the user account.
			2.Enter an invalid password (different from the actual password for this account).
			3.Click the "Login" button.
			4.Repeat steps 1-3 two more times, entering the same invalid password each time (total of 3 attempts).

	
Expected result:  The system should lock the user account temporarily (according to the implemented security policy).
						
Status: Ready to Test

Priority: Medium
