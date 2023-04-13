+++
title = "IDE Setup"
weight = 2
+++

Our website is built using the .NET framework, which means that you'll need to use an IDE (integrated development environment) to work with our codebase. We recommend using Visual Studio, as it provides the best support for .NET development and can open .sln files (solution files) directly.

#### Open .sln
To open the .sln file for our website using Visual Studio, follow these steps:

1. Open Visual Studio.
2. Click on the **File** menu, and then select **Open** > **Project/Solution**.
3. Navigate to the directory where the .sln file is located.
4. Select the .sln file, and then click **Open**.

Visual Studio will now load the solution file and display the project files in the Solution Explorer. From here, you can edit, build, and debug our website.

Overall, having a good understanding of .NET development and using an IDE like Visual Studio is essential to working with our website and ensuring its success.

### Projects 
This will open 4 projects, [Domain, Repository, Mortgage-Market, WebAppView]:

- **WebAppView:** All the Website pages are in WebAppView folder. 
- **Mortgage-Market:** Contains all the middleware files. 

**These two projects are only needed for website related work.*

### Startup Projects

To view your edits and for publishing, you need to set Startup Projects: 

1. In Solution Explorer, select the solution (the top node).
2. Choose the solution node's context (right-click) menu and then choose Properties. The Solution Property Pages dialog box appears.
3. Expand the Common Properties node, and choose Startup Project.
4. Choose the Multiple Startup Projects option and set the appropriate actions.