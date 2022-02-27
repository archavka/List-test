# Test Scenarios

## Login Flow

### Functional

* Verify if a user will be able to login with a valid username and valid password.(Happy path )
* Verify if a user cannot login with a valid username and an invalid password., verify error message
* Verify if a user cannot login with a invalid username and an invalid password., verify error message
* Verify if the data in password field is either visible as asterisk or bullet signs.
* Verify forgoten password functionality.
* Captcha on multiple tries
* Keep form blank and click login, verify error message
* Enter non exicting login id
* Keep me signed in
* Password assistance after multiple tries
* Click on the logo to exit login window

### Non Functional

* Verify if a user cannot enter the characters more than the specified range in each field (Username and Password) Positive
* Verify if a user cannot enter the characters more than the specified range in each field (Username and Password). Negative
* Verify the login page by pressing ‘Back button’ of the browser. It should not allow you to enter into the system once you log out.
* Varify there is NO timeout functionaility in Login session.
* Verify if a user should not be allowed to log in with different credentials from the same browser at the same time. 


* Verify the Login page against SQL injection attack.
* Verify the implementation of SSL certificate.

## Register(Create) Account Flow 

* Register(Create) account (Happy path)
* Keep form blank and proceed, verify error message
* Password less than 6/8 characters error message
* Email or any other optional field
* Email with dual domain name(.co.in)
* Less than 9 chars mobile number
* Invalid mobile number
* letters in mobile number


## Search Box

- Valid search with characters
- Valid search with numbers
- Valid search with alphanumeric
- Predictive search
- Invalid search
- Typo sherch
- Use keyboard to navigate and enter to search
- Search with my "My Account"


## Search List/Result Page

- Verify refinments - single, multiple (**check data also**)
- Verify removing refinments
- Verify sorting options (**check data also**)
- Verify pagination options - previous, next, page#
- Verify delivery option details (Prime content)
- Verify sponsored content

## Product Details Page

- Verify product detail
- Verify price is correct (should match search list/result and product details price)
- Verify quantity box
- Verify add to card button
- Verify add to wish list button (forced login scenario)
- Verify swatches
- Verify images (**should be high definition**)

## Account Page

- Verify different options on this page
- Verify mouse over on box changes color
- Verify differet links on the page
- Verify recomendation carousels 
- Verify back to top link

