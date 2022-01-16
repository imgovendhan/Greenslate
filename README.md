# GreenSlate Coding Challenge

This automation program will run the web app https://demo.opencart.com/ to verify the following:
1. New User Registration
2. Adding item to the cart
3. Verifying currency change in the display

This is done in Junit using POM 

I have used three test methods in my testcases.java

In the first test method I have verified the Account registration for the new user by giving all the input mandatory for the creation of new user.

An important thing to be noted in this method is that we have use new email id each time we run the test cases otherwise it would create a new user as the provided email ID would have been already registered.

So whenever running the test case please provide new email id in field called 'email' in Configuration.properties in Configs folder
