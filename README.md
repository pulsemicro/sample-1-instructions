# Tajima Software Sample Program Instructions

## Instructions

Using .NET 8 as a backend for a Web API project and any front-end framework of your choice, create a web application that allows:

* Selection of a "template".
* Changing properties of that "template".
* Saving the final data (template identifier + changed properties + user information) to persistent storage (file, database, etc.)

Include a readme document with any building instructions and/or installation instructions and extra notes for anything else required if applicable.

ZIP up the entire project and include it with your resume, or post it somewhere for download and include download instructions.

### Additional options for bonus points:

* A page (or pages) that list the final data that was stored to the persistent storage of choice
* "Realtime" visual updating of the template based on the changed properties
* Use [SignalR](https://dotnet.microsoft.com/en-us/apps/aspnet/signalr) or another protocol of your choice for *anything*

## Requirements

* Please use Visual Studio 2022 Community or Visual Studio Code. For this purpose, the free Community editions are as good as the enterprise editions. Visual Studio Community 2022 can be downloaded from [here](https://visualstudio.microsoft.com/vs/community/). Visual Studio Code can be downloaded from [here](https://code.visualstudio.com/Download).
* The front-end application must be 100% browser-based (back end server assisted). It must run in Google Chrome and/or Mozilla Firefox and/or Edge. For Chrome, Firefox, and Edge, they should be up to date using the latest version.
* Use of Javascript libraries is permitted (such as jQuery, React, Vue, KnockoutJS, etc.), even encouraged.
* Use of 3rd party libraries is permitted. Please document what 3rd party libraries were used so we know what is yours and what is not.

## FAQ

### What is a template?

A template can be anything you want it to be, as long as it has something that can be modified by the user. Each template should have a unique set of customizable fields.

A simple example:

Allow your user to select from "Template 1", "Template 2", or "Template 3".

* Template 1 includes customizable options such as "First Name" and "Last Name", see [sample screenshot](https://github.com/pulsemicro/mvc-sample-1-instructions/raw/master/MvcSample1-Template1.PNG)
* Template 2 includes customizable options such as "Home Town", see [sample screenshot](https://github.com/pulsemicro/mvc-sample-1-instructions/raw/master/MvcSample1-Template2.PNG)
* Template 3 includes customizable options such as "Spouse's Name", "Kid's Name #1", "Kid's Name #2", etc., see [sample screenshot](https://github.com/pulsemicro/mvc-sample-1-instructions/raw/master/MvcSample1-Template3.PNG)
  * Note: In the sample file there is a "Your Name" and "Your Address" field. These are just recommendations and could be anything you choose.

### Can I use other technologies instead of .NET 8 for the backend and Javascript frameworks for the frontend such as PHP, or Ruby, Python?

While these are acceptable alternatives, we would like this to be built using .NET 8. So, we are looking for someone well versed in C# and .NET. If the entire solution is C# MVC based, we will not overlook this as a solution to the problem. There are options to create an MVC based front end and backend in .NET 8. An ASP.NET Core Web App (Model-View-Controller) that also includes an ASP.NET Core Web API project.

### Can I post my sample application somewhere in the Cloud (Google, Azure, etc) for you to see?

You can, and this will help us when executing your sample application. But we still want to see the source code.

