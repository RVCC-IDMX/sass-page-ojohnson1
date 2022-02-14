#SCSS File System

<p> This project has five folders. All folders are contained in the scss folder.The main..scss folder contains four folders that have stylesheets that outline parts of the site. The utilies folder includes these files : <strong>_functions.scss</strong> <strong>_variables.scss</strong> <strong>_mixins.scss,</strong>
 <br>
 They all included variables and styles. _functions.scss file has code to automate the change in appearance of the page. The mixins.scss file has predefined parameters that can be applied to elements in the stylesheet. The _variables.scss contains predefined colors. Reusing these variables will increases this site's cohesiveness. 
 <br>
 The base folder contains these files:<strong>_reset.scss</strong> <strong> _typography.scss</strong>The _reset.scss file will reset the elements in this HTML to a margin and padding of 0. The typography page uses variables to define the font-family such as "$font". You can see this variable being used in the _home.scss file to use the "*Fraunces*"  font-family for the body of the page. </p>
 
 <p>The components folder has the structural rules for the header in the <strong>_header.scss </strong>file. The header is predefined with mixin parameters.  The pages folder is for each individual page style. For this project there is only one page. The<.scss> main .scss </strong>file has to imports of the reset file and the home file. These are listed in the order they should be applied.</p>
