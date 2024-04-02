# Osint 2

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