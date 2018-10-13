
# Mobile App Tech Talk Setup
Follow the steps below to get Ionic installed on your machine. If you have any questions, bring them on Thursday and we can help you get setup.

### 1. Install NPM

Open up your terminal and check if you have npm:

```
npm -v
```

If you see a version number, then you’re set. If you see “command not found: npm” (or some equivalent), then you can visit https://nodejs.org/en/ and install it (in case you’re wondering why I took you to a node.js site, npm is packaged with node.js).


### 2. Install Ionic
Ionic is a framework that allows us to write mobile apps for both Android and iOS. With npm installed, you can install Ionic from the command line:

```
npm install -g ionic cordova
```

> Note that the `-g` specifies a global install. If you're on Windows, you may need to open an Admin command prompt. For Mac/Linux, you may need to use `sudo` 
*Bonus:* Check out [the Ionic Website](https://ionicframework.com/docs/intro/installation/) for a quick tutorial


### 3. Install Git
Check to see if you have git installed already
```
git --version 
```

If a version shows up, you’re good to go. If not, go to https://git-scm.com/book/en/v2/Getting-Started-Installing-Git and find the installation instructions for your computer. 


### 4. Clone the Project Files
With git installed, navigate to a folder on your computer though your command line where you don’t mind having the tutorial project. Once you’re there, enter:

```
git clone https://github.com/bqmackay/weather_or_not.git
```
Once that’s done, go inside that folder and run the following Ionic command:

```
ionic serve
```

A browser should pop up with the application. Depending on when you pull this down, you may see something like “The world is your oyster”. If you get this far, than you’re all ready to go on Thursday. If you run into issues, you can either use the Ionic docs or Google to troubleshoot or shoot me an email at steve.godderidge@gmail.com. 
