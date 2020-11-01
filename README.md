# IdentityFramework
The samples in this repository demonstrate how to create user, Role & assign user to role using Identity framework and MVC Core.

# In this sample I create a WebAPI Controller - UserManagerController
# SignUp methods of UserManagerController class create user which is provide via UserVM ViewModel class.
# To test SignUp methods Run the projects and open Postman. If you have not installed Postman download it from this link https://www.postman.com/downloads/ & installed.
# Copy  url https://localhost:44317/api/UserManager and paste in Postman and select POST from dropdownlist. Provide a user object like that 
  {"UserName":"Kamal",
	"Email":"s@ss.com",
	"Password":"@Test123"
}
and hit on SEND button.
# You will see Kamal user is created.
# To create role Copy and past url https://localhost:44317/api/UserManager/Roles?roleName=Sales . select POST and hit Send button.
# To Login and get Token copy and paste https://localhost:44317/api/UserManager/signin and provide login credential like this 
  
  {"UserName":"Kamal",
	
	"Password":"@Test123"
}
# After successful login you will get Token to access authorized resources.
If you have any questions,  feel free to email .
