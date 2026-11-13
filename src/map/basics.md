# Using the map

## Getting around

Open [map.unifly.gg](https://map.unifly.gg/). Drag to move, scroll or pinch to zoom, and tap any aircraft or airport
for its details. The first few times you visit, small tips point out what the map can do. They go once you've used
the thing they point at, and you can switch them off (or bring them all back) in **Preferences → About**.

### The corner buttons

Down the bottom right:

| Button | What it does |
|---|---|
| 🧑‍✈️ Find me | Jumps to your own aircraft (shown once Me mode knows who you are) |
| 📍 Destination of the week | Opens this week's destination guide, if you've hidden its banner |
| 🏆 Leaderboards | The leaderboards window |
| 📅 Events | Upcoming events, results and tours (with a count of new events) |
| 🏢 Virtual airlines | Browse, join or start a virtual airline (alpha) |
| 🗺️ Map layers | Weather radar, clouds, wind, traffic heatmap and popular routes (a dot shows while one's on) |
| 👤 Account | Sign in, your account and pilot page, Preferences, light or dark, stream overlays |

The zoom buttons and a clock sit at the top right. The clock shows your time setting with the other one under it
(local and UTC). Click it to swap them, or right-click (press and hold on a phone) to copy the time. With an airport
open it shows that airport's local time as well.

### The pilot list and search

The pilot counter at the top left opens the list of connected pilots. Its dot shows the live feed: green when it's
live, amber when positions have stopped coming in, red when the map can't reach UniFly. The counter also says how many
pilots are connected but still in their sim's menus.

- **Tabs:** *Pilots* (everyone connected) and *Recent flights* (finished flights from the last 7 days, by day; tap one
  to draw it on the map).
- **Search:** one box for pilots, callsigns, airports (ICAO, IATA or name), aircraft types and airlines. Matching
  airports and types show as suggestions.
- **Filters:** All, Flying, Ground, ★ Watched, ● LIVE (pilots streaming on Twitch) and, while one's on, 🎟️ Event. The
  **Sim ▾** chip filters by simulator.
- **Order:** the UniFly Team first, then donators, then pilots streaming, then everyone else. You can pick another order
  (Pilot A–Z, Callsign…) and the map remembers it.
- Pilots in the sim's menus are listed under *In the menus*.

Press **/** to open the list and search.

### Aircraft on the map

- **Labels** show the callsign and altitude, with more detail if you want it (Preferences → Aircraft → Label detail).
  The aircraft you select always shows everything. Press **L** to hide or show labels.
- **Colours:** the UniFly Team are blue, donators gold, pilots live on Twitch red, everyone flying an event that's on
  now green, and your flight party teal. Group flights are purple. A virtual airline's aircraft can show in its own
  colour. Turn on **colour-blind friendly colours** in Preferences → Map for a set anyone can tell apart, with a small
  mark on the label as well (▶ live, ◆ your party, ✦ an event).
- **Sizes:** aircraft are drawn to scale with each other, so a Cessna is smaller than an A380. Zoomed right in at an
  airport, aircraft on the ground are drawn at their real size, so a 737 fills its stand on the satellite map.
- **Movement:** aircraft glide smoothly between updates, keep turning through a turn, and leave a trail behind them.
- **Lights, shadows and contrails:** from about zoom 6 aircraft show their navigation lights, beacon and strobes,
  taxi and landing lights (when real aircraft would have them on), and a shadow that falls away from the sun. Jets
  cruising at FL280 and above leave contrails, one from each engine.
- **Busy airports** glow, bigger the busier, when three or more flights are heading to or from them.

### 3D aircraft

Zoom right in and aircraft on the ground or low down (below about 2,500 ft, arriving or departing) turn into real 3D
models in their airline's colours, with wheels on the ground and their lights on. There are over 400 types, from
airliners to light aircraft, warbirds and helicopters. Gear folds up after take-off and comes down on approach. The
models are from FlightGear and are credited on the map's credits page.

3D aircraft are set to **Auto** in Preferences → Aircraft: on for computers, off for phones, and off for a while if
the map gets slow (Preferences says so, with a button to turn them straight back on). You can set them to always On
or Off.

### The 3D view of a flight

Select a flight and press 🏔️ (or **3**) to fly round it in 3D, tilted over the hills and mountains, with its path at
its real height and the aircraft's 3D model at the end. The sky is lit from where the sun really is. Use the chip at
the bottom, or close the flight, to go back to the flat map.

## Airports

Tap an airport for its panel. It opens with a summary (the weather in a few words, the runway in use, the next sunrise
or sunset, and flights coming and going) and four tabs:

- **Traffic:** arrivals and departures on a departure board (due times, from or to, type and status: en route,
  descending, approach, landed, taxiing, departed…), the next arrival with a countdown, and the aircraft parked there
  from pilots' hangars and virtual airlines.
- **Weather:** the latest report (METAR, with when it was issued and when the next is due), the forecast (TAF), and the
  sun: whether it's day, twilight or night there, and the next first light, sunrise, sunset and dark.
- **Runways:** every runway end, best into the wind first, with its headwind or tailwind and crosswind and which one's
  in use. Tap one to make it **your runway**: its course, the wind on it, its size and (at US airports) its ILS. The map
  remembers your pick. The **runway queue** lists who's rolling, lined up and holding short, in order, with how long
  each has waited. The airport's radio frequencies are here too (real-world ones, which may not match your sim).
- **Activity:** recent landings (with a landing board for that airport), popular routes, and the airport's busy hours.

The panel opens on the tab you used last. ☆ makes an airport a favourite, so you get an alert when someone takes off
or lands there. **Copy for Discord** on the board copies today's summary for that airport. Airport links can be shared
(`unifly.gg/map/?airport=EGLL`).

### Up close

Zoom in to an active airport (or the one you've opened) and you'll see:

- **Runways** drawn to scale with their numbers painted on.
- **Taxiways** with their names, red dots for holding points, and stands and gates (numbered as you zoom in). These come
  from OpenStreetMap, so busy airports are covered best.
- **3D windsocks** beside the runway in use, filling with the wind.
- A **windsock** marker at arrival airports when zoomed out a little.

### Historic airports

Closed airports that the sims still have, like Kai Tak (VHHX), Chicago Meigs and Durban, are fully supported. Take-offs
and landings there are named after them, flights filed by the old code show the airport, and when someone's flying to
or from one it's drawn over today's map as it was: grounds, grass, aprons, buildings and taxiways. Its panel is marked
🏛️ Historic airport, with a line of its history. You can switch the drawings off in Preferences → Map.

## Map layers

The 🗺️ button holds the layers you can lay over the map:

- **🌧️ Weather radar:** rain and snow from the weather radars (press **R**).
- **☁️ Clouds:** cloud from the weather satellites, a new picture every 15 minutes. The whiter, the higher and thicker.
- **🌬️ Wind:** wind at weather stations around the world as arrows, coloured by speed, with gusts when zoomed in
  (press **W**).
- **🔥 Traffic heatmap:** where UniFly pilots have flown over the last 7 or 30 days. The brighter, the more time flown.
- **🛫 Popular routes:** the most-flown routes on UniFly. Tap one for its route page.

**Day/night shading** is in Preferences → Map.

## Preferences

Open Preferences from the 👤 menu (or press **P**). Changes apply straight away.

- **Map:** map look (Automatic, Streets, Dark or Satellite), day/night shading, historic airports, trails, smooth
  movement, virtual airline colours, colour-blind friendly colours, and **low-data mode** (fewer updates and no 3D,
  radar, contrails or heatmap; *Auto* turns it on for slow connections and data saver).
- **Aircraft:** labels and label detail, the simulator on labels (MSFS24, XP12, P3D…), real-size aircraft, contrails,
  lights and 3D aircraft.
- **Alerts:** take-offs, landings and connections for watched pilots and favourite airports, any pilot connecting or
  changing flight stage, sound, and system notifications while the map is in the background.
- **Units:** speed (kts, km/h, mph), distance (nm, km, mi), altitude (feet or metres), flight levels (automatic from
  each airport's transition altitude, above a fixed altitude, or never), pressure (hPa or inHg), airport codes (IATA
  or ICAO) and times (local or UTC). Climb and descent rates are always in feet per minute.
- **You:** your UniFly nickname for Me mode, and your account.
- **About:** What's new, keyboard shortcuts, stream overlays, the [map status page](https://unifly.gg/status), the
  [press & creators page](https://unifly.gg/press), data credits, tips, and resetting the map's settings.

Light or dark panels are in the 👤 menu (or press **T**).

### Me mode

Tell the map who you are and it marks your aircraft with ♦, adds the 🧑‍✈️ button to find yourself, and tells you your
landing rate, personal bests and new badges. While you're flying, a **Your arrival** card at the top left shows your
destination, distance, time to go and ETA, the likely runway with the wind on it, QNH, visibility and the weather.

If you're signed in with your pilot linked, Me mode is set up for you. Otherwise type your UniFly nickname in
Preferences → You.

## Keyboard shortcuts

| Key | Does |
|---|---|
| **/** | Pilot list and search |
| **B** | Leaderboards |
| **M** | Find me (Me mode) |
| **F** | Follow the selected aircraft on or off |
| **A** | Show all aircraft |
| **L** | Aircraft labels on or off |
| **R** | Weather radar on or off |
| **W** | Wind on or off |
| **3** | The selected flight in 3D (or back to the flat map) |
| **T** | Light or dark |
| **P** | Preferences |
| **+ / −** | Zoom in or out |
| **Esc** | Close the open window or panel |
| **?** | The list of shortcuts |

Windows keep **Tab** inside them while they're open, and if your system is set to reduce motion, the map jumps rather
than flies and nothing slides or blinks.

## Sharing and embedding

- The map's address keeps your view (position, zoom, filters and hub), so a copied link opens the same view.
- Pilots, flights, airports, aircraft types, routes and events all have their own links, which show a picture preview
  in Discord.
- **Embedding:** add `?embed=1` to the map's address for a clean map with no buttons or panels, for a website, Discord
  activity or OBS. Options:

| Option | Does |
|---|---|
| `pilot=Name` | Follows that pilot, with a small info card |
| `zoom=8` | Starting zoom (1 to 16) |
| `labels=0`, `labels=1` or `labels=callsign` | Labels off, on, or just the callsign |
| `airports=0` | No airport dots or tags |
| `trail=0` | No trail behind the followed pilot |
| `night=0` | No day/night shading |
| `theme=light`, `dark` or `satellite` | The map look |

For example: `https://unifly.gg/map/?embed=1&pilot=YourName&zoom=8`
