Update your resume.json file with whatever changes you need.
Run on the terminal, in this directory:
node generate_resume.js

this will create an updated index.html file.

To change your theme:

Search for a theme here:
https://registry.jsonresume.org/themes

then search for it here:
https://www.npmjs.com/

Once you have found it, grab the name of it and run this in the terminal:
npm install <NAME OF PACKAGE> 

The package name will be "jsonresume-theme-<NAME>".

Then update your script. Open up "generate_resume.json" and replace the `var theme` requirement with your new theme. Then run the node command above.
