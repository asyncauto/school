
#### Testing  
**What**  
Testing happens after  feature development is complete and before it goes to people for use.   

During this process we need to ensure that  

1. The new feature is working as expected  
2. The existing features aren't broken  
	1. Give prioriy to critical functions   

**Why**  
The purpose of testing is to create enough confidence in the system. Even though nothing has changed in some section of the app, we test it periodically to have confidence that all is good. 

**How**  
1. Proactively avoid worst case scenarios which can happen during testing  
This is usually:  

- Production Data loss/corruption  
	- avoid storing production database credentials in the local system  
- Emails going to unintended addresses
	- don't use production user data in the testing system  
	 
2. Create a map before testing  
	Before you start testing, you should know when will the testing be over. What features do I need to cover? Create a list of those. Higher the granularity the better. Example:  

		- [ ] User Authentication is working
			- [ ] Sign up page is loading
			- [ ] Sign up is working
			- [ ] Login page is loading
			- [ ] Login is working
			- [ ] I am able to reset my password
				- [ ] forgot password page is loading
				- [ ] reset password email is received
				- [ ] reset password is working
3. Systematically cover the map
Once you have the map of features to be tested, it's exploration time. ([Set up your app locally]() if you haven't already. ) Go through each of the feature and add notes against them if you notice something abnormal. Share your report with the product and development team.


**Guidelines for covering cases exhaustively**   
- Identify different user roles and their functions. For each role, the implementation might be different.  
- *Routes* will have the list of all URLs used in the app.   

