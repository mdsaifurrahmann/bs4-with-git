# BS4-WITH-GIT
use Bootstrap 4.3.1 and Font-Awesome 5.8.1 using Git Bash. Includes Complete Bootstrap 4 dev environment with gulp, global gulp-cli and sass.

# gulp Dependencies and Command
Use <code>$ npm install gulp browser-sync gulp-sass --save-dev</code> command.</br>
then use <code>$ gulp</code> this Command. If this command say "command is not found" then simply use <br> <code>$ npm install --global gulp-cli</code> this command.</br>
Then Re-enter <code>$ gulp</code> command. It will work Fine.

# Font-Awesome Compile
Use <code>@fortawesome/fontawesome-free</code> instead of <code>fontawesome</code> for Use Latest Font-Awesome.
If you Want to use Old Font-Awesome, then use normal <code>fontaweome</code> command and use the <code>old-gulpfile.js</code>.
### Note:
Rename the <code>old-gulpfile.js</code> file to <code>gulpfile.js</code> for use old Font-Awesome and don't use the new gulpfile.js that contain latest font-awesome.

# Compile Sass & Run Dev Server
<code>$ npm start</code>
Files are compiled into <code>/src</code> folder.

# Explaination
<code>gulp-cli</code> stand for gulp-CommandLineInterface.
