A calm, one-page focus timer set in a fictional racing team's garage coffee bar. Set your one task, click **Start focus**, and work for 30 minutes to lo-fi music and soft café sounds while the crew sits quietly. When the stint ends, the car drives into the bay and a crew member asks what you got done. Your answer goes into a scratch pad on your device. Then you get a 5-minute break.

## How to use it

1. Type your one task at the top.
2. Click **Start focus**. Music and café sound start, and there are separate volume sliders for each.
3. When the timer ends (or you click **Box now**), the car comes in. Type what you got done and click **Add to scratch pad**.
4. Take the 5-minute break, then start the next stint.

Open the **scratch pad** from the control panel to see every debrief, newest first. **Copy all** puts the whole log on your clipboard. **Clear scratch pad** permanently wipes it, after a confirmation step.

## Privacy

- Everything you type (task, debriefs, settings) is stored in your browser's `localStorage` on your device. Nothing is sent anywhere.
- The page makes no network requests: no analytics, no web fonts, no outside scripts.
- Clearing the scratch pad or your browser's site data deletes the entries. Nobody else can see them.

## Files

```
index.html     the whole app: markup, styles, and script in one file
audio/         10 lo-fi tracks, shuffled so none repeat until all have played
README.md      this file
```

## Customizing

Everything to edit is in the `CONFIG` section near the top of the script in `index.html`: session lengths, team name, crew names and backstories (hover a crew member's name in the debrief to see theirs), debrief replies, and the track list.

## Credits

- Music generated with Google's Lyria in the Gemini app.
- Code written with Claude.
- Corsa Britannia and its crew are fictional. Any resemblance to real teams or people is unintended.
