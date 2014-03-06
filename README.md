## To make your first component

###  1. Fork this repo

Just click the fork button in the top right of this page.

###  2. Rename it (e.g. my-component)

In the right hand column, click on the screwdriver/wrench icon for Settings.

###  3. Git clone it to your computer

The usual git clone command will work.


### 4. Install node and grunt

Install [node.js](http://nodejs.org/) on your machine, then install Grunt via the command line...

```
npm install -g grunt-cli
```


###  5. Install & Run the Component

On the command line...

```
cd <wherever you cloned it>
npm install
grunt
```

You'll be prompted to name your component after running the `grunt` command. You can pick a new name or leave it blank.

###  6. Add a Security Exception

* Load the URL from Step 4 into your browser.
* The browser will complain that the security certificate is not trusted.
* That's okay - add an exception, this will allow the component to work in Appmaker.

###  7. Teach Appmaker where you find your new component

* Go to [Appmaker](https://appmaker-integration.herokuapp.com/designer) - We'll be using the Integration version for the workshop.
* Sign in.
* In the menu with your email address, click on 'Add a Component'.
* Specify the URL that Step 5 gives you.

### 8. Edit the Component

As the component files are changed, the local server will udpate; Refresh the designer to make it load the new version. (we hope to streamline this later).

[Learn how Components Work](https://github.com/mozilla-appmaker/appmaker/wiki/How-Components-are-Built)

### 9. Use Grunt Lint to catch Errors

To catch errors in your component code, run the following command on the command line in your component folder...

```
grunt lint
```

It will identify syntax errors in your component and help you troubleshoot.
