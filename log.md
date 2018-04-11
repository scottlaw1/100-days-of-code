# 100 Days Of Code - Log

### Day 1: January 2, 2018

**Thoughts**: Both before and after being laid off last summer, I spent quite a bit of time on sites like [HackerRank](http://www.hackerrank.com) and [Udemy](http://www.udemy.com) ramping up on new technology and knocking the rust off of coding skills after 2 1/2 years of pure management.  In my new role I need to ramp up Angular and Node.js, and I intend to use 100 Days of Code to help keep me consistent.

**Today's Progress**: Completed parts 15, 16, and 17 of The Complete Node.js Developer Course on Udemy.  My Notes app saves notes to a file, reads them back from a file, and prevents notes from having duplicated titles.  I also updated the getAll function to call fetchNotes.  Once I get further along in the course we'll see if my implementation matches the instructor's or note.

**Tomorrow's Plan**:  Spend at least an hour implementing solutions to HackerRank's 30 Days of Code, beginning with Day 20 (the previous 19 days were done sporadically last year)

### Day 2: January 3, 2018
**Today's Progress**: Completed Day 20 (sorting with bubble sort) and Day 21 (generics) with C# solutions.  Day 20 took awhile, since I probably haven't written a bubble sort since undergrad.  Also added "remove note" capability to my Notes app.

### Day 3: January 4, 2018
**Today's Progress**: Added "read note" capability to my Notes app.  I also figured out how to upgrade the version of node I've been running and got rid of my Anaconda install (brew doctor complained about its config scripts and I haven't really used Anaconda, so no need to keep it).

### Day 4: January 5, 2018
**Today's Progress**: Unfortunately I didn't make a full hour of progress today.  I made a tiny bit of progress with the app you build as part of the [Angular Fundamentals](https://app.pluralsight.com/library/courses/angular-fundamentals/table-of-contents) course (from Pluralsight) when I wasn't conducting testing of some development work I did for my day job.  I also refrain from work and work-related activities during Sabbath hours, so it will be tomorrow evening before I get back to it.

### January 6, 2018
Missed the full day yesterday, but for a life reason (aunt's 70th birthday party).  Back at it tomorrow.

### Day 5: January 7, 2018
**Today's Progress**: Learned about node debugging tools (both command-line and in Chrome).  Also completed the basic implementation of the [notes application](https://github.com/scottlaw1/notes-node), including required arguments. 

### Day 6: January 8, 2018
**Today's Progress**: Started learning about async programming in node along with a new app for getting weather information.  In addition to using the [request package](https://www.npmjs.com/package/request), I installed the [JSONView](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en) plugin for Chrome. 

### Day 7: January 9, 2018
**Today's Progress**: More progress on Angular Fundamentals, including finishing the course's exploration of templating in Angular.

### Day 8: January 10, 2018
**Today's Progress**: Today I got through the point in the Angular Fundamentals course of creating a couple of reusable Angular services.  One service factored the events out of the component they were hard-coded into in a separate service.  The second service simply wrapped [Toastr](https://www.npmjs.com/package/toastr).

### Day 9: January 11, 2018
**Today's Progress**: Started a new section of Angular Fundamentals that covers routing.  I got far enough that clicking on the events in the site we build as part of the course display an event details page (via RouterLink binding).  I also added a link to the navbar that takes you back to main events page.

### Day 10: January 12, 2018
**Today's Progress**: Continued learning about routing up to the point of guarding aginst route activation (by invalid routes).

### January 13-15, 2018 
Missed extra time due to my own birthday (#44).  Day 11 starts tomorrow.

### Day 11: January 16, 2018
**Today's Progress**: Spent about 90 minutes getting further into async programming with node.  The weather app doesn't retrieve weather for a given address just yet, but it does have error handling along with the ability to accept addresses from the command-line.

### Day 12: January 17, 2018
**Today's Progress**: Today was a break from hands-on Angular and Node learning to read about peer code review.  I read part of an old copy of [Best Kept Secrets of Peer Code Review](https://smartbear.com/SmartBear/media/pdfs/best-kept-secrets-of-peer-code-review.pdf) I got from the very first Stack Overflow Dev Days once upon a time.  There's a ton of good information in here.  We'll see if I can convince my team at work to adapt our code review process to apply some of this.

### Day 13: January 18, 2018
**Today's Progress**: More progress on Angular Fundamentals, specifically route de-activation.  I was also able to convince my team to try reading code in advance of code review.  We'll find out tomorrow if makes a meaningful impact on the length of our review meeting.

### Day 14: January 19, 2018
**Today's (Lack of) Progress**: The code review meeting did proceed much more quickly today thanks to reading code in advance.  Sadly, no progress on the code front due to feeling sick.

### Day 14, Take 2: January 24, 2018
**Today's Progress**: Far too long a layoff, but the sick mentioned in my previous entry is a huge culprit.  I finally succumbed to whatever colds, sneezing, sniffling, etc that my twins have been trying to give me all winter.  In any case, I finally spent more time on Angular Fundamentals today, specifically pre-loading data, lazy loading of feature modules and active link styling.

### Day 15: January 29, 2018
**Today's Progress**: Made a long-overdue return to The Complete Node.js Developer Course on Udemy.  Since I spent 2 1/2 hours instead of just 1, my weather application now takes an address at the command line and returns the temperature and apparent temperature for the latitude and longitude of that address using callback chaining.  The actual weather data comes from the [Dark Sky API](https://darksky.net/dev), which is free to register for.

### Day 16: January 30, 2018
**Today's Progress**: Today I spent more time on Angular Fundamentals while one of the testing environments I use for my day job was out of commission.  I learned about "barrels" (for organizing exports) and got started on Angular forms and validation.

### Day 17: January 31, 2018
**Today's Progress**: More Node.js work tonight, this time on promises.  Comparing and contrasting callbacks and promises for handling asynchronous calls was quite interesting.

### Day 18: February 1, 2018
**Today's Progress**: Took a break from Angular and Node to pick up where I left off with another Udemy course covering Java, Spring, and Hibernate.  I experimented with definition and usage of init-method and destroy-method in Spring configuration.  The rationale for this is the possibility that my team at work may be inheriting ownership of an API written in Java.

### Day 19: February 5, 2018
**Today's Progress**: Too long a layoff since the last update, but no excuses.  To build my comfort level with all things JavaScript, I followed a [tutorial](https://hackernoon.com/build-a-cryptocurrency-price-tracker-in-5-minutes-d66c3d37ad71) I came across to build a cryptocurrency price tracker.  I modified the publisher.html to include most of the JavaScript in the header (instead of all in-line in a script block like the original author).  The implementation required registering for another API called [PubNub](https://www.pubnub.com/).  I should put my implementation (sans API keys) into GitHub and perhaps expand it to cover more cryptocurrencies.

### Day 20: March 1, 2018
**Today's Progress**: This is day 1 of an in-house machine learning competition, so a co-worker and I spent a full day poking around with Python trying to get a non-trivial amount of data into shape to train a model.

### Day 21: March 2, 2018
**Today's Progress**: This was day 2 of a competition that was originally scheduled to last 2 days, but AWS problems and a wind storm conspired to knock out enough cloud infrastructure (in addition to closing our corporate HQ) to limit our forward progress to "data shaping".

### Day 22: March 4, 2018
**Today's Progress**: With the competition deadline extended to March 9, I spent a couple hours today making up for lost time reading and taking notes on machine learning materials I found online.

### Day 23: March 5, 2018
**Today's Progress**: My co-worker found some good machine learning content over the weekend which I've been adding to a [playlist](https://www.youtube.com/playlist?list=PLQn6WJYuh4tuxI-23AfqlfDavOvVmjA6m) as I proceed.  I ended up writing enough code as I watched these that it seemed like a good idea to save it in a [github repo](https://github.com/scottlaw1/machine-learning).

### Day 24: March 6, 2018
**Today's Progress**: Wrote some data exploration scripts in Python for a 8GB dataset.

### Day 25: March 7, 2018
**Today's Progress**: Wrote a regression pipeline on a subset of data and computed the mean squared error.

### Day 26: March 9, 2018
**Today's Progress**: Wrote a Jupyter notebook summarizing the data exploration and feature engineering from earlier in the week.

### Day 27: March 21, 2018
**Today's Progress**: After the end of the machine learning competition (and a break from coding outside of work), jumped back into the weather app from January and used the Axios library instead of wrapping calls to a non-promise supporting library in promises.

### Day 28: March 22, 2018
**Today's Progress**: Researched and compiled the first draft of an abbreviated history of C#.  The impetus for this was a conversation with a VP at work who was curious about the work my team does in .NET because he never worked on that tech stack when he was an individual contributor on development teams.  I was pleasantly surprised to discover as I researched that my recollections of nearly 20 years ago regarding the legal battle between Microsoft and Sun over Java and J++ were pretty much on-target.

### Day 29: March 26, 2018
**Today's Progress**: More Node tonight.  This time we implemented a webserver in Node using the Express webserver framework.  I'll keep an ongoing repo of that project here [here](https://github.com/scottlaw1/node-web-server).

### Day 30: April 8, 2018
**Today's Progress**: Tonight I did some templating with Handlebars.

## Day 31: April 10, 2018
**Today's Lack of Progress**: I heard about the React-Python dev stack at work today, and thought I'd find an example and try to get it working.  [This example](https://codeburst.io/creating-a-full-stack-web-application-with-python-npm-webpack-and-react-8925800503d9) did not work as advertised because I never managed to get 'npm run watch' to work.  I kept getting an error where npm couldn't find the webpack.config.js module.  Tomorrow I will just try a webpack demo to see if I can figure out where I went wrong.
