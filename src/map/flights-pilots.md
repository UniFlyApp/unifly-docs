# Flights, pilots & badges

## The flight panel

Tap an aircraft to open its flight panel. The header has the callsign, aircraft and route. Underneath:

- **Flight details:** altitude, vertical speed, ground speed and heading (with the aircraft in a compass ring), the
  flight's stage, time to go and ETA. On the ground it says exactly where the aircraft is: on stand 501, pushing back,
  taxiing out, holding short of 27L, lined up, on the take-off or landing roll, crossing or backtracking a runway, or
  taxiing in.
- **Arrival:** distance and time to go, the **top of descent** ("TOD in 42 nm · about 7 min"), and whether it'll land
  in daylight, at dusk or dawn, or after dark. Flights planned in SimBrief also show whether they're on time against
  the plan ("Arriving 12m late · due 14:35"). Within 15 minutes is on time.
- **Altitude profile:** the flight so far and the rest of its route, with the ground drawn underneath, the highest
  ground on the way, and a warning if high ground ahead is above (or close to) the aircraft. Top of climb and top of
  descent are marked, here and on the route on the map.
- **Flight timeline:** everything that's happened so far: pushback, taxi, take-off, step climbs, cruise level,
  holds, go-arounds, the landing and taxi in.
- **Filed route:** the SimBrief route, drawn on the map. With a route filed, distance and time to go follow the route
  (arrival and all), so they match your sim's GPS closely.
- **Pilot strip:** the pilot's average landing, flights, hours and badges, and **View profile** for their pilot page.

Each section folds to one line with a short summary, and the map remembers which ones you keep open. Other buttons:

