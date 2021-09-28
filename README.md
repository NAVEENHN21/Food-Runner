# Food-Runner
The Food Runner is primarily responsible for delivering food orders from the kitchen to customers' tables rapidly and accurately. It is this person who will maintain the cleanliness of the expo line, organization of order tickets, and communicate effectively.

1 Splash Screen
Display the logo of the app
Page exits after a few seconds and navigates to a
login page Kotlin File
If the user was previously logged in, navigate to
home page XML file
Naming Conventions

2 Login
EditText for mobile number Validation for the length of the mobile number Kotlin File
EditText for password Validation for the length of the password XML file
Login Button Password should be hidden when typed Naming Conventions
Forgot Password text
Navigation to forgot password page on
corresponding click
Registration text
Navigation to registration page on corresponding
click
Upon clicking the login button, if all the validations
are true, the code should hit the API and validate the
credentials.
If the credentials were correct, take the user to all
restaurants page, else provide an appropriate error
message

3 Register
EditText for all the fields
(Name, Email Address, Mobile
Number,
Delivery Address, and
Password)
Validation on name, email, mobile number,
password, and confirm password Kotlin File
Register button Password == confirm password validation XML file
Clicking on Register button sends a request to the
API along with the params and token Naming Conventions
Project Evaluation Rubric - Android App Development Food Runner

4 Forgot Password
EditText for mobile number Validation on mobile number Kotlin File
EditText for email Validation on email XML file
Button for moving to the next
screen
Send request to the API with params and token when
clicked on next and all validations are true Naming Conventions
After success from API, navigate the user to the reset
password page also sending mobile and email to that
screen via Intent

5 Reset Password
EditText for OTP Validation on OTP Kotlin File
EditText for password Validation on password XML file
EditText for confirm password Validation on confirm password Naming Conventions
Submit button
Clicking on submit button, sends a request to the
server with the params and token to reset the
password
If password gets successfully changed, navigate the
user to login page
If there is an error, display a corresponding message
and keep the user on the same screen

6 Navigation Drawer
Drawer header Click Home navigates to All Restaurants fragment Kotlin File
Home Fragment Favourite -> Favourite fragment XML file
Favourite Fragment My Profile -> Profile Fragment Naming Conventions
My Profile Fragment Order History -> Order history fragment
Order History Fragment FAQs -> FAQs Fragment
Project Evaluation Rubric - Android App Development Food Runner


6 Navigation Drawer
FAQs Fragment After every navigation the drawer closes itself
Logout Clicking on Logout, takes the user to the login page
After logout, all the preferences are cleared

7 All Restaurants
List of restaurants (Recycler
View)
Opening this fragment, sends a request to the server
and fetches the list of restaurants Kotlin File
Toolbar
The fetched json is parsed and the data is inflated in
the recycler view XML file
Sorting Menu options Clicking on icon on toolbar, opens the sorting menu Naming Conventions
Clicking on home icon opens up the drawer

8 Restaurant Card
Name of the restaurant
Clicking on the restaurant card, navigates the user to
the menu items of that restaurant Kotlin File
Restaurant Rating
Clicking on the favourite icon adds the restaurant to
the favourites XML file
Cost for one Naming Conventions
Restaurant thumbnail
8 Restaurant Details
Food Menu for restaurant
Opening this screen, sends a request to the server
requesting the details of the food items Kotlin File
Add to cart button
Clicking the favourite icon, adds the restaurant to the
favourites XML file
Remove from cart button
Clicking on add button, adds the food item to the
cart and changes the button from Add to Remove Naming Conventions
Go to cart button Clicking on Remove removes it from the cart
Add to favourite button
Add to cart button, navigates the user to the cart
page
If there are items in the cart and the user tries to go
back, the user should get a prompt and the cart
would be cleared
Project Evaluation Rubric - Android App Development Food Runner


9 Cart
Toolbar
Only the food items added in the cart should appear
in the list Kotlin File
Restaurant name The total should be calculated correctly XML file
List of food items
Clicking on the Place Order button would send a
request to the server for placing the order Naming Conventions
Total amount
If the order was successfully placed, user should be
notified and then navigated to the all restaurants
screen
Order confirmation screen
If there was an error, notify users accordingly and
keep them on cart page

10 Favourites
List of favourite restaurants
(Recycler View) The favourite icon should be checked Kotlin File
Toolbar
Unchecking the icon and reloading the screen should
remove the restaurant from favourites XML file
Restaurant Card
Clicking on restaurant card opens up the food items
menu of that restaurant Naming Conventions

11 Order History
List of previous orders
Opening this fragment sends a request to the server
to the fetch the previous orders of the logged in user Kotlin File
Restaurant Name
The fetched JSON should be parsed properly to be
displayed in the list XML file
Food items list Naming Conventions
Price of each food item
Date of ordering

12 User Profile
Name of user
Extract the user details from the shared preferences
and display them in the fragment Kotlin File
Project Evaluation Rubric - Android App Development Food Runner
5
12 User Profile Phone number XML file
Email Naming Conventions
Delivery Address
13 FAQ
Questions Static scrollview to display the contents on the screen Kotlin File
Answers XML file
Naming Conventions
14 Menu Items
Sort by rating
Clicking on sort by rating, reorders the list in a
decreasing order of their ratings Kotlin File
Sort by price
Clicking on sort by rating, reorders the list in a
decreasing order of their ratings XML file
Naming Conventions
