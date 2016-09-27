Subscriber War
===
Subscriber War is a live, textpunk YouTube subscriber counter written in Python3.  
![Screenie](https://i.sli.mg/q9g6Uo.png)  
To start it, make sure you have Python3 installed and an [API key registered with YouTube](https://developers.google.com/youtube/android/player/register), place 
the API key in the file "apiKey.txt" and run:  
```
./subWar.py
```  

Adding users to monitor is simple, just use the addUser() function:  
```
addUser(<NAME TO DISPLAY>,<CHANNEL ID>,<COLOR>)
```

Version 0.1
Original

Version 0.2
- getSubs() now takes a username instead of channelID
- Exchanged playerList for number of players
- addUser() to now take only displayName & channelName
- randomColor() gives a randomColor to each user
