# GreenSlate Coding Challenge

This automation program will run the web app https://demo.opencart.com/ to verify the following:
1. New User Registration
2. Adding item to the cart
3. Verifying currency change in the display

This is done in Junit using POM 

# Please follow the following steps in order to execute the test cases:
1. Download and extract the file greenslate.rar
2. Extract the files from greenslate.rar 
3. Import the greenslate folder to your ide and execute the test cases. 

I have used three test methods in my testcases.java

# In the 1st test method:

I have verified the Account registration for the new user by giving all the input mandatory for the creation of new user.

An important thing to be noted in this method is that we have to use new email id each time we run the test cases otherwise the test will fail as the provided email ID would have been already registered.

On the successfull running of this method we would get "Account has been registered" displayed on our console.
 
So whenever running the test case please provide new email id in field called 'email' in Configuration.properties file in Configs folder




Testcase Number: TC_01

Testcase Objective: Register a new user in the demo portal

Steps:
1. Navigate to demo.opencart.com
2. Click on My Account and click on Register
3. Fill in your personal details and your password
4. After Clicking on Privacy Policy and hit Continue

Expected Result:
Account should be registered and message stating "Your Account has been created" should be available.

Actual Result: <After Execution>

Priority: High

# In the 2nd test method:

I have verified whether the item has been added to the cart or not, if the item is added to cart it will print "Verified the search item has been added to the cart".
If not then we would get an exception thrown.

Testcase Number: TC_02

Testcase Objective: Check if the selected product is added in the cart

Steps:
1. Navigate to demo.opencart.com
2. Click on Search bar and Search your needed product. 
3. Click on "Add to Cart" and try viewing it in View Cart

Expected Result:

If the item is added in the cart, there will "Verified the search item has been added to the cart" message will be displayed. 
If the item is not present, Exception would be thrown.

Actual Result: <After Execution>

Priority: High

# In the 3rd test method:

I have verified whether currency change is displayed on the screen when changing the currency from USD to EUR, if it changes then we would get a message "Currency has changed" if not we will get "Currency didn't change"

Testcase Number: TC_03

Testcase Objective: 
Steps:
1. Navigate to demo.opencart.com
2. Click on Currency dropdown, and convert from USD to EUR.

Expected Result:
Changed Currency should be available in the charges field.

Actual Result: <After Execution>

Priority: High

