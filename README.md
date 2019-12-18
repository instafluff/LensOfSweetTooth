# LensOfSweetTwoof
Halloween Candy Recognizer using Microsoft Azure's Custom Vision AI!

We built this Lens of **Sweet Twoof** Bot live on Twitch for Coding Cafe during a sponsored stream by [Microsoft Azure](https://aka.ms/instafluff-social)!

## Instructions ##

### Create a Custom Vision Project ###
1. Clone this repository and then install dependencies using `npm install`
2. Go to [https://www.customvision.ai](https://www.customvision.ai) and log in, and create a new Project.
3. Upload various candy and non-candy images and create Tags (labels) for the candy photos! You should have at least 5 of each tag including the *Negative* tag for non-candy photos.
4. Click the green **Train** button above and wait for it to complete.
5. Under the **Performance** tab, click Publish and then go to the **Prediction URL** and copy the first url and Prediction Key into index.html in this project and set your Twitch channel username like

```javascript
var url=[Prediction URL];
var predictionKey=[PredictionKey];
var channel=[YourTwitchChannelName];
```

6. Run the project with `node index.js` and then open [http://localhost:1031](http://localhost:1031) in a web browser.
7. Type in your Twitch chat, `!sweettwoof [any-candy-photo-url]`. Done!

## Instafluff ##
> *Like these projects? The best way to support my open-source projects is by becoming a Comfy Sponsor on GitHub!*

> https://github.com/sponsors/instafluff

> *Come and hang out with us at the Comfiest Corner on Twitch!*

> https://twitch.tv/instafluff

## Credits ##
Thank you too all the participants of this project!

**That_MS_Gamer, Instafriend, Instafluff, ChatTranslator, BillNash, Luxadin, MacabreMan, Gilokk0, opti_21, Alca, i_am_from_mars, FlavCreations, ecomath328, MaryJoStaebler, itsbobaT, simrose4u, wgd_isolde, BungalowGlow, rickyuttam, CodingGarden, glitch3dout, mynameisinfi, aronhoyer, BoxmonsterPrime, okprogamer, onemen_, yigitkurtcu, efzetz, bolomin99, Procelsior, jakepintu, ja0b_, pixelbreath, sweetvalhalla, Terminal_Bash, m1lfsarethebest089, Linol_Shadowcat, donaldwm, DutchGamer46, sparky_pugwash, Talasa, outlaw_dan, JMSWRNR, BottleStudios, Bruece, FuriousFur, MalForTheWin, AntiPixelated, TrueOlive, ShinSharkai, TheHungerService, LilyHazel, 10TenArt, Agent_Merlin, aj2017, malfunct, ummmheck, Maayainsane, eminyilmazz, jjan97, atel0s, Cloudhun, neniltheelf, rota22_, ruandersMSFT, XanderPrime, ziiggyy, DragosNox, Fleauris, MasakiOyata, AmericanVikingJohn, Julll, ph1lt0r_and_lala, CrimsonKnightZero, LANiD, Bloom_jiminy, Liraquin, Odysseus_Xeno, RokvirStormshield, VapidF, where_is_laughingman, csharpfritz, drewdruniliskindagay, s7e_deathconnor, mcgeorgeofthejungle, LuckyNoS7evin, CJnxd**
