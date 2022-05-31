# MHF-Z-Personal-Adjustments-W.I.P.
This is just some personal adjustments I'm doing to MHF-Z by myself for some personal reasons. So this is just a patch that I see necessary for myself and of course is just a W.I.P. that I might end up not finishing if some criteria that I'm thinking meet it. I also am aware of my own skills so I won't give anyone hope about anything. As said, this is some personal work mainly for myself and I know that some people might be interested and then I'm sharing this.

## Known Bugs
**Urgent Quest won't trigger**: If you already have a character when you change for these files, the key quest progression will be lost and you'll need to manually reset this, even changing to vanilla's file won't clear it and the urgent quest won't trigger. To do so, make use of the cool manager Chakratos made, there is a function to reset the key quest flag there: https://github.com/Chakratos/mhf-save-manager/releases

## Why are you doing this?
Simply because I want, it hurts so much in my soul to play the game like it was. A lot of content is simply skipped, this is not the same game I started back in 2011. Plus I'm determined enough to do this and improve it way more than this!

## But Fist is doing/done it, why don't you wait?
Personally I disagree with at least 90% of what Fist stated in that rebalancement system of his, the only points I agree are the ones I consider myself a necessity, like returning some system back to a previous state of the game. Also if I have some knowledge and can do things myself, why should I wait? I disagree with a lot of stuff, but I respect everyone and I hope everyone else can respect me as well.

## Now that I justified the above I'll tell everything about this:

* No cheat, just no, never, don't even complain!

* The most time consuming work here is the armour's upgrade system, I've been working for the last weeks to revert them back, of course this is not finished and I'll be working more on those, unless... For now rest assured that I did all the "normal", Goushu and Exotic armours, aside from the Exotic and 2 Goushu monsters the rest are all the original upgrades from a previous version and I even might need to work on that, if you find anything wrong with those just tell me, it takes so long doing this alone and it's worse not having any tool to work with this, but whatever.

* More key quests were added to the quest list. The intention behind this is to try to make everybody enjoy a bit more of the HR which was the main content of this game for so many years, there are a lot of content there but if you play it like it was left you'll simply skip it like it was nothing.

* I added some restriction to early GR content that would make everybody skips it, again I want everybody to experience and enjoy the game as much as we can, so no skipping! Tied to that I modified something in the Navi, you won't even notice the changes there.

* I didn't lock the GR content behind key quests or GR level because it wasn't locked before, I can do that though, but I don't like that idea since we could do almost everything with the exception of the Burst/Origin and eventually the Exotic and since there is the Z content it would be really weird... Anyway, the Exotic is now accessible at GR300!

* Zenith content was pushed far to the end of the GR, Zenith 1 starts now at GR600, Zenith 2 is now GR700, Zenith 3 is now GR800 and Zenith 4 is now GR900. Don't need to rush to this content, personally it lacks a lot to be really worth it, sure it is nice to play and all but it's just not enough and you should go and play the GR and enjoy the other 160 monsters of the game instead of just 24.

## A slightly preview:

https://user-images.githubusercontent.com/68492734/157886782-8a193711-be47-4a3e-81da-a03f9ce8ddcb.mp4


## Clarification about my files:
I saw the other day Fist and others talking about this and I don't want any drama nor anything, but I took some time to clarify a few things here, not that there is any need to do so but I also don't feel like being treated like I didn't do any work and "stole" things while I put so much effort alone on doing this and shared by free will for those who wants that.

* Fistly I want to say that I have used Fist's mhfemd.bin file from the **public** version he officialy shared, this file as he stated are the unnerfed monsters statuses before the ZZ updates, it was in a link called eng.fist.moe, this is the last update and, again, **public** and not **stolen** from anyone! This version has the "cheat shop" and as you can see in the files name and date of the last time modified, you can see that it's the original and I got it by that time. If he didn't have done something about the webarchive you could still get it from there since someone made backups of those, I checked it a couple months ago. Also this file does not contains anything related to key quests or about the old armour upgrade system!

