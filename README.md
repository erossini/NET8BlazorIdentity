# NET8 Blazor Identity

Every time we build an application, the first point of concern is how to manage the users and their roles and the security across the application. 
The basic essence of the requirement is always the same, which is to register, login, authorize users, roles, and so on. 
So, to help ease the user management process, Microsoft comes up with a default implementation of User Management. 
The name is Microsoft Identity, Also, it has built-in UI to support various user functionalities.

You find the posts of this project on [PureSourceCode](https://puresourcecode.com):

- [Custom User Management with NET8 and Blazor](https://puresourcecode.com/dotnet/blazor/custom-user-management-with-net8-and-blazor/)

If you find this code useful, please consider making a donation on [GitHub](https://github.com/sponsors/erossini).

This solution is a boilerplate for the implementation of common functionalities like:

- add a schema and change the name of the Identity tables
- custom fields in the `ApplicationUser` (such as _FirstName_, _LastName_...)
- display the first name of the user of the username if the name is empty
