# Streaming with UniFly

## Stream overlays

UniFly's stream overlays put your live flight on your stream in OBS (or any streaming app with Browser sources). Open
the overlay maker from 🎥 *Stream overlays* in the 👤 menu or Preferences → About. Every overlay updates live from the
map, so there's nothing to install.

### The pieces

| Piece | Shows |
|---|---|
| **Flight strip** | Callsign, aircraft, route with a progress bar, altitude, speed, climb or descent, heading, phase, time to go, ETA, top of descent and more |
| **Landing pop-up** | Your landing rate and grade, runway, touchdown point, crosswind and any new badges |
| **Mini-map** | A map following your aircraft, with optional zoom that follows your altitude and nearby UniFly pilots |
| **Pilot card** | Your rank, hours, flights, landings and badges |
| **Route card** | How often your route's been flown, its record in your aircraft and whether you're on course to beat it |
| **Stream alerts** | Pop-ups for a take-off, a badge earned, a new best landing, milestones and pilot of the week or month |
| **Guess leaderboard** | Your chat's best landing guessers (see UniFly Dispatch below) |

### Making it yours

- **Styles:** the instrument bar (the default), labels before values, or compact. Starter looks (Classic dark, Clean
  light, Neon, Airline, See-through) give you a quick start.
- **Canvas:** pick your OBS canvas (720p, 1080p, 2K, 4K or your own) and every piece is sized for it. The maker tells
  you what size to make the Browser source.
- **Layout:** drag the boxes into your own order, or use the free layout to place every item anywhere on the banner and
  size each one. Pick what each piece shows from tick-box lists, with short or full labels (ALT or Altitude).
- **Look:** your own fonts, colours, corners, padding, borders, banner background (a colour, a gradient or your own
  picture) and logo. The progress bar can sit along the top, bottom or between the airports, with a plane riding on it.
- **Network box:** UniFly, VATSIM, IVAO, PilotEdge, Offline, or your own text.
- **Your own CSS:** each piece has its own CSS box (up to 20,000 characters), with a list of class names to style.
- **Sharing looks:** export your look as a code or file for another streamer, and import theirs. CSS that comes with
  someone else's look is held back until you've checked it.
- **Sample data:** tick *Sample data in the links too* to set your scenes up with a made-up flight when you're not
  flying. Untick it to go live.

The preview sits beside the settings while you work, against a scene, dark, light or transparent background.

### Saving overlays

Signed in, **Save to my account** gives each overlay a link that never changes. From then on every change in the
overlay maker shows in OBS within a few seconds, with no need to copy a new link. Saved overlays always show your own
pilot, even after a nickname change, so nobody else can pose as you. If a link gets out, **Reset link** replaces it.

Without an account you can still copy a link. Paste any overlay link back into the maker to load and change it.

Overlays look after themselves. They update to the newest version of the overlays when it won't interrupt anything,
and if you drop off UniFly mid-flight (a client update, a crash), they keep your last details marked *Reconnecting…*
for up to 2 minutes.

### Building your own

`https://unifly.gg/map/overlay-data.php?pilot=YourName` gives the same live data as JSON, if you'd rather build your own
overlay page.

## Live on Twitch

Add your Twitch channel on your account page and verify it (sign in to Twitch as that channel). While you're live and
flying:

- You're shown in **red** on the map, with a **● LIVE** pill and your viewer count in the pilot list and flight panel.
- Viewers can find streamers with the ● LIVE filter.
- If others are flying along with you (an event or group flight), you're drawn bigger, with "+3 flying along".

The **Streaming** tab on your account page has a checklist: link your pilot, verify your Twitch, save an overlay,
switch on UniFly Dispatch and make it a moderator.

## UniFly Dispatch, the Twitch chat bot

UniFlyDispatch is our bot for your Twitch chat. Switch it on from your account page once your channel is verified.
It only goes to verified channels, so nobody can send it into someone else's chat.

> **Make it a moderator:** type `/mod UniFlyDispatch` in your chat. Twitch blocks or holds back bots that aren't
> moderators in followers-only, subscribers-only or emote-only chat, slow mode and AutoMod. Your account page shows ✅
> once it's a moderator, or what's stopping it.

### Chat commands

| Command | Answers |
|---|---|
| `!flight` | Your flight right now |
| `!route` | Your route |
| `!aircraft` | What you're flying |
| `!landing` | Your last landing |
| `!pilot` | Your pilot stats |
| `!badges` | Your badges |
| `!uf` | About UniFly |
| `!top` | The chat's best landing guessers |

Your moderators can pause the bot with `!uf off`.

### Landing guesses

When you're on approach (descending, below about 6,000 ft and within 25 nm of your destination), the bot asks your
chat to guess your landing rate with `!guess 150`. Guesses close at 500 ft. At touchdown it names the closest guess:
3 points, or 5 if it's spot on, and 1 point for anyone within 50 fpm. A go-around calls the round off. Landing guesses
are on by default and can be switched off on your account page. Put the guess leaderboard overlay on your stream to
show the standings.

### Flight announcements

Off unless you switch them on. The bot tells your chat how the flight's going: take-off and route, reaching cruise,
halfway, 30 minutes to go, starting the descent, the landing, go-arounds and a change of destination.