![patch](https://user-images.githubusercontent.com/68492734/159828680-f7d842a4-978d-4f1c-a682-6cd194e5ce73.png) 
![eng patch](https://user-images.githubusercontent.com/68492734/159838926-701cb031-cd0e-40a7-a796-cf3c10d1b99a.png)


* Secondly I used the mhfdat.bin file shared by MaiLBG to release the ENG version for anyone that wants it since Fist released (as far as I've found) only the "cheat shop" version, since I wanted to share it for non-JP readers as well and it didn't have the "cheat shop" and didn't have whatever the heck was that has in Fist's file for not being able to read all Road's Shop. It's a rebalanced work mostly for the armours upgrades, why would I release it with a cheat file? It makes no sense, right?
Just for you to know, I don't even use any ENG patch, I play it in JP since... well, I'm used to this game in JP like I played for years and I can read a lot of things. So my focus was always on editing the files for my clean JP version of my client, which also I got from a friend that played in the last week in the original servers and has his ID on the farewell video (my client was not up to date since the last time I've played it was on my PS3 and my PC client was from the G10.1 update).

* Thirdly I want to say that the additional key quests and GSR restrictions added in those files are not in any way related to whataver balance Fist is doing, since I don't have any information about the old HR system, which I think it's the ideal one, I reached the conclusion that in order to make myself and my friends to enjoy more of the HR100+ content (like we used to since I started back in 2011 in the Korean server) the only thing I could do about that was adding more key quests, mostly for the HR100+ (HR5 now) which was when the paid subscription started (way back then we could only play until HR10 if I remember well, the HR99 restriction is not that old) and has a lot of new monsters, so the key quest was not thought beforehand, I simply added a few quests to kinda force us to prepare ourselves for those challenges, for the ranks below it I just threw whatever was available since they don't have much content, I also reorganized the quest listing as you can see compared to the vanilla version. This took me only a few minutes to do. For the GSR restriction version I talked with some people playing and they asked to add key quests there too, I'm not fond of this idea but I'm not against it either, so I took a few hours to think about that and did it that way.

* I also recorded a video while I was doing this process and I'll share it below so you can have a look on what I did, but I'll state them here. First I searched inside the mhfdat.bin to find the materials, if you have an ID list you can easily find them, then I followed some patterns and found a table with some materials listed in there, then I found the start and end addresses, I exported that section from the mhfdat.bin and did the same with another file that had the old system (from the G6.1 version I got here: https://zenhax.com/viewtopic.php?t=1968). Then I copied all the tables from the old version to the current one and checked the upgrade mats ingame, that way I could find which table and address that that table were, after confirming that I just needed to check the upgrade list from MHSX2G (used this version: https://www.dropbox.com/sh/cv3p5dwda91ro6i/AABC0P7zZkE22JUjyd7-IlaSa/20151004?dl=0) and then searched through the old version, if it was there I would only need to copy the table to the current version, save it, then copy it back to the "test build" which is obviously the **public** "cheat" version mentioned above and finally check ingame if everything was right, what happened when I reached monsters that were released after the implementation of the Armour Spheres? I simply made up the tables, mostly of them are for the Exotic monsters, considering how good their armours are I simply added more mats to make it harder to upgrade.
Finally, the video showing what I did: https://www.youtube.com/watch?v=hFrzrrzjih8

I don't want any drama nor anything, but I refuse to let someone say that I didn't do anything and someone else instead did, I made this alone with my determination and I'll be keep working on this to improve it until I think it's good for me, I'll eventually learn and find more things, I don't need anyone telling me to stop or anything, I'll do that because I want to do!

## Last notes...
This is shared of free will and all the work here was done by myself alone, anyone can have these files and use them how they see fit.

Most of you might not even want this for any reason and all, so this shouldn't be forced onto people either.

This may be only for, perhaps crazy, people like me that likes it this way.

Lastly how everyone play is not my fault, people that want to cheat, skip or something like that will always do that no matter which game or whatever, if you are going to do this then simply don't use this patch, but for those that will use it, I hope they enjoy "some" of the original system content as much as I do.
