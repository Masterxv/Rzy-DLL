# Rzy-DLL

This dll is for .net applications that you see on a lot of products that are sold everywhere. This dll is made to get your program somes better protections.
How to use it?
WARNING: You need to have the System.Management dll !
1. Add RzyProtector.dll as a reference 
2. using RzyProtector;

Features:
RzyProtector.Protector.appCheckHash("link of your website file with your app hash"); | Check the MD5 hash of your application.
RzyProtector.Protector.DownloadString("link"); | Same as Webclient, more faster for you when you make lot of functions with the webclient downloadstring.
RzyProtector.Protector.GetMD5(); | Get the MD5 hash of your application.
RzyProtector.Protector.AntiShit(); | Use this when user click on login or smthg, it check if somes programs like fiddler is open, if yes your application close.
RzyProtector.Protector.DeleteFile("path"); | Delete a file silently.
RzyProtector.Protector.StopComputer(); | Stop computer of the user
RzyProtector.Protector.Download("link", "path"); | Same as webclient function, but more faster when you use downloadfile on lot of functions.
RzyProtector.Protector.getHwid(); | Copy the user HWID on his clipboard.
RzyProtector.Protector.GetUserIP(); | Get the current user IP address. Good to make an ip whitelist or smthg like that.

Please keep in mind that this dll is free, I did it for the community. And don't msg me about this, except if you get any errors.
