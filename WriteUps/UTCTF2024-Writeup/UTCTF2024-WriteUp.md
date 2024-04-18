---
title: UTCTF 2024 - OSINT Collection WriteUp
author: Zell
tags: CTF, UTCTF, OSINT, CyberSecurity
---

# UTCTF 2024 - OSINT Collection WriteUp

## Table of Contents
  
* [**Web**](#Web)
    * [OSINT 1](#osint1)
    * [OSINT 2](#osint2)
    * [OSINT 3](#osint3)<br/><br/>

# Osint 1<a name="osint1"></a>

## Description of the challenge :

```
It seems like companies have document leaks all the time nowadays.
 I wonder if this company has any.
(NOTE: It turns out there's also an actual company named Kakuu in Japan. 
The real company is not in scope. Please don't try and hack them.)
By mzone (@mzone on discord)

Hints :

You're looking for a leaked document. You won't find it on their website.
Accounts online associated with the scenario should be (fairly) distinguishable.

Site :

[http://puffer.utctf.live:8756/](http://puffer.utctf.live:8756/)

Value : 568 points
```

Kakuu Corporation 

Team : 

Sophia Rodriguez

Alexander Johnson

Emily Chen 

Isabella Nguyen

Jacob Patel

**Cole Minerton**

Twitter : Cole Minerton ([https://twitter.com/coleminerton/with_replies](https://twitter.com/coleminerton/with_replies))

Bio : [https://linktr.ee/coleminerton](https://linktr.ee/coleminerton)

![Untitled](Osint%201%20351b70f39cb24573b4d5faedb2f68d4d/Untitled.png)

Confirmation that it’s the right way 

[https://mastodon.social/@coleminerton](https://mastodon.social/@coleminerton)

![Untitled](Osint%201%20351b70f39cb24573b4d5faedb2f68d4d/Untitled%201.png)

But nothing really important on Mastodon except for the confirmation 

So back to the linktr.ee

I went on reddit but nothing special too but we can see that’s Cole Minerton is a speedrunner so we go on his ytb channel checking if there is any run.

[https://www.youtube.com/watch?v=0CLDP8Gc4KE&ab_channel=ColeMinerton](https://www.youtube.com/watch?v=0CLDP8Gc4KE&ab_channel=ColeMinerton)

Nothing in the video, the comments and the description so let’s take a look at the description of the channel and BINGO we have a private discord server 

![Untitled](Osint%201%20351b70f39cb24573b4d5faedb2f68d4d/Untitled%202.png)

[https://discord.gg/re9ez8ey](https://discord.gg/re9ez8ey)

If we scroll a bit on the general channel we can see that there is a PDF file named : [trustly_contract.pdf](https://cdn.discordapp.com/attachments/1211103526818811936/1212603289993093120/trustly_contract.pdf?ex=661759d1&is=6604e4d1&hm=cce3507be31246c0ca009402e81d4ade5dccdff1901e8ac5621959b4f11aa888&)

![Untitled](Osint%201%20351b70f39cb24573b4d5faedb2f68d4d/Untitled%203.png)

When we download the pdf and open it we got the leaked document and the flag :

[https://cdn.discordapp.com/attachments/1211103526818811936/1212603289993093120/trustly_contract.pdf?ex=661759d1&is=6604e4d1&hm=cce3507be31246c0ca009402e81d4ade5dccdff1901e8ac5621959b4f11aa888&](https://cdn.discordapp.com/attachments/1211103526818811936/1212603289993093120/trustly_contract.pdf?ex=661759d1&is=6604e4d1&hm=cce3507be31246c0ca009402e81d4ade5dccdff1901e8ac5621959b4f11aa888&)

### Flag : utflag{discord_is_my_favorite_document_leaking_service}



# Osint 2<a name="osint2"></a>

## Description of the challenge :

```
Can you find where the person you identified in the first challenge lives? 
Flag format is City,State,Zip.
For example, if they live at UT Austin submit Austin,TX,78712.

Do not include any spaces in your submission. 
The submission is also case sensitive, and works with or without utflag{}.

By mzone (@mzone on discord)

Hints :

Follow the storyline.
All in scope accounts follow the same naming convention.
Once you've reached a centralized location any sites you need can be reached in at most
3 clicks.

Start : 
https://discord.gg/re9ez8ey

Value : 781 points
```

As Osint 1 redirects us to the discord of Cole Minerton, we should read the conversation. We can understand that Bradley Hyderman, Ross and Cole are friends. At the end of the conversation, we can read that they planned to see each other at Telluride in the Colorado.

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled.png)

But if we come back a little higher in the conversation we can understand that the 1 march 2024, Cole has 7 hours drive before arriving in Telluride. 

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%201.png)

With these informations we can already have an approximative area where Cole Minerton can leave :

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%202.png)

I precise the date because if we take a look at his social networks, we can see that the 1 March 2024, he posted that on mastodon: 

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%203.png)

We can guess that he’s at the closest gas station to him.

We’ll try to find where this picture has been taken.

On the picture we can see on the gas pump that there is 2 logos : Bradley 

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%204.png)

And Sav-o-mat :

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%205.png)

There also is a sign :”Cimarron” :

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%206.png)

So let’s google all of those elements !

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%207.png)

It seems like the same pumps with the two stickers no ?

So let’s watch the source :

![Untitled](Osint%202%208dbe96e0dc6c4d68b44a768eabfecd3c/Untitled%208.png)

Now we know the city and the state (Raton NM) so we can guess that Cimarron is the name of the avenue so let’s go to google map : 

[https://www.google.fr/maps/@36.8950397,-104.4409614,3a,75y,110.72h,83.84t/data=!3m6!1e1!3m4!1sA9IingjjWpBya8eew8ea5g!2e0!7i13312!8i6656?entry=ttu](https://www.google.fr/maps/@36.8950397,-104.4409614,3a,75y,110.72h,83.84t/data=!3m6!1e1!3m4!1sA9IingjjWpBya8eew8ea5g!2e0!7i13312!8i6656?entry=ttu)

We get the same gas pumps, the same stop and Cimarron signs.

### Flag : utflag{Raton,NM,87740}



# Osint 3<a name="osint3"></a>

## Description of the challenge :

```
Can you find the person's IP address? Flag format is XXX.XXX.XXX.XXX

By mzone (@mzone on discord)

Hint :

If you wound up on another (unrelated) discord server,
then one of the sites you visited is too new.

Value : 890 points

```

As we already used the youtube channel, the mastodon and the twitter of Cole Minerton, the only social network that we didn’t use is Reddit :

[](https://old.reddit.com/user/coleminerton)

As we can read in the URL name, the site is the old reddit of Cole, we can read a post named : “It sucks having a new account” and an other post named :”New mod of r/tinyislandsurvival”

So let’s watch the **old** [r/tinyislandsurvival](https://old.reddit.com/r/tinyislandsurvival/) subreddit ! 

There is nothing really important except we can go to the [Wiki Tiny Island](https://tiny-island-survival.fandom.com/wiki/Tiny_Island_Survival_Wiki)

On this site we can go to the history and we can find the IP adress of Cole :

![Untitled](Osint%203%20a63b0c49b39c4230a8bf1a00d82dc018/Untitled.png)

Special mention : 

To understand the hint we have to go on the “recent” [r/tinyislandsurvival](https://www.reddit.com/r/tinyislandsurvival/) and in the description of the subreddit we have a Discord server : [https://discord.gg/HtfmrHmKys](https://discord.gg/HtfmrHmKys)

But if we read the hint, we understand that’s it’s in the description of the subreddit but in the old reddit.

### Flag : 181.41.206.31
