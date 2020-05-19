# llSPS-INT-131-AI-Powered-News-Search-App-Level-1-
AI Powered News Search App (Level-1)

The video presentation can be accessed through:-

https://drive.google.com/file/d/1Yob1MoiKt5f-C3ZWPvhNwFNdBmG3K1Wd/view?usp=sharing


#TO ACCESS JSON NODE RED FILE THROUGH IBM CLOUD

Starter Kit application
Log in or sign-up for an account at cloud.ibm.com

Navigate to the catalog and search for ‘Node-RED’. This will present you with the Node-RED Starter. This gives you a Node-RED instance running as a Cloud Foundry application. It also provides a Cloudant database instance and a collection of nodes that make it easy to access various IBM Cloud services.

Click the starter application you want to use, give it a name and click create.

A couple of minutes later, you’ll be able to access your instance of Node-RED at https://<yourAppName>.mybluemix.net

Customising your Node-RED application
To start customising your instance of Node-RED, you can either download the application locally or you can enable the Continuous Delivery integration option via your application’s IBM Cloud dashboard page. That will create a git repository on either GitHub or IBM DevOps services, from where you can customize your Node-RED, save the changes and automatically update the application in IBM Cloud.

Securing the editor
When you first ran the Node-RED instance you were presented with some options to secure the editor. To change those options, you can set some environment variables from either the IBM Cloud console or the cf command-line

In the IBM Cloud dashboard, select the ‘Environment Variables’ page for your application
Add the required user-defined variables:
NODE_RED_USERNAME - the username to secure the editor with
NODE_RED_PASSWORD - the password to secure the editor with
NODE_RED_GUEST_ACCESS - set to true to allow anonymous users to have read-only access to the editor
Click Save.

Your node red account get ready and now you can import the json file and access the flow.
<The flows created in Node-RED are stored using JSON which can be easily imported and exported for sharing with others.>
Adding nodes
You can add nodes from within the editor. Select the manage palette option from the dropdown menu within the editor.

Alternatively, you can edit the application’s package.json file and add the required node modules in the dependencies section.
The format is: "node-red-node-package-name":"x.x.x" Where x.x.x is the desired version number.

#TO ACCESS LOCALLY

Installing with npm

To install Node-RED you can use the npm command that comes with node.js:

sudo npm install -g --unsafe-perm node-red

This command will install Node-RED as a global module along with its dependencies.
You can confirm it has succeeded if the end of the command output looks similar to:

+ node-red@1.0.0
added 332 packages from 341 contributors in 18.494s
found 0 vulnerabilities

Installing with docker

To run in Docker in its simplest form just run:

docker run -it -p 1880:1880 --name mynodered nodered/node-red
For more detailed information see our docker guide.

Installing with snap

If your OS supports Snap you can install Node-RED with:

sudo snap install node-red

#To run node red through git

To run Node-RED from source you will need:

a supported version of Node.js.
a git client
the grunt-cli npm module installed globally:
sudo npm install -g grunt-cli
Cloning the code and installing dependencies
You can clone the source repository directly from GitHub:

git clone https://github.com/node-red/node-red.git


Result:-

https://samikshanodered.eu-gb.mybluemix.net/ui
