# Finding out if a game supports Apple Silicon

If you're unsure how to find out if a game supports Apple Silicon, follow these steps below.
Note: you must be on an [Apple Silicon device](https://support.apple.com/en-gb/HT211814) for these steps to work.

1) Launch the game in question
2) Launch Activity Monitor (`⌘ + space` and search for "Activity Monitor")
3) Search for the game in Activity Monitor
![Screenshot of Activity Monitor](</docs/images/activitymonitor.png>)
4) Look for the result of the "Kind" column. If it says `Intel`, then it does not support Apple Silicon. If it says `Apple` then it is running on Apple Silicon.
