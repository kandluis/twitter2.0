# Project 3 - *Twitter 2.0*

**Name of your app** is a basic twitter app to read and compose tweets from the [Twitter API](https://apps.twitter.com/).

Time spent: *20* hours spent in total.

- [x] User can sign in using OAuth login flow.
- [x] User can view last 20 tweets from their home timeline.
- [x] The current signed in user will be persisted across restarts.
- [x] In the home timeline, user can view tweet with the user profile picture, username, tweet text, and timestamp.  In other words, design the custom cell with the proper Auto Layout settings.  You will also need to augment the model classes.
- [x] User can pull to refresh.
- [x] User can compose a new tweet by tapping on a compose button.
- [x] User can tap on a tweet to view it, with controls to retweet, favorite, and reply.

The following **optional** features are implemented:

- [x] When composing, you should have a countdown in the upper right for the tweet limit.
- [x] After creating a new tweet, a user should be able to view it in the timeline immediately without refetching the timeline from the network.
- [x] Retweeting and favoriting should increment the retweet and favorite count.
- [x] User should be able to unretweet and unfavorite and should decrement the retweet and favorite count.
- [x] Replies should be prefixed with the username and the reply_id should be set when posting the tweet,
- [x] User can load more tweets once they reach the bottom of the feed using infinite loading similar to the actual Twitter client.

The following **additional** features are implemented:

- [x] General UI Improvements (ie, Navigation Bar)
- [x] UI Change, including highlighting recently selectected tweet.
- [x] Images fade into place, with default placeholder image.
- [x] Launch icons for the application.
- [x] Ability to DM people (direct message)
- [x] CompsoeViewController changes depending on the type of message the user is sending.
- [x] Favorite and retweet counts are locally stored and updated (no need to refresh)
- [x] Alerts on failures from network requests and other instances.
- [x] Other minor interface and programmatic improvements.

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. Twitter API
2. Improvements other people made on the app.

## Video Walkthrough

Here's a walkthrough of implemented basic user stories:

<img src='http://i.imgur.com/MqLWAUP.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

Here's a walkthrough of user persistence.

<img src='http://i.imgur.com/tqKOUes.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

A walkthrough of some improvements and more advanced features.
<img src='http://i.imgur.com/PFsJBcX.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

And finally, a walkthrough with the orientation modified.
<img src='http://i.imgur.com/SGr52j2.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
