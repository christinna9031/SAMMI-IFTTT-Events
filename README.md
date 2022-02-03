# LioranBoard IFTTT Events
 Extension for LioranBoard which lets you fire IFTTT events.  
IFTTT is a very powerful app that connects to a lot of different services, such as your phone apps, smart devices, email, social media etc. Full list can be found here: https://ifttt.com/services. You can create 3 applets for free.  

**Special thanks goes to [MisterK](twitch.tv/misterk_qc) for migrating the extension to LioranBoard 2.** 
   
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
4. Create a new button in LB and add IFTTT event extension command. Paste your IFTTT key and event name. Value 1, value 2 and value 3 is what you want to parse once you trigger the event. This way you can let your viewers easily control your Philips Hue Lights and parse variables such as brightness, color, etc. You can choose to enable/disable proxy to see which one will work more consistently for you. It is using my own Heroku proxy since the default one has been extremely unreliable and slow lately. Feel free to change the .lbe file to use your own.
5. Yellow notification message "IFTTT event has been fired" means IFTTT received your request.   

[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)

DISCLAIMER: The extension is provided as is. The developer has no obligation to provide maintenance and support services or handle any bug reports.
Feel free to edit the extension for your own use. You may not distribute, sell or publish it without the author’s permission.
