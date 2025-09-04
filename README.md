# MemeStreamApp (PROG7314 ICE Task one )

Android app (Kotlin, min SDK 24) scaffolded for MemeStream.

## What’s in this repo
- **Navigation** with `NavHostFragment`
- **FeedFragment** + placeholder UI (“Feed goes here”)
- **ViewBinding** enabled (Compose disabled)
- Dependencies added: Retrofit, Moshi, Glide, Maps, Location, Room, Navigation, AppCompat

## How to run
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Run on an emulator or device.

> Known issue: app currently crashes on launch — will fix after grabbing Logcat error (next step in progress).

## Backend (separate project)
A Node/Express/MongoDB API has been built and tested locally:
- `POST /memes` (create)
- `GET /memes` (list)
- `GET /memes?userId=...` (filter)

Will be added as a separate repo / link in final submission.
