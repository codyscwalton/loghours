# loghours
Automation built to enter hours into BambooHR

Initially built using Selenium

**Required**

ZSH:

> sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

Homebrew:

> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

node (the Node.js programming language) version 8 or 10

npm (the NodeJS package manager) which typically gets installed with node

> brew install node

selenium-side-runner (the Selenium IDE command line runner)

> npm install -g selenium-side-runner

and the browser driver we want to use (Chrome)

> npm install -g chromedriver

Once everything's installed, running your tests is a simple matter of calling selenium-side-runner from the command-line followed by the path to the project file saved earlier

> selenium-side-runner /path/to/your-project.side

Steps to configure:

Download loghours.side

Open it with preferred IDE

There will be two feilds to modify, sroll until you see "value": "ENTER_EMAIL" and type in your Subsplash email, then scroll until you see "value": "ENTER_PASSWORD" and enter your password to your Google account.

Save the file and move it to a permenant spot on your computer (Ex. I have a folder in my user called Subsplash and it is stored in there) 

Find the path of the file, it will look something like this: 

> /Users/codywalton/Subsplash/loghours.side

Once we are at this point you can add it to part of a workflow in Alfred.
