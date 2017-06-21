# Pulse Microsystems MVC Sample Program #1 Instructions

## Instructions

Using ASP.NET MVC 3, 4 or 5, C#, and HTML5, create a web application that allows:

* Selection of a "template".
* Changing properties of that "template".
* Saving the final data (template identifier + changed properties + user information) to persistent storage (file, database, etc.)

Include a readme.txt with any installation instructions and extra notes.

ZIP up the entire project and include it with your resume, or post it somewhere for download and include download instructions.

### Additional options for bonus points:

* "Realtime" visual updating of the template based on the changed properties
* Use [SignalR](https://github.com/SignalR/SignalR) for *anything*

## Requirements

* Please use Visual Studio 2015 or 2017. For this purpose, the free Community editions are as good as the enterprise editions. Visual Studio Community 2017 can be downloaded from [here](https://www.visualstudio.com/vs/visual-studio-express/). Visual Studio Express 2015 can be downloaded from [here](https://www.visualstudio.com/post-download-vs/?sku=xweb&clcid=0x409&telem=ga).
* Use of Flash or Silverlight is not permitted. The application must be 100% browser-based (web server assisted) using HTML/HTML5. It must run in Internet Explorer 9/10/11 and/or Google Chrome and/or Mozilla Firefox. For Chrome and Firefox they should be up to date using the latest version.
* Use of Javascript libraries is permitted (such as jQuery, KnockoutJS, SignalR, etc.), even encouraged.
* Use of 3rd party libraries is permitted. Please document what 3rd party libraries were used so we know what is yours and what is not.

## FAQ

### What is a template?

A template can be anything you want it to be, as long as it has something that can be modified by the user. Each template should have a unique set of customizable fields.

A simple example:

Allow your user to select from "Template 1", "Template 2", or "Template 3".

* Template 1 includes customizable options such as "First Name" and "Last Name", see [sample screenshot](https://github.com/pulsemicro/mvc-sample-1-instructions/raw/master/MvcSample1-Template1.PNG)
* Template 2 includes customizable options such as "Home Town", see [sample screenshot](https://github.com/pulsemicro/mvc-sample-1-instructions/raw/master/MvcSample1-Template2.PNG)
* Template 3 includes customizable options such as "Spouse's Name", "Kid's Name #1", "Kid's Name #2", etc., see [sample screenshot](https://github.com/pulsemicro/mvc-sample-1-instructions/raw/master/MvcSample1-Template3.PNG)
  * Note: In the sample file there is a "Your Name" and "Your Address" field. Thses are just recommendations and could be anything you choose.

### Can I use other technologies instead of ASP.NET MVC, such as ASP.NET Web Forms, PHP, or Ruby?

No. Our projects will be built using ASP.NET MVC, so we are looking for someone well versed in ASP.NET MVC.

### Can I post my sample application somewhere (such as Microsoft Azure) for you to see?

You can, and this will help us when executing your sample application. But we still want to see the source code.

### How long should this project take?

We wrote an acceptable project with the minimum requirements (no extras) in **61 minutes**. We used Visual Studio 2012, ASP.NET MVC4, and [KnockoutJS](http://knockoutjs.com/).  It took an additional 2 minutes to add "Realtime Preview" (extra option #1).
