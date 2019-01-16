# HTML Snippets

Simple CSS & JS snippets of code intented to be used with [AEM](https://www.adobe.com/marketing/experience-manager.html) instances to further customize the UX of websites while custom components are being developed.

# How to use it!
  - Add a paragraph, text box at the top of your site
  - Open CRXDE
  - Navigate to the directory that contains your website
  - Within this directory, navigate to ```jcr:content/par/text_box```
  - In the properties of the textbox, replace the content of ```Text``` with the desired HTML snippet. Both CSS and JS files must be placed in here.


> This code was built for a specific instance of AEM. Nonetheless, other than the class names, it should be generalizable for other HTML projects / AEM projects