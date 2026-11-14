---
title: Worldeck privacy policy
---

# Worldeck privacy policy

Last updated: November 14, 2026

Worldeck is a mixed-reality app for Meta Quest. You pick a place, or say or type one, and your room becomes that place. This page explains what data the app uses, why, where it goes, and how to have it deleted.

**The short version.**
- Everything Worldeck remembers stays on your headset.
- **Your voice never leaves the headset.** Speech is turned into text on the headset itself. Nothing is recorded, saved or uploaded.
- With voice turned on, Worldeck listens on the headset for its name, "Juniper", and for a few short, plain commands it understands by itself (like "make it rain"). Everything else is discarded at once.
- Only your own request can leave the headset: if you ask for a place or a thing the app doesn't know, or ask a question (said to Juniper, or typed), the text of that request may be sent to an AI service to answer with something from the app's own kit. Achievements and scores you earn go to Meta's own platform, as on any Quest app.
- Nothing is sold, and nothing is used for advertising.

## Voice, on the headset only

- **Voice is off until you turn it on.** Worldeck asks first. You can turn it off any time with **Voice** in the menu, or turn off the microphone permission in Quest's settings.
- **While voice is on, the microphone stays on.** A small blue light beside Juniper shows it. Each thing you say is turned into text by a speech recogniser that runs on the headset; the recogniser comes with the app and needs no internet.
- **The text is used only if it starts with Juniper's name** (for example "Juniper, make it rain"), if you just touched Juniper to talk, or if it is a short, plain command the app understands on the headset by itself (for example "make it rain" or "take it slow"). Plain commands said without the name are handled on the headset only and never leave it. Everything else is discarded the moment it has been read.
- **Audio is never stored.** It exists only in the headset's memory while it is being turned into text, then it is discarded. No recording is kept, written to storage or sent anywhere.
- **If you never turn voice on,** the microphone is used only while Juniper is listening after you touch it. Otherwise it isn't used at all.

## Typing

- **Type…** (on the Ask Juniper page of the menu) opens a keyboard that Worldeck draws in front of you. The letters you touch stay on the headset.
- What you type is handled exactly like something said to Juniper: on the headset when the app understands it (places it knows, changes, things it can make), and sent as text to our relay only when it doesn't.
- The suggestions shown while you type come from a list inside the app. Nothing you type is sent while you are typing.

## What stays on your headset

| Data | Why |
|---|---|
| Hand and head tracking, and your room layout from Quest's Space Setup (walls, floor, furniture boxes and their labels) | To turn your room into the world around you, fit the world's objects to your furniture, keep things within reach, and fade back to your room if you stand up |
| Your progress: worlds you have finished, souvenirs and where they stand on your table, how far you are in Mara's story, saved worlds, your daily streak, your records, your settings (caption size, sound, comfort options), whether you have seen the introduction, and whether voice is on | So the app remembers you between sessions |
| A play log: which worlds were opened and how they were asked for, how long the room took to change, how long speech took to turn into text, frame times, and error messages | To measure how well the app works and to find and fix problems. **It never contains your words or your voice,** only counts and timings |
| A random install number | To limit how many AI requests one headset can make. It is not linked to your Meta account or your headset's serial number |

## What can leave your headset: requests the app doesn't know

| Data | Sent to | Why | Kept |
|---|---|---|---|
| The text of a request said to Juniper (by name, or just after you touched Juniper to talk) or typed, that the app can't answer by itself (for example "a castle in the snow", "make me a rubber duck", a question about a thing you are holding up, like "how fast could it run?", or a question to someone who lives in a world), the current world's settings, the short names of things you have already made in this world (like "lantern"), and which kinds of furniture your room has to put things on (like "table" or "sofa", never their sizes or positions). Never audio | Our relay, then Anthropic's Claude AI | To answer with a world composed from the app's own kit (its colours, sky, plants and objects), or a thing built from simple shapes | Not by us. The relay does not store your words. Anthropic processes them under its commercial terms, which do not allow training on them |
| The random install number and a shared app key | Our relay | To stop one device sending too many requests | Request counts only, for one minute |

The relay is a small program we run on Cloudflare Workers. It keeps a count of requests and the time each took. It does not keep your words. To answer the same request faster next time, it may keep the answer (the world's settings, never your words) under a one-way code made from the request, for up to 30 days. If you only use the worlds on the map, or the relay can't be reached, nothing leaves your headset at all.

## Achievements and leaderboards (Meta)

Worldeck uses Meta's own achievements and leaderboards on Quest. When you earn one (for example bringing Mara down safely) or set a score (meteors blocked, worlds visited), the app tells Meta's platform, which keeps it on your Meta account and shows it according to your Meta privacy settings. This happens under Meta's terms and privacy policy, not ours; Worldeck sends only the achievement's name or the score, never your words, voice or room. On starting, the app also asks Meta's platform whether this copy of the app is properly installed (an entitlement check). If you are offline or signed out, none of this happens and the app works the same; your records also stay on the headset (**Records** in the menu).

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
