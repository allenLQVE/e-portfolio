---
layout: post
tags: [JavaScript, HTML, CSS, Google Oauth2, YouTube API, iFrame]
title: YouTube Randomizer
---
<img src="assets/images/screenshot-youtubeRandomizer.PNG" alt="screenshot of N-Guessing Game" style="width: 49%; display: inline;">
<img src="assets/images/screenshot-youtubeRandomizer2.PNG" alt="screenshot of N-Guessing Game" style="width: 49%; display: inline;">
<hr/>

[YouTube Randomizer](https://allenlqve.github.io/YouTube_Randomizer/)

YouTube has a terrible shuffle function for their playlist. Therefore, I wrote a player that allows users to search, merge, and play their playlists. The user needs to log in with their Google account to gain access to the application. After user login, their playlists in their account will be loaded automatically. Users can also search or merge the playlist by using the search bar.

This application is built using JavaScript only. It utilizes Google Ouath2 for users to log in to their Google account, and uses Google YouTube API to get playlists from the user's account. After the user fetches the videos in a playlist, the videos will be played using the YouTube iFrame API.


[GitHub Link](https://github.com/allenLQVE/YouTube_Randomizer)