- **Route page ›** for everything about the route (see below).
- **Fly this** opens SimBrief with the airports, aircraft and route filled in.
- **★ Follow / Watch** for alerts when the pilot takes off and lands.
- **🚩 Report this flight** if something looks wrong. It goes to the UniFly Team.
- **🏔️** for the [3D view](basics.md#the-3d-view-of-a-flight).

Flights with a virtual airline's callsign show the airline's name, with a link to its page. Flights in a group flight,
flight party or event have a chip listing who's flying with them. Tapping it zooms the map to all of them.

### What the map works out for you

UniFly records each flight automatically. As well as take-offs and landings, the map spots:

- **Go-arounds and missed approaches.** A go-around needs a real approach, lined up with a runway. Going round from a
  straight-in approach near decision height is a *missed approach*. Low passes and touch-and-goes aren't counted.
- **Holding patterns, step climbs and cruise level.**
- **Rejected take-offs.** A take-off run stopped after passing 60 kts is noted, and isn't counted as a take-off.
- **Circuits and special missions.** A flight that lands back where it took off without going more than 25 nm away is
  *circuits* (circuits flown and time in the circuit instead of a time to go). One that goes further out first is a
  *special mission*, and it shows *RTB* on the way home. If a special mission has a filed route, its waypoints become
  objectives, ticked off as you pass within 2 nm.
- **Sim rate (time acceleration).** Shown as "×4" on the label. Hours always count real time, and sped-up flights don't
  count towards the long-flight badges or landing leaderboards.
- **Pauses.** Paused time doesn't count as flying time.
- **Teleports and slewing.** UniFly's teleport, or moving the aircraft in slew mode, is drawn as a dotted line. The jump
  isn't counted as distance flown, and no take-off or landing is logged from it.
- **Joining in the air, reconnecting and server switches.** Connect mid-flight and the flight is logged from there.
  Drop off and come back (even under a different callsign, or on the other UniFly server) and it's the same flight.
- **Back to the menus.** If you return to the sim's menus and aren't flying again within 5 minutes, the flight ends
  there as incomplete.
- **Departure from somewhere else.** Take off from an airport that isn't your plan's departure and the flight shows
  where you really left from.
- **Made-up aircraft types.** Types typed in by hand are matched where it's clear (*737-800* → B738, *H135* → EC35).
  If yours isn't recognised, your account lists it and you can say what you were really flying.

## Landings

Every landing gets a rate and a grade, shown on the aircraft's label for a minute after touchdown. The logbook keeps:

- **Landing scorecard:** where the wheels touched the runway (distance down it, touchdown zone, distance from the
  centreline).
- **Landing replay:** the last 1,000 ft of the approach as a chart.
- **Wind:** the runway, the wind and the crosswind at the time.
- **Notes** for bounces, overruns, going off the side, hard landings and the like.
- **🖼️ Landing card:** a picture of the landing to save or post in Discord.

## Pilot pages

Tap **View profile** (or a pilot in any list) to open their pilot window. At the top: their banner, picture, rank,
team or donator badge, Twitch channel if they're live, home airport, favourite aircraft and links. 🪪 makes a **pilot
card** picture of their stats to copy into Discord.

- **Overview:** their stats (average and best landing, flights, hours), *Nearly there* (badges close to being earned)
  and recent flights.
- **Landings:** the last 60 landing rates as a chart, and the best and average landing per aircraft type.
- **Badges:** see [Badges](#badges) below.
- **Logbook:** every flight they've ever flown on UniFly, one line each. Tap one for its details, landing, timeline,
  **Show on map** (with the filed route as a dotted line for the last 10 flights), Copy for Discord, the route page, a
  landing card, or 🚩 Report. Search covers every flight. 🗺 **Plot routes** draws every route they've flown in the
  last 30 days, 90 days, year or all time. Logbooks can be downloaded as CSV.
- **Goals:** this month's challenges and tours, country challenges and passport stamps.
- **Places:** the airports they've visited on a map, and their trends (hours each week for the last 26 weeks, and
  whether their landings are getting softer).
- **Hangar:** their aircraft (see [Virtual airlines & hangars](airlines-hangars.md)).

Every flight is kept in the logbook for good. Trails are kept for the last 10. Logbooks are public.

### Ranks

Pilots rank up by hours flown, from Cadet to Chief Pilot, with epaulette stripes. Tap a pilot's rank for every rank,
the hours each starts at, and how far they have to go to the next.

### Following pilots

**☆ Follow** (signed in) pins a pilot to the top of your list and gives you their take-off and landing alerts on every
device you're signed in on. Your account lists who you follow and who follows you. Without an account, ★ **Watch**
does the same in that browser.

## Badges

There are well over a hundred badges, for things like:

- **Landings:** butter landings, streaks of soft landings, crosswinds, gusts, low visibility, difficult airports.
- **Distance and time:** long flights, ocean crossings, hours flown, night flying, the all-nighter.
- **Places:** airports, countries and continents visited, famous and difficult airports, mountains, the poles,
  seaplane bases.
- **Aircraft:** types flown, gliders, helicopters, widebodies at small airports, sims flown.
- **Flying together:** formation flying, events, tours, challenges, route records, special missions, circuits.
- **Hidden badges**, which stay a secret until you earn one.
- **Mishaps 🙈:** just for fun and worth no points: *Arrival by gravity*, *Lawn dart*, *Overrun*, *Bunny hop*,
  *Desktop crash* and more.

Many come in bronze, silver and gold. Tap a badge to see how to earn it, how rare it is ("3% of pilots have this"),
who earned it first, your progress, and the flight that earned it. The **badges window** (from the 👤 menu) lists them
all by group, with *Yours* and *Still to get*.

An airport only counts towards the places badges if you land there having flown in from at least 50 nm away (circuits,
hops from next door, teleports and slewing don't count). The famous airports like Lukla and Saba count from any
distance.

## Challenges and goals

- **Monthly challenges:** four new challenges each month (new airports, a long leg, a gentle landing, so many hours…),
  with badges for finishing them.
- **Country challenges:** the continents and countries you've flown to, and how many of each country's main airports
  you've visited. You can colour the countries on the big map.
- **Tours:** see [Events, tours & community](community.md#tours).
- **Passport stamps:** see [Destination of the week](community.md#destination-of-the-week).

## Leaderboards

The 🏆 button (or **B**) opens the leaderboards. The front page has the pilot of the month and the top three of every
board, for today, this week, this month or all time. *See all ›* opens a whole board.

- **Smoothest landings** (today, the last 7 days or the latest), and landing boards for one airport or one aircraft
  type. Landings stay on the board for 7 days and in the logbook for good.
- **Most flights, most hours and most distance.**
- **Hub league:** UniFly's hubs ranked by hours flown.
- **Badge points:** 1 a badge, more for bronze, silver, gold, special flights and hidden badges. Mishaps don't count.
- **Pilot of the day, week and month:** most hours flown. The pilot of the month gets a gold badge.
- **The week so far:** a recap of the week on UniFly.

Pilots who have opted out of the records don't appear.

## Pages for routes and aircraft types

- **Route pages:** who's flying a route now, how often it's been flown and by whom, its best landings, the aircraft
  flown on it, recent flights, and **records by aircraft type** (the fastest 737 only races other 737s). Hold a record
  on a route that's been flown at least 3 times in your type for the **Record holder** badge.
- **Aircraft type pages** (`?type=A320`): who's flying it now, who flies it most, best landings, popular routes, records
  (longest, farthest, highest, softest landing) and its 3D model turning at the top.

## Your year and your week

- **UniFly Wrapped:** each pilot's year in review, from 1 December to the end of January: flights, hours, distance,
  favourite aircraft and sim, top route, best landing, badges and more, ending on a card to save or share.
- **Your week on UniFly:** a picture of your last 7 days on your account page, to save or share.
