# LogIn
### A simple USB password barrier.
![It should look somewhat like this](https://snag.gy/av9mRn.jpg)
### How Do I Use This Program?
To use, simply, enter in the drive letter of the USB device and the correct password; click 'Log In' and the folder containing all your files will pop up!

### How Do I Install LogIn?
To install, drag the 'LogIn.jar' file and the 'lib' folder from the 'dist' folder into your USB root folder. Then create a new folder called 'Main' (without the ' ' but with the capital M) and place all your folders you wish to hide inside the 'Main' folder. Finally, edit the properties of both the 'lib' & 'Main' folders and check the Hide button (making sure just to hide the folders and not the contents of them).
Note: To more securely hide the 'Main' folder follow [THIS LINK](http://www.howtogeek.com/104825/make-a-super-hidden-folder-in-windows-without-any-extra-software/), to find a tutorial.

### How Do I Change The Password?
By default the password is 'password', if you want to change it you need to, first open the LogIn project in [Netbeans IDE](https://netbeans.org/features/index.html) and navigate line 133 in the 'Window.java' class. It should look somewhat like this:
![It should look somewhat like this](https://snag.gy/9C7zqR.jpg)
Then open up the 'Encryption.jar' in the 'Encryption' folder; type your password into the text field and hit Encrypt once.  Your password will be replaced with an long line of numbers, letters, and symbols; copy this and replace W6ph5Mm5Pz8GgiULbPgzG37mj9g= (located between the "s on line 133) with it. Save and Build the project, and a version of the LogIn program with your new password will be located in the 'dist' folder.

The source for the Encryption program is [HERE](https://github.com/Snowball2047/Encryption)
