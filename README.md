# Project 2 - *Simple Tweet*

**Simple Tweet** is an android app that allows a user to view their Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **10** hours spent in total, 4 hours on the second check-in of the project

## User Stories

The following **required** functionality is completed:

- [x] User can **compose and post a new tweet**
    - [x] User can click a “Compose” icon in the Action Bar on the top right
    - [x] User can then enter a new tweet and post this to twitter
    - [x] User is taken back to home timeline with **new tweet visible** in timeline
    - [x] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
    - [x] User can **see a counter with total number of characters left for tweet** on compose tweet page

The following **optional** features are implemented:

- [ ] User is using **"Twitter branded" colors and styles**
- [ ] User can click links in tweets launch the web browser 
- [ ] User can **select "reply" from detail view to respond to a tweet**
- [ ] The "Compose" action is moved to a FloatingActionButton instead of on the AppBar
- [ ] Compose tweet functionality is build using modal overlay
- [x] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [ ] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
- [ ] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft. If saved, the draft should then be **persisted to disk** and can later be resumed from the compose view.
- [ ] Enable your app to receive implicit intents from other apps. When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet. 

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://recordit.co/0TKSw7kSA8.gif' title='Video Walkthrough of Composing a Tweet' width='' alt='Video Walkthrough of Composing a Tweet' />

Here is a gif showing the counter turning red when you go over the tweet character limit:

<img src='https://recordit.co/UuJqSKqUUj.gif' title='Video Walkthrough of Character Limit' width='' alt='Video Walkthrough of Character Limit' />

GIFs created with [Recordit](https://www.recordit.co).

## Notes

Getting the tweet character counter to work with my app posed a challenge, as it wasn't finding the correct libraries, but after some research I was ultimately able to find a way that worked! 

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Danielle Rolon]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


# Project 2 - *Simple Tweet*

**Simple Tweet** is an android app that allows a user to view their Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **6** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can **sign in to Twitter** using OAuth login
- [x]	User can **view tweets from their home timeline**
- [x] User is displayed the username, name, and body for each tweet
- [ ] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [x] User can refresh tweets timeline by pulling down to refresh

The following **optional** features are implemented:

- [x] User can view more tweets as they scroll with infinite pagination
- [ ] Improve the user interface and theme the app to feel "twitter branded"
- [ ] Links in tweets are clickable and will launch the web browser
- [ ] User can tap a tweet to display a "detailed" view of that tweet
- [ ] User can see embedded image media within the tweet detail view
- [ ] User can watch embedded video within the tweet
- [ ] User can open the twitter app offline and see last loaded tweets
- [ ] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.

## Video Walkthrough

Here's a walkthrough of all implemented user stories:

<img src='https://recordit.co/lVFdXWchT4.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Here are two extra walkthroughs of implemented user stories, the first showing required stories, and the second showcasing infinite pagination!

<img src='https://recordit.co/SaNDleUczj.gif' title='Video Walkthrough Requirements' width='' alt='Video Walkthrough Requirements' />

<img src='https://recordit.co/RMwqH8lQGj.gif' title='Video Walkthrough Extras' width='' alt='Video Walkthrough Extras' />

GIFs created with [Recordit](https://www.recordit.co).

## Notes

I'm still in the process of implementing the relative timestamps for tweets. I was impressed by how quickly the infinite pagination feature loads more tweets, I was expecting more of a lag and was pleasantly surprised!

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Danielle Rolon]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.