# LB IFTTT Events
 Extension for LioranBoard which lets you fire IFTTT events.  
IFTTT is a very powerful app that connects to a lot of different services, such as your phone apps, smart devices, email, social media etc. Full list can be found here: https://ifttt.com/services. You can create 3 applets for free.  
   
**Instructions:**      
1. Install the extension.  
2. Make a new account at https://ifttt.com/join if needed. Go to https://ifttt.com/maker_webhooks. Click on Connect and click on Documentation. Copy your key.  
3. a) Go to https://ifttt.com/create/, click on If This-Add.  
b) Search and click on Webhooks-receive a web request.   
c) Choose your event name and click on Create Trigger.   
d) Click on Then That-Add. Choose your service you want to trigger. Next screen will depend on what you selected here.   
e) In this example, let's say we selected Email and clicked on Send me an email. At this point you will be asked to connect IFTTT to your email.  After verifying it and clicking on Connect, you can customize the Subject, Body and add ingredients (variables). You can parse up to 3 variables (value1, value2, value3) from LioranBoard. For example, if someone redeems a point reward on your stream, you can automatically send yourself an email containing the viewer's name, name of the reward and their message.   
f) Once you're done customizing the body, click on Create action.   
g) Click Continue, customize your Applet Title and click Finish. Your applet should be live now.   
4. Create a new button in LB - Add Commands - Send to Extension - IFTTT event. Paste your IFTTT key and event name. Value 1, value 2 and value 3 is what you want to parse once you trigger the event. This way you can let your viewers easily control your Philips Hue Lights and parse variables such as brightness, color, etc. You can choose to enable/disable proxy to see which one will work more consistently for you. It is using my own Heroku proxy since the default one has been extremely unreliable and slow lately. Feel free to change the .lbe file to use your own.
5. Yellow notification message "IFTTT event has been fired" means IFTTT received your request.   




**How to install an extension:**
1. Download the .lbe extension file
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
<<<<<<< HEAD
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.    


[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)
