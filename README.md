# LensOfSweetTwoof
Halloween Candy Recognizer using Microsoft Azure's Custom Vision AI!

We built this Lens of **Sweet Twoof** Bot live on Twitch for Coding Cafe during a sponsored stream by [Microsoft Azure](https://aka.ms/instafluff-social)!

## Instructions ##

### Create a Custom Vision Project ###
1. Clone this repository and then install dependencies using `npm install`
2. Go to [https://www.customvision.ai](https://www.customvision.ai) and log in, and create a new Project.
3. Upload various candy and non-candy images and create Tags (labels) for the candy photos! You should have at least 5 of each tag including the *Negative* tag for non-candy photos.
4. Click the green **Train** button above and wait for it to complete.
5. Under the **Performance** tab, click Publish and then go to the **Prediction URL** and copy the first url and Prediction Key into index.html in this project and set your Twitch channel username like ```javascript
var url=[Prediction URL];
var predictionKey=[PredictionKey];
var channel=[YourTwitchChannelName];
```
6. Run the project with `node index.js` and then open [http://localhost:1031](http://localhost:1031) in a web browser.
7. Type in your Twitch chat, `!sweettwoof [any-candy-photo-url]`. Done!

## Instafluff ##
> *Come and hang out with us at the Comfiest Corner on Twitch!*

> https://twitch.tv/instafluff

> https://twitter.com/instafluffTV

## Credits ##
Thank you too all the participants of this project!

****
