Hello,

Over the past month, I had a lot of thought about implementing a custom prefix command for Nero but there were some things that concerned me about adding them. After recieving some advice, I have decided that I will not put customisable prefix commands and I have reasons why:

__Reason 1:__

Every bot has their own prefix that makes them go to work. I would rather stick with the default prefixes I gave to Nero instead of a server using a different prefix (including the dumb '/' prefix since it will be compulsory for all bots to have them before they can be verified by Discord).

__Reason 2:__

I have not yet developed functional databases to store the custom prefixes for the server. I am trying to develop a database to keep these kind of prefixes but failed. Another thing is that if I did, it will be only be used for the currency and levelling system as I have seen how hard they are to create a functional one.

__Reason 3:__

Racial slurs and offensive words can be used as a custom prefix. That is one major thing it gave me the biggest reason why I should not implement the command. Racial slurs and offensive words can be used and I might have Nero and/or myself falsely reported for being racist and/or offensive.

These __3 reasons__ are why I will not put it and you might have questions that may put me into though. Well... let me get onto those questions you will frequently ask me:

__I remembered you said you use Replit for JSON databases and Heroku/Qovery for running your bot 24/7. Can't you do that?__

In Replit, the token is almost publicly exposed including the code and the JSON database and can be forked/modified and that will be a huge risk to take. And Replit is not always reliable to use as a VPS, even if I use the keep_alive. The bot may stop running and I mostly will get no warnings that it is offline (Discord Bots requires it to have a runtime at least 75% until testing stage). This is why I had to move Nero to Qovery as a main VPS and Heroku as a backup VPS if anything happens in Qovery where I cannot restart him and I have to change tokens to make him run on one instance only. Having him run on more than one instance will have him to send the same command more than once at the same time.

__Why can't you blacklist the words that are racial and offensive?__

There is a whole dictionary of racial slurs and offensive word you can find in the internet and it would be time consuming to blacklist all of them. There's even one word that I am scared of saying it and I can get arrested for it and it is the 'K word' (in South Africa, you can get arrested for saying it publicly). [You can read it by clicking here](https://www.nytimes.com/2016/10/28/world/africa/south-africa-hate-speech.html)

__You are allowing Nero to use the default prefixes including the dumb slash. Why?__

Discord is forcing all bot developers to have the slash commands implemented into the bots before they can be verified (deadline is at April 2022). This eliminates the custom prefixes as they can be considered useless in the bots.

I hope you will understand my reasons about why I will not include custom prefixes for Nero


Thank you

`ZaneRE`
