# SecureWhistler Chat App |  1.0.0 βeta
An encrypted chat app so an anonymous source stays anonymous.

##Setup
* `git clone` this repository
* Install the npm dependencies, simply run `npm install`
* Run `node server.js`



## Instructions
This web application was built with Mongodb, Express, Socket.io, and Node.  In order to get this secure application to run, you'll need to download node - You can do that  [here](https://nodejs.org/en/).  

If you have brew installed already, you can just install the pre-built package with this command:
```
brew install node
```
Once node is installed, you'll also need to get a copy of [Mongodb from here](https://www.mongodb.org/downloads#production). This can be done from brew with this command:
```
brew install mongodb
```
Once you have setup both node and mongodb, clone down the repository from github with this command:
```
git clone git@github.com:jenniferkahn/secureWhistler.git
```
After the repository has been installed, start your instance of mongodb.  This can be done from the command line with this command:
```
sudo mongod
```
Once mongo is running, navigate to the directory where you cloned the github repository and run the following commands to install other dependencies.
```
npm install
```
To start the server, run this command:
```
npm start
```
OR
```
node server.js
```
Now, navigate to http://localhost:3000/ in your web browser to see the app.

![Alt Text](http://i.imgur.com/gkJB0V0.png?1)
