# ChatterboxTranslatorExtension
We built this ChatterboxTranslator as a Twitch Extension live on Twitch!

This code requires the Twitch developer-rig to run correctly as an extension.
The regular ChatterboxTranslator is available at [https://github.com/instafluff/ChatterboxTranslator](https://github.com/instafluff/ChatterboxTranslator)

## Instafluff ##
> *Come and hang out with us at the Comfiest Corner on Twitch!*

> https://twitch.tv/instafluff

> https://twitter.com/instafluffTV

## Credits ##
Thank you to all the participants of this project!

**ClumsyWolfy, Instafluff, foxotic, MacabreMan2, Instafriend, That_MS_Gamer, Mikeystea, QeraiX, SimmeringSoupPot, trufflette, damien506, BountyHunterLani, Meggerz_alot, kingswerv, Stay_Hydrated_Bot, Mortgar, Rosuav, AntiViGames, rosedoodle, ItsNaomiArt, Neo_TA, hentaimilklord, GeoRevilo, mrbinary001, sethorizer, blackdawn1980, Saxfire, Amarogine, Thedudeskee, SparkzAlot, iAcerj, BillNash, YouMakeMeMoist, NinjaFalcon_2, VioletOsK, BaristaJosh, sparky_pugwash, nightsilas, Poolpourri, jellydance, twitchy_mctwitcher, Grognardian, MalForTheWin, malfunct, mr_grey, Lord_of_Conquest, neniltheelf, YOgorockBowlerffxi11Yo, lizardqueen, Polarami, kaisuke, DevMerlin, Liayda, HeyOhKei**

## Instructions ##

1. Install NodeJS - [https://nodejs.org/en/](https://nodejs.org/en/)
2. Open the directory in a Command Prompt/Terminal
3. Install Dependencies: `npm install`
4. Get a Twitch Chat OAuth Password Token - [http://twitchapps.com/tmi/](http://twitchapps.com/tmi/)
4. Create a file named `.env` that looks like this:
```javascript
PORT=8000
TWITCHUSER=[YOUR-USERNAME-HERE]
OAUTH=[YOUR-OAUTH-PASS HERE] # e.g. OAUTH=oauth:kjh12bn1hsj78445234
```
5. Run Server: `npm start`
6. View the webpage from your web browser! [http://localhost:8000](http://localhost:8000)
