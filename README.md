
## "CollectiveTweaks"  -  _`Crowdsource (y)our view`_    
<i>
/ 'Crowd Fixes'? - A new word? 
( "User tweaks", easier than "user scripts", but universally relevant/functional  and  a collective crowd effort) (unlike "user styles" for specific tastes). <br>
<img width="420" alt="usertweaks" src="https://user-images.githubusercontent.com/25022245/115540770-a7485500-a29e-11eb-9a98-c54a7a3823fb.png"><br>
</i>

<b> `IDEA:`   Crowd-Sourcing universal CSS improvements or annotations to refine, renew, reimagine the web.  <br> - One-fit-all. The web as collaboration / wiki  </b>

- **Mandate:** Tweaks for everybody.<br> 
- **Debate:** If we can achieve the best, then can we also make the community of volunteers grow/prosper from it? 
Or must we tolerate, if our work will be implemented by the originals, after we prove it right, without giving us credit?)

- **Scheme / "Rules of the game":**  Everybody runs every tweak out of a pool/catalogue, that is was voted up, democratically or near consensus by the community, i.e.  >80%  "Yes", while  quickly disabling a tweak could also inevitably change one's vote to "No". Collecting at least 100 votes for each, by users/volunteers & revisors/developers. ( * Wisdom Of The Crowd:  https://www.youtube.com/watch?v=iOucwX7Z1HU) (User IDs could be random, data could be public, on a central server or in a blockchain / L2 blockchain)
    - **1.** This will motivate thoughtfulness, unexpected help, wonderful creativitiy: 
        - Deleting useless things 
        - Enlarging tiny inputs & Auto-focus if they are the only input.
        - Web-street art.
        - Correcting fake news in place.
        - ...
   - **2.** There can be specific rule sets, as in Adblockers. For example one called "Brand-Me-Not" or "Logo-Hater", removing logos in the top left of websites. (Except those that >20% of users whitelist and think of as relevant content (be it for being non-profits, social or small enough, or so). While this set-example as a whole might not be wanted by more than >80% of people, so that it will be at risk of becoming optional opt-in. Yet a 2nd-level (another consensus within), will raise the value of the whole, so that it might be visible enough. While 2nd-level thresholds could be auto-adjusted to optimize the overall-acceptance of a set.)
   - **3.** Most tweaks will be per domain, yet can any be applied for a wide URL-range? ( Such as .edu? - And for everybody - "Holy-Grail"?). 
      - ("Brand-Me-Not", may be half-done with <code><code> body :nth-child(-n+5){ \*[id="logo"], img[src^="logo."], img[src*="/logo."], \*[href="#"] \*, \*[href="/"] \*, \*:not([class~=" "]).logo, [id="logo"], :is(img)[src^="logo."], :is(img)[src\*="/logo."], [href="#"] \*, [href="/"] \*, :not([class~=" "]).logo {display:none}</code></code>) 

-------------
-------------

   - In other words:
     - compare: https://github.com/letsblockit/letsblockit 
     -   Similar: UserScripts & UserStyles but pragmatic, with voting resulting in collectively running  things & little effort per person
         - [UserScripts](https://greasyfork.org) (Often require some review, same as browser extensions. ) 
         - [UserStyles.org](https://userstyles.org) (Currently mostly themes/playful. Easy adjustability tho already.) 
     - Not only for devs [css-peeper](https://chrome.google.com/webstore/detail/css-peeper/mbnbehikldjhnfehhnaidhjhoofhpehk), [user js&css](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld), [Live css,less,sass:octocat:](https://github.com/webextensions/live-css-editor) 
     - Nor "Remix the web"-niche for style-nerds [chrome.google/webstore/amino-live-css](https://chrome.google.com/webstore/detail/amino-live-css-editor/pbcpfbcibpcbfbmddogfhcijfpboeaaf)

----

###  Just some quick examples (drafts) :
<b>1.</b> The following two github standard labels can be boring / unnecessary to watch, so lets make them just a bit less visible: <br>
<img width="285" alt="github standard labels" src="https://user-images.githubusercontent.com/25022245/115553356-9eab4b00-a2ad-11eb-9c1e-e06fc2f23a93.png"><img width="295" alt="help wanted good first issue" src="https://user-images.githubusercontent.com/25022245/115553361-9f43e180-a2ad-11eb-8fb8-6a6aded8f703.png"> <br>
<i> `a[data-name^='help wanted'], a[data-name^='good first issue'] {opacity: 0.80; transform:scale(0.96);}` </i>
<br>
<img align="right" width="546" alt="google analytics too small" src="https://user-images.githubusercontent.com/25022245/115553367-9fdc7800-a2ad-11eb-8d86-9b5ac951e457.png"> 
<img align="right" width="523" alt="google analytics filter" src="https://user-images.githubusercontent.com/25022245/115553364-9f43e180-a2ad-11eb-91f2-faf7d2f63272.png"> 
<b>2.</b> The google analytics filter field is very small since ages. It also is very far on the right. 
<br><br><br> Lets make it just a little better: <i><code> .ID-filterBox { width:190px !important;  font-size: 14px !important;  height: 21px !important;} </code></i><br>
 <br><br><b>3.</b> Youtube's sidebar is very bold and contrasty, compared to actuall videos. Lets counter balance that by just 12% transparency: <i><code> #secondary {opacity:0.88} </code></i>



###  Testing methods: 
  -  uBlock Origin or https://github.com/code-charity/dark-mode/

<img width="267" alt="usertweaks" src="https://user-images.githubusercontent.com/25022245/115553355-9d7a1e00-a2ad-11eb-95a0-797a8aacb266.png">  <img width="263" alt="youtube related videos sidebar" src="https://user-images.githubusercontent.com/25022245/115606631-3e83cb80-a2e4-11eb-8ceb-9058c8115c76.png"> <img  width="268" alt="usertweaks user styles" src="https://user-images.githubusercontent.com/25022245/115553357-9eab4b00-a2ad-11eb-86b9-611129f197e0.png"> 

-----

https://www.reddit.com/r/UserTweaks/


