# GreenSlate Coding Challenge

This automation program will run the web app https://demo.opencart.com/ to verify the following:
1. New User Registration
2. Adding item to the cart
3. Verifying currency change in the display

This is done in Junit using POM 

I have used three test methods in my testcases.java

In the 1st test method:

I have verified the Account registration for the new user by giving all the input mandatory for the creation of new user.

An important thing to be noted in this method is that we have to use new email id each time we run the test cases otherwise the test will fail as the provided email ID would have been already registered.

On the successfull running of this method we would get "Account has been registered" displayed on our console.
 
So whenever running the test case please provide new email id in field called 'email' in Configuration.properties file in Configs folder

In the 2nd test method:

I have verified whether the item has been added to the cart or not, if the item is added to cart it will print "Verified the search item has been added to the cart".UP
If not then we would get an exception thrown.

In the 3rd test method:

I have verified whether currency change is displayed on the screen when changing the currency from USD to EUR, if it changes then we would get a message "Currency has changed" if not we will get "Currency didn't change"
