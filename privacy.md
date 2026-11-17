---
layout: default
title: Privacy policy
---

# Privacy policy

**Boxset** for Apple TV, iPhone and iPad<br>
Effective November 17, 2026

<p class="lead">The short version: Boxset collects nothing about you. There's no Boxset account, no analytics, no advertising and no tracking, and there are no Boxset servers: nothing reaches its developer. Boxset talks to Plex, to your own servers, and only if you set them up, to TMDB with your own key and to your own request server.</p>

## Plex

To sign in, Boxset shows a code you enter at plex.tv/link; Plex then gives the app a sign-in token, kept in your device's Keychain. Boxset uses it to list your Plex servers and to play from them, as any Plex app does: your server learns what you play and where you stop, so you can carry on elsewhere. With Plex Home, the same is true of the profile in use.

## Who's in the scene

The first time you pause a film or an episode, Boxset asks whether to show who's in the scene. If you say yes, it reads the paused picture **on your device**, finds the faces in it and compares them with the cast's photos from your Plex server (and from TMDB, if you added a TMDB key). No picture and no face is sent anywhere. To recognise the cast sooner next time, it keeps, in the app's caches on the device, numbers describing faces it was sure of, per show or film, and the times each person was seen in a title; never a picture. These go after 120 days unused, and Settings > Who is in the scene > Forget the faces it has kept removes them, with its log, at once. The switch in the same place turns it off.

## TMDB (optional)

If you type a TMDB key of your own in Settings, Boxset asks TMDB, with that key, for the cast of what you play and a few photos of each actor. TMDB receives those requests under your account and its own privacy policy. Without a key, Boxset never contacts TMDB.

## Your request server (optional)

If you connect your own Overseerr or Seerr server in Settings > Requests, Boxset first checks that the address answers as one, then signs in to it with your Plex sign-in token, as that server's own "Sign in with Plex" does. The server's session and its address are kept on your device. Boxset asks it what an actor has been in when you open their page, and passes on the requests you make. Its posters come from TMDB's image host, which sees your device's network address as any website does.

## Controllers on your home network (optional)

On Apple TV, a home automation system on your own network can be paired by a code on the screen, to start or pause what plays. Its key is kept in the Keychain; nothing outside your network is involved.

## iCloud

Your channels are kept in your own iCloud key-value storage so they appear on your other devices. Apple holds that under its own terms; the developer has no access.

## On your device

Your settings, downloaded films and episodes (iPhone and iPad), cached artwork and the channels' lineups stay in the app's own storage on the device. Deleting the app removes them.

## Children

Boxset is not aimed at children and collects nothing from anyone.

## Changes and contact

If this policy changes, this page changes with it, with a new date. Questions: [ayers177@gmail.com](mailto:ayers177@gmail.com).
