# Troubleshooting & FAQ

## I'm not showing on the map

- **Check you're connected:** the UniFly client should show both Network and Simulator as green `Connected`.
- **Still in the sim's menus?** Pilots in the menus aren't drawn on the map. They're counted in the pilot counter and
  listed under *In the menus* in the pilot list. You'll appear once you're loaded into a flight.
- **Loading screens:** some sims park you at a stand-in spot while loading (such as 0°N 0°E, or the middle of the
  Indian Ocean). The map treats that as being in the menus too.
- **Is the map itself working?** Check the pilot counter's dot (green is live) and the
  [status page](https://unifly.gg/status).

## My landing has no rate, or didn't count

- **Joined in the air:** if you connected mid-flight, the landing only counts for leaderboards and badges when you
  joined at least 10 minutes before landing.
- **Sim rate:** landings flown with time acceleration on aren't counted, and sped-up flights don't count for the
  long-flight badges.
- **Slewing and teleports:** no take-off or landing is logged from moving the aircraft in slew mode or teleporting.
- **X-Plane:** X-Plane's readings can't yet be trusted for a landing rate, so X-Plane landings are logged without one
  for now.
- **Opted out:** pilots who've opted out of recording don't get landings recorded. See
  [Privacy and opting out](index.html#privacy-and-opting-out).

If a rate looks wrong, use **🚩 Report** on the flight (live or in your logbook) and the UniFly Team will take a look.

## An airport didn't count towards my badge

Airports, countries and continents only count when you land there having flown in from at least 50 nm away.
Circuits, short hops from the airport next door, take-offs, and teleported or slewed flights don't count. Famous
airports like Lukla, Saba and Courchevel count from any distance, as long as you flew in from somewhere else. The same
rule applies to the destination of the week's passport stamp.

## My flight was split in two, or ended early

- **Dropping off and reconnecting** carries on the same flight, even under a different callsign or on another hub, as
  long as you carry on from where you were. A new callsign while you're on the ground is a new flight.
- **Back to the menus:** if you go back to the sim's menus mid-flight and aren't flying again within 5 minutes, the
  flight ends there, marked incomplete in your logbook.
- **Paused:** pausing doesn't end a flight. Paused time just isn't counted as flying time.

If a flight still looks wrong, report it from your logbook.

## My aircraft type is wrong or not recognised

Types typed in by hand are matched where it's clear (*737-800* becomes B738). If yours isn't recognised, your account
window lists it: say what you were really flying (its ICAO code) and the UniFly Team will put your logbook, stats and
badges right.

## My flight didn't count for my virtual airline

For a flight to count for an airline:

- you must be a member of it,
- your callsign must be its code and a flight number (or you used *Fly this one* or booked a timetable flight first),
- and it must have an aircraft of the type you're flying parked at the airport you take off from, free to fly (not
  in a maintenance check, grounded for an inspection or being flown by someone else).

If the map picked the wrong one of two aircraft, you can switch it for 24 hours after landing. See
[Virtual airlines & hangars](airlines-hangars.md#flying-for-your-airline).

## My flight went to my airline, not my own aircraft

That's by design: a flight that counts for your airline is always flown in the airline's aircraft. See
[Your hangar and a virtual airline don't mix](airlines-hangars.md#your-hangar).

## My stream overlay is blank or out of date

- If you dropped off UniFly mid-flight, the overlay shows *Reconnecting…* for up to 2 minutes, then carries on when
  you're back.
- Check *Sample data in the links too* isn't ticked in the overlay maker if you want your live flight.
- Saved overlays update themselves, so there's no need to refresh the Browser source in OBS.

## The map is slow on my computer

- Set **3D aircraft** to Off in Preferences → Aircraft.
- Turn on **Low-data mode** in Preferences → Map (fewer updates, and no 3D, radar, contrails or heatmap).
- Switch off contrails and lights in Preferences → Aircraft, and any map layers you don't need.

## Still stuck?

Ask in the [UniFly Discord](https://unifly.gg/discord).
