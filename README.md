# Twitch ticker chat
Horizontal chat for twitch. News ticker like chat.
Chat supports twitch and BTTV emotes. No any user badge support.

This chat using [tmi.js](https://tmijs.com/).

## Settings
1. Get your Twitch channel ID.
2. Set your channel name and channel ID in ***index.html***
```
    // Put your twitch ID here.
    const channelID = '61220092';
    // Put your twitch channel name.
    const channelName = 'PavlikBender';
```
3. Set up message separator in ***index.html***, if you needed:
```
    // Message separator.
    const separator = '&nbsp;&nbsp;▪&nbsp;&nbsp;'
```
4. Test it by opening index.html in your browser. 
Type something in your chat it should immediately appear in ***index.html*** page.
5. Add ***index.html*** as local browser source in your OBS programm. 
*Recommended height: 50px.*
7. PROFIT!!!
