# Vinyl Tracker

#### What is this?
Vinyl Tracker is a little project I picked up to organize my record collection. I am not too knowledgable in music and I do not want to research each title when I am trying to play something I have never listened to. 
So I thought, it would be nice to have an app that allows me to enter all my albums and singles and have a programm collect all the information I would need to make a choice. I would also love this program to be availble to my guests, so that they can view my collection and choose something they might want to listen to. 

#### So, what does it do?
The allows you to create a user account and store your old records as a sort of index. You can also use the app without an account if you do not want to use the service with muliple people.

Metainformation is included in the index.

A detailed breakdown of all automatically collected information can be found here: 

| Metadata | Description | Source | Required Credentials | Name in .env file |
| -------- | ----------- | ------ | -------------------- | ----------------- |
| Album Cover | The Cover of the Album or Single. Not necessarily the right one | | |
| Song List | A list of the names of all songs on the record | | |
| Lyrics | Lyrics for each Song on the record | | |
| Playtime | Playtime of each song on the record | | |

There is also data that the user adds themseves such as the Album Name in order for the app to fetch all the information and a rating so that they can also sort by rating if they so desire. 
In essence this app is an iTunes that you can host yourself and use with friends and family.
#### Why do we need such an app?
The short answer is we do not.
I wanted to build something and I had this problem to solve. I am aware, that there is plenty of options out there that do this. However, I wanted something that I can host myself and that does not require and online account or trust towards a third party. This is why this project is open source and free to use and distribute in a non commercial setting. It is targeted and tinkerers and privacy enthusiasts that want to stay in control of their data. 
This app will NEVER send any of your data anywhere and it will not collect information on you (unless you make it do that yourself). All data is stored locally.