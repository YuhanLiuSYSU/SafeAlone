# SafeAlone
Android app which helps alert your friend when you are ill. When you click "TRACK", the app will track your activation time and location. If you haven't tracked for the time period longer than the "inactive time", it will send an email automatically to your friend along with your last three activation information, and ask him/her to see whether you are alright. 

1. To use this app, you need to install Android Studio in your PC and use AS to install it on your android phone. Gmail service is
required. For some reason, your email and password should be entered in a hardcore way. Just go to 

SafeAlone\app\src\main\java\com\example\safealone\LongOperation.java

and set "sender_email" and "pwd". And in your gmail setting, change account access for less secure apps https://www.google.com/settings/security/lesssecureapps


2. The part on using GPS is modified from the source code obtained from
 http://rdcworld-android.blogspot.com/2012/01/get-current-location-coordinates-city.html
 
 The part on sending email on background is modified from the source code from
 https://stackoverflow.com/questions/2020088/sending-email-in-android-using-javamail-api-without-using-the-default-built-in-a
 and  http://pointofandroid.blogspot.com/2017/02/send-mail-in-background-send-mail.html written by pankaj gurjar.
 
 Thank you very much for making your codes available online :)
 
3. This app can only be used for non-profitable personal usage. Have fun!

