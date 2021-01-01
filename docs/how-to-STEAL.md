# How to rip stylesheets from MySpace profiles
#### [← Back to Homepage](https://bonkmaykrq.github.io/)
  
###
**Please don't blatantly copy other's stylesheets without their explicit permission or if it comes with a license that allows you to do so.**  
**I will not be held responsible for your misuse of this information.**  
  
## Step 1
Visit the profile of the user you want to steal CSS from.  
#### For demonstration I will be using **psych0kitty**'s profile:  
![](https://files.gamebanana.com/bitpit/image_2021-01-01_000631.png)
  
## Step 2
Press F12 on your keyboard.  
Some laptops have shortcut keys that replace the function keys. To send an F12 input on those laptops, hold down the Fn key at one of the bottom corners.  
If for whatever reason F12 still does not work, press Ctrl + Shift + I, or right click and select Inspect Element.
  
#### **This should bring up the developer tools. On Chromium/Electron based browsers, it should look like this:**  
![](https://files.gamebanana.com/bitpit/image_2021-01-01_000757.png)  

## Step 2 3
Click "Console" at the top of the developer tools window.  
This will open a terminal where you can input Javascript.  
  
## Step 4
Paste this code into the console and press enter:  
`document.getElementsByTagName("body")[0].getElementsByTagName("style")[0].innerHTML;`  
  
You should now have a copy of the user's CSS, in double quotes.  
Don't forget to remove these quotes at the beginning and end of the CSS, if you don't the CSS will not work!  
![](https://files.gamebanana.com/bitpit/image_2021-01-01_000949.png)
