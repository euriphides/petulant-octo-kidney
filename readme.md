//Make sure you have git, nodejs and ruby installed on your computer.

//Then in the terminal window, while cd'd into where you want to install the project:

npm install -g bower grunt-cli
gem install foundation

//then, where "project_name" is the name of your project:

foundation new project_name --libsass

//now cd into the project folder and:

grunt build
grunt