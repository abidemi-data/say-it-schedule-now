# Say It, Schedule It

Say your event out loud and add it to Google Calendar in a few taps. No typing needed.

Tap the mic, say something like *"Lunch with Sam next Tuesday at 1pm,"* and the app fills in the title, date, time and place. Check the card, then add it to Google Calendar.

## How to use it

1. Tap the mic and say your event.
2. Check the card that appears.
3. Tap **Add to Google Calendar** and save.

Prefer not to talk? Tap **Type instead**.

## What it can do

- Understands natural phrasing such as "dentist next Friday at 3pm for 45 minutes"
- Handles several events in one go
- Handles repeating events, such as "yoga every Monday at 7am for 8 weeks"
- Turns birthdays and anniversaries into yearly all-day events
- Lets you edit any detail before adding it
- Works on phone and computer, in light and dark mode

## Run it

It is a single file with no build step and nothing to install.

- **Locally:** open `index.html` in Chrome, Edge or Safari.
- **Online:** enable GitHub Pages (Settings, then Pages, branch `main`, folder `/ (root)`). Your app will be at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

Voice input needs a browser that supports speech recognition (Chrome, Edge or Safari) and permission to use the microphone. Microphone access requires https, which GitHub Pages provides. If you open the file directly from your computer, your browser may block the microphone; use GitHub Pages or a local server instead.

## Good to know

- The app opens Google Calendar with the event pre-filled. You tap Save there, so it does not need your Google login or any API keys.
- On the Claude-hosted version, parsing uses Claude for better understanding of unusual wording. On other hosts, including GitHub Pages, it falls back to built-in rules that cover common phrases.
- Nothing you say or type is saved by the page itself. Events only reach your calendar when you tap Save in Google Calendar.

## Coming soon

More features on iOS are on the way. [Join the iOS waitlist](https://forms.cloud.microsoft/e/n2qQd8FnBF?origin=lprLink).
