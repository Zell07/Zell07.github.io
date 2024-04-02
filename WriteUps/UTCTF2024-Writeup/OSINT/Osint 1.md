# Osint 1

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