# YouTube Android Player API

The YouTube Android Player API enables you to incorporate video playback functionality into your Android applications. The API defines methods for loading and playing YouTube videos (and playlists) and for customizing and controlling the video playback experience.

Using the API, you can load or cue videos into a player view embedded in your application's UI. You can then control playback programmatically. For example, you can play, pause, or seek to a specific point in the currently loaded video.

You can also register event listeners to get callbacks for certain events, such as the player loading a video or the player state changing. Finally, the API has helper functionality to support orientation changes as well as transitions to fullscreen playback.

## Purpose

As the library might be added to the project by pasting the `jar` file into the `libs` directory, many people prefer to use `Gradle.`

This project makes adding `YouTube Android Player API` into your project in two easy steps.

## Getting started

Add to the end of repositories:

    allprojects {
        repositories {
            ...
            maven { url "https://jitpack.io" }
        }
    }

Add dependency:

    dependencies {
        compile 'com.github.tommus:youtube-android-player-api:1.2.1'
    }

## Library website

Read more about the library at Google Developers website [here](https://developers.google.com/youtube/android/player/).
