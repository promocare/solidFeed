![solidFeed logo](https://github.com/promocare/solidFeed/blob/master/logo.png)
# solidFeed
A better social media platform based on Solid

## Introduction
The goal of this documents is to explain the guidelines for a new Solid based social network.
Please feel free to contribute, add suggestion or point out mistakes.
This is not a technical document and does not contain code. Please don't use brand names in this document.

## Advantages of Solid

The goal of Solid is to provide a decentralized system for storage of personal data. The storage can be provided by either a hosting company, inrupt or a **self hosted** server. The data will be always stored and manaed by the user independently of the applications using it.

You can learn more about Solid [here](https://github.com/solid/solid) and [here](https://solid.inrupt.com/)

## An UI/UX to prevent addiction and misinformation
The biggest UI/UX flaw (_read feature_) of current social media platforms is that users are encouraged to spend as much as possible time on the platform so that the companies can sell ads and promoted material. 

This creates addiction and suffering for a lot of people as proved by various studies. _(links will be added soon)_

Our goal is to create a easy to understand and fast interface that doesn't allow the user to spend an excessive amount of time on the platform but can be used to keep in touch with people, creators and brands in a healthy way.
We could use reminders (eg. Nintendo games) to alert that the user, and other UI features.

## A better tool for creators and brands
A big problem in current social media platforms for brands and creators is to be able reach all their followers without having to pay for a post or event promotion. 
We believe that all the followers that a creator or brand earns should get all posts chronologically.

## No recommendations 
We believe that recommendations are a big part of the problems that cause people to be narrow minded and more radical on the internet (and real life) today.

Removing recommendations will force the user to search content that they would like to follow instead of being "spoon fed" other accounts or sources of information. The recommendation system can also be hijacked to spread information that is not factual and is designed to spread hate or further propaganda. This will also remove the tentation to collect user preferences and informations that can be sold to third parties.

## Login & Profile
The app will use WebID to authenticate the users using existing accounts on solid.community or other providers.
The profile data will be gathered by the POD profile with the possibility to be changed manually.
There are no pages or other types of user, a company would have to create a separate account.

## Posting
The user will be able to post various formats of data to their on feed, including:
- Text
- Images 
- Links
- Video
- Surveys

And a combinations of those (text+image, text+image+link, text+link, so on..)

## Following & interaction
A user can follow any other account that can be searched inside the app and the posts will apper in the user's feed.
A user can also comment on a post but not "like" it (or "Heart" it) this is to minimize addictive behaviour on the receiving end.

## Privacy
There will be various settings for privacy for example:
- control who can comment (everybody, only people that you follow, so on..)
- be not searchable for a certain amount of time or forever
- block certain users
- if non followers can see posts
- who can follow

It will not be shown on the public profile data how many followers a profile has but that number can be visible by the owner of the profile. No one will be able to see who is following them, this is to protect the privacy of the users and to prevent targetization of posts and provides anonymity for people in delicate situations.

**By default the maximum amount of privacy will be enabled**

## Technologies
We should use a reactive JS framework (eg. Vue.js) along with the HTML/JS that solid requires.
we could also create a HTML "lite" versions for devices with limited computing resources, limited connectivity or legacy OSs and browsers.

Mobile apps for iOS and Androis could be created in the future.

## Things to consider
- How to properly do notifications (redis?)
- How to optimize content using PODs (video, images, links rendering)
- Create an original UI/UX

Thank you for reading,
feel free to contact me.

This project belongs to everyone.
Thank you to Inrupt and the prople at Solid for inspiring me.
