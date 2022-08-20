# brawl-stars-news
A repository where you can create (with a bit of work) your own brawl stars news site to go with your server!
Stole all the code from brawlstars.com using the inspect feature, then hooked everything together
***
DONT change any of the html or css or js names or the news wont work
## Support
* Currently seems to support all BS versions on Android and iOS!

# Setup
### Making The Website
Well we first have to start by making a website for the news to be hosted

* This method is 100% free with no ads or anything like it.

1. So step 1. would be to go to [replit.com](https://www.replit.com/)

2. Create an account if you havent already.

3. Create a new repl in replit

4. The repl settings should look like this:

![ReplSettings](https://github.com/brownmouse10/brawl-stars-news/blob/main/Images/Screenshot%202022-08-20%20at%2020.28.01.png)

<i>(You can name your repl whatever you want XD)</i>

5. Delete script.js and style.css

6. Paste the contents of [index.html](https://github.com/brownmouse10/brawl-stars-news/blob/main/index.html) into the index.html that you see on the top left

7. Download the latest github repo zip and upload all of its contents except index.html (because we just replaced the replit ones contents, remember?)

8. Make sure everything is working when you click "run"

9. Save your link, you'll need it later. my one was here:

![ReplLink](https://github.com/brownmouse10/brawl-stars-news/blob/main/Images/Screenshot%202022-08-20%20at%2020.42.14.png)

### Replacing the links

1. Go to locales.csv
on iOS this path is: [name].ipa/[name].app/res/csv_logic/locales.csv
on Android this path is: [name].apk/assets/csv_logic/locales.csv

2. Find the row EN (or a different language if your server prefers a different one)

3. Scroll all the way until you see the collumns with links

4. Find Laserbox Url to change the news

5. Paste the link you saved earlier

6. Repackage your apk/ipa and go into the game, you should see it has changed

There are many more links you could change; Play around with them :)
