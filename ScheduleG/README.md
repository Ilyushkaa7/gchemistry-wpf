# ScheduleG

ScheduleG is a simple Android app for marking work shifts in a calendar.

I made this app as my first Kotlin project and as a college project for a mobile development course. The idea came from a real need: my father works on a rotating schedule, and he needed a clean and easy way to mark day and night shifts.

## Why I Built It

My father used another shift calendar before, but it had an old interface, too many bright colors, and many features he did not need. It looked more like an Excel table than a simple mobile app.

I wanted to make something minimal:

- open the app
- tap a date
- choose a shift type
- continue the schedule automatically

The main idea was to keep only the features that are actually useful.

## Features

- Calendar view for shift planning
- Tap a date to mark it as a day shift
- Tap a date to mark it as a night shift
- Tap the same marked date again to remove the mark
- Empty dates are used as days off
- Automatic schedule extension for the next 30 days
- Clear all marked shifts button
- Data is saved locally on the phone

## Shift Types

The app uses a fixed color system:

- Green: day shift
- Blue: night shift
- Empty: day off

This keeps the interface simple and easy to understand.

## Auto Extension

The most important feature is automatic schedule extension.

The user marks the work pattern several times, and the app tries to understand the repeating schedule. For example, if the pattern is:

```text
Day / Night / Off / Off
```

the app can continue this pattern for the next 30 days.

This was the hardest part of the project, because the app needs to detect the user's schedule and apply it correctly.

## Tech Stack

- Android
- Kotlin
- XML layouts
- SharedPreferences for local data storage

## My Role

I created the idea, app structure, interface sizes, colors, logic, auto-extension algorithm, and tested the app behavior.

This project was made with help from prompts during development, but the main product idea, requirements, testing, and final decisions were mine.

## Project Status

The app is currently used as an APK on my father's phone.

There is no public demo yet, because it is a native Android application.

## What I Learned

While building this project, I learned:

- how to create a simple Android app with Kotlin
- how to design a mobile interface for a real user
- how to save user data locally with SharedPreferences
- how to work with calendar-based logic
- how to build an automatic schedule continuation feature
- how important minimalism is when the user needs a practical tool

## Future Ideas

I do not plan to add many new features right now, because the goal of the app is simplicity. Possible future improvements:

- screenshots in the README
- small UI improvements after more real use
- better testing on different Android devices
