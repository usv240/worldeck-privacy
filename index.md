---
title: Worldeck privacy policy
---

# Worldeck privacy policy

Last updated: November 11, 2026

Worldeck is a mixed-reality app for Meta Quest. You pick a place, or say one, and your room becomes that place. This page explains what data the app uses, why, where it goes, and how to have it deleted.

**The short version.**
- Everything Worldeck remembers stays on your headset.
- **Your voice never leaves the headset.** Speech is turned into text on the headset itself. Nothing is recorded, saved or uploaded.
- With voice turned on, Worldeck listens on the headset for its name, "Ember". Anything not said to Ember is discarded at once.
- Only one thing can ever leave the headset: if you name a place the app doesn't know, the text of those words may be sent to an AI service to choose one of the app's worlds.
- Nothing is sold, and nothing is used for advertising.

## Voice, on the headset only

- **Voice is off until you turn it on.** Worldeck asks first. You can turn it off any time with **Voice** in the menu, or turn off the microphone permission in Quest's settings.
- **While voice is on, the microphone stays on.** A small blue light beside Ember shows it. Each thing you say is turned into text by a speech recogniser that runs on the headset; the recogniser comes with the app and needs no internet.
- **The text is used only if it starts with Ember's name** (for example "Ember, make it rain"), or if you just touched Ember to talk. Everything else is discarded the moment it has been read.
- **Audio is never stored.** It exists only in the headset's memory while it is being turned into text, then it is discarded. No recording is kept, written to storage or sent anywhere.
- **If you never turn voice on,** the microphone is used only while Ember is listening after you touch it. Otherwise it isn't used at all.

## What stays on your headset

| Data | Why |
|---|---|
| Hand and head tracking, and your room layout from Quest's Space Setup (walls, floor, furniture boxes and their labels) | To turn your room into the world around you, fit the world's objects to your furniture, keep things within reach, and fade back to your room if you stand up |
| Your progress: worlds you have finished, souvenirs and where they stand on your table, saved worlds, your daily streak, whether you have seen the introduction, and whether voice is on | So the app remembers you between sessions |
| A play log: which worlds were opened and how they were asked for, how long the room took to change, how long speech took to turn into text, frame times, and error messages | To measure how well the app works and to find and fix problems. **It never contains your words or your voice,** only counts and timings |
| A random install number | To limit how many AI requests one headset can make. It is not linked to your Meta account or your headset's serial number |

## What can leave your headset: unknown places only

| Data | Sent to | Why | Kept |
|---|---|---|---|
| The text of a place the app doesn't know (for example "a castle in the snow") and the current world's settings. Never audio | Our relay, then Anthropic's Claude AI | To choose the nearest world from the app's own set of worlds | Not by us. The relay does not store your words. Anthropic processes them under its commercial terms, which do not allow training on them |
| The random install number and a shared app key | Our relay | To stop one device sending too many requests | Request counts only, for one minute |

The relay is a small program we run on Cloudflare Workers. It keeps a count of requests and the time each took. It does not keep your words. If you only use the worlds on the map, or the relay can't be reached, nothing leaves your headset at all.

## What we never do

- We never record, store or upload your voice.
- We never sell or share your data for advertising.
- We never record or upload images of your room or anything from the headset cameras. The app does not use the camera.
- We never collect your name, email, contacts or location.
- We never use your data to identify you.

## Children

Worldeck is for teens and adults (13+).

## Deleting your data

- **On the headset:** uninstalling Worldeck deletes all its data. This includes your progress, your souvenirs, your settings and the play log.
- **Data on our side:** we keep nothing that identifies you. If you have a question or want confirmation, open an issue titled "Delete my data" at https://github.com/usv240/worldeck-privacy/issues. We'll reply within 30 days and arrange a private way to confirm. It's free.

## Changes

If the app starts using data in a new way, this page will be updated before that version is released.

## Contact

Open an issue at https://github.com/usv240/worldeck-privacy/issues.
