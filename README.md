# autobahn
## automatic Hacker News front page output in terminal

### Why
I wanted to have up to date HN information, and I noticed I was opening my terminal a lot.
I used to have fortune readings in my terminal, but I figured it was better if I was able
to read HN headlines.

This was made simply in bash so as to not require many dependencies. It also requires some
tools found in *NIX including lc, tr, jq, curl, sed, awk, echo and bash.

### Installation
Add to .bashrc

Example:
```
bash ~/path/to/autobahn.sh
```

Then type `source .bashrc`

### Sample Output
```
01) ESP32/ESP8266 Wi-Fi Attacks <https://github.com/Matheus-Garbelini/esp32_esp8266_attacks>
    Discussion: <https://news.ycombinator.com/item?id=20867758> | Poster: gioscarab | Score: 261
02) Go 1.13 Release Notes <https://golang.org/doc/go1.13>
    Discussion: <https://news.ycombinator.com/item?id=20869324> | Poster: 0xmohit | Score: 118
03) Mozilla’s Manifest v3 FAQ <https://blog.mozilla.org/addons/2019/09/03/mozillas-manifest-v3-faq/>
    Discussion: <https://news.ycombinator.com/item?id=20867720> | Poster: Findus23 | Score: 101
04) Android 10 <https://www.android.com/android-10/?>
    Discussion: <https://news.ycombinator.com/item?id=20868164> | Poster: Aissen | Score: 258
05) A Gambler Who Cracked the Horse-Racing Code (2018) <https://www.bloomberg.com/news/features/2018-05-03/the-gambler-who-cracked-the-horse-racing-code>
    Discussion: <https://news.ycombinator.com/item?id=20865312> | Poster: tosh | Score: 221
06) The Eternal Mainframe <http://www.winestockwebdesign.com/Essays/Eternal_Mainframe.html>
    Discussion: <https://news.ycombinator.com/item?id=20868307> | Poster: ptx | Score: 9
07) Ask HN: Who is hiring? (September 2019)
    Discussion: <https://news.ycombinator.com/item?id=20867123> | Poster: whoishiring | Score: 184
08) China Drone Attack on Crop-Eating ‘Monster’ Shows 98% Kill Rate <https://www.bloomberg.com/news/articles/2019-09-02/china-drone-attack-on-crop-eating-monster-shows-98-kill-rate>
    Discussion: <https://news.ycombinator.com/item?id=20865823> | Poster: pseudolus | Score: 91
09) C++ is not a superset of C <https://mcla.ug/blog/cpp-is-not-a-superset-of-c.html>
    Discussion: <https://news.ycombinator.com/item?id=20869451> | Poster: lochsh | Score: 46
10) Full Body Teleportation System <https://patents.google.com/patent/US20060071122A1>
    Discussion: <https://news.ycombinator.com/item?id=20869316> | Poster: albertzeyer | Score: 16
11) A German Idea of Freedom: Nude Ping-Pong, Nude Sledding, Nude Anything <https://www.nytimes.com/2019/08/31/world/europe/germany-nudism.html>
    Discussion: <https://news.ycombinator.com/item?id=20869757> | Poster: tysone | Score: 42
12) Need a USB Cable? Build One <https://josef-adamcik.cz/electronics/need-a-usb-cable-build-on.html>
    Discussion: <https://news.ycombinator.com/item?id=20867276> | Poster: Gedxx | Score: 42
13) DeepFaceLab: A tool that utilizes ML to replace faces in videos <https://github.com/iperov/DeepFaceLab>
    Discussion: <https://news.ycombinator.com/item?id=20866202> | Poster: wawhal | Score: 257
14) Show HN: Fullstack ML – From Notebooks to Deployment <https://github.com/xadrianzetx/fullstack.ai>
    Discussion: <https://news.ycombinator.com/item?id=20865012> | Poster: xadrianzetx | Score: 131
15) Firefox 69.0 Released <https://www.mozilla.org/en-US/firefox/69.0/releasenotes/>
    Discussion: <https://news.ycombinator.com/item?id=20866084> | Poster: sulkie | Score: 372
16) Cache Attacks on CTR_DRBG <https://security.cohney.info/blackswans/>
    Discussion: <https://news.ycombinator.com/item?id=20866620> | Poster: shaananc | Score: 40
17) Show HN: Ackee – Self-hosted website analytics <https://ackee.electerious.com>
    Discussion: <https://news.ycombinator.com/item?id=20865426> | Poster: electerious | Score: 122
18) Betting the Farm on the Drought <https://longreads.com/2019/08/22/betting-the-farm-on-the-drought/>
    Discussion: <https://news.ycombinator.com/item?id=20866533> | Poster: axiomdata316 | Score: 24
19) Eros at Play <https://aeon.co/essays/how-ancient-poetry-can-revitalise-our-erotic-imaginations>
    Discussion: <https://news.ycombinator.com/item?id=20863755> | Poster: pepys | Score: 39
20) OpenBSD was right to disable hyperthreading [video] <https://www.youtube.com/watch?v=jI3YE3Jlgw8>
    Discussion: <https://news.ycombinator.com/item?id=20865492> | Poster: rodrigo975 | Score: 186
21) Googie Architecture, an Art Form Worth Saving (2014) <https://allthatsinteresting.com/googie-architecture>
    Discussion: <https://news.ycombinator.com/item?id=20862794> | Poster: tintinnabula | Score: 34
22) Timeline for Logic, λ-Calculus, and Programming Language Theory (2012) [pdf] <http://fm.csl.sri.com/SSFT15/Timeline.pages.pdf>
    Discussion: <https://news.ycombinator.com/item?id=20860888> | Poster: adamnemecek | Score: 166
23) A Town for People with Chronic Fatigue Syndrome <https://www.newyorker.com/culture/personal-history/a-town-for-people-with-chronic-fatigue>
    Discussion: <https://news.ycombinator.com/item?id=20868395> | Poster: fortran77 | Score: 7
24) Why the Amazon Basics Keyboard Is My Favorite Keyboard <https://nickjanetakis.com/blog/why-the-amazon-basics-keyboard-is-my-favorite-keyboard>
    Discussion: <https://news.ycombinator.com/item?id=20866319> | Poster: nickjj | Score: 121
25) India’s Restaurants Rebel Against Food Delivery Apps <https://www.nytimes.com/2019/08/29/technology/india-restaurants-logout-delivery-zomato.html>
    Discussion: <https://news.ycombinator.com/item?id=20864703> | Poster: ishikawa | Score: 67

Get all news at https://news.ycombinator.com/
```

### Deletion
Remove from .bashrc

### License
Copyright (c) 2019 Andrew Lee (MIT License)
