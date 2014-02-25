## To make your first component

###  1. Fork this repo

Just click the fork button in the top right of this page.

###  2. Rename it (e.g. my-component)

In the right hand column, click on the screwdriver/wrench icon for Settings.

###  3. Git clone it to your computer

The usual git clone command will work.

###  4. In your terminal window:

```
cd <wherever you cloned it>
npm install
grunt
```

###  5. Add a Security Exception

* Load the URL from Step 4 into your browser
* The browser will complain  that the security certificate is not trusted
* That's okay - add an exception, this will allow the component to work in Appmaker.

###  6. Teach Appmaker where you find your new component

* Go to Appmaker
* Sign in
* In the menu with your email address, click on 'Add a Component'
* Specify the URL that Step 4 gives you.

### 7. Edit component.html

As the file is changed, the local server will udpate; Refresh the designer to make it load the new version. (we hope to streamline this later).

