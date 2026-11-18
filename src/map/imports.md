# Importing your flights

Flown for years somewhere else? Bring those flights into your UniFly logbook. Sign in with your pilot linked, then
open 👤 › **Your account** › **Flights** › **Import flights**.

Imported flights sit in their own list in your logbook, marked with where they came from. They're a record of your
flying, not part of UniFly's: they **never count** for badges, leaderboards, records, landing stats or challenges. The
one exception is the **Back catalogue** badge, for bringing them in.

## Where you can import from

| From | What you need | How to get it |
|---|---|---|
| **FSAirlines** | Your CSV log, and your FSAirlines pilot ID | On fsairlines.net: **Pilot › Logbook › CSV Log Export**. The file is called something like `pilot_12345_log.csv`; the number in its name is your pilot ID. |
| **Volanta** | Either export, as it is | Volanta's own export (ask Volanta for an export of your data: a zip with a file for each flight), or the zip from the free [Volanta data exporter](https://github.com/Scyks/volanta-data-exporter) app (someone else's app; it can take a few hours for a big logbook). Pick which one you've got. |
| **Elevatex** | Your Elevatex data export, as it is | Ask Elevatex for an export of your data. You get a zip like `elvtx-export-….zip`. |
| **Fly UK** | The backup zip Fly UK gives you, and your Fly UK pilot ID | Ask Fly UK for your backup (like `flyukbackup_UKV1234.zip`). |
| **VATSIM** | Just your VATSIM CID | No file: UniFly fetches your flight plans and connections from VATSIM's public records. |

## How it works

1. **Choose where your flights are**, then the file (or put in your VATSIM CID).
2. **Check the preview.** Nothing's added yet. It shows how many flights will come in and about how many hours, and
   what's being left out and why:
   - flights already in your UniFly logbook, or imported before
   - flights already imported from **another platform** (the same flight on FSAirlines and VATSIM, say: same airports,
     about the same time). You keep the copy you imported first.
   - failed filings, flights filed twice, and flights that never landed
   - for VATSIM, flight plans you weren't connected for at least half the planned time

   It also tags circuits, flights flown with sim rate, and times it had to estimate (when a sim's clock wrapped round or
   jumped). If the file has airports UniFly doesn't know (old, renamed or made-up codes), they show as *Unknown airport*
   until the UniFly Team matches them. Your flights are fixed when they do.
3. **Add your proof and import.** Except for FSAirlines (checked against your public FSAirlines signature), you add a
   screenshot of your profile on that platform showing your name and your flights or hours. Only the UniFly Team sees
   it.
4. **The UniFly Team checks it.** Until then your imported flights are only visible to you. Once it's approved they
   show in your logbook, and you get the **Back catalogue** badge. If it isn't approved, your account says why.

## What you'll see

- **Your logbook** has an *Imported* list, each flight marked with where it came from, its time (≈ when estimated,
  and for VATSIM, which only knows when you logged on and off) and, where the platform kept them, its landing rate and
  g. Elevatex flights come with a simplified path: tap 🗺️ **Path** to see it on the map.
- **Your pilot page** shows imported flights and hours under your UniFly ones (📦 +1,234 imported), and their airports
  in the Places tab.
- **Plot routes** on your logbook can include your imported flights.

## Managing your imports

From the Import flights card on your account:

- **Show my imported flights on my public logbook:** untick it to hide them from everyone else.
- **My imported flights:** look through them and **Remove** any single flight.
- **Find duplicates:** lists flights you've imported twice from different platforms and takes out the later copies
  (you confirm first).
- **Undo this import:** removes everything that import brought in.

## What happens to your files

Your files aren't kept.

- **FSAirlines and Fly UK:** read on the server straight away. Only the flights are kept, never the file.
- **Volanta and Elevatex:** read in your browser. Only your flights (and, for Elevatex, a simplified path for each) are
  sent. Everything else in the export, like your email, friends and screenshots, stays on your computer.
- **VATSIM:** no file at all.

What's kept is the imported flights, a short summary of the file for the UniFly Team to check against your proof, and
your proof screenshot (deleted when the import is undone or removed).

## Questions

**My imported flights aren't showing.** They show for everyone once the UniFly Team has approved the import. Check its
status on your account (*waiting for approval*, *approved* or *not approved*, with the reason). If it's approved,
make sure **Show my imported flights on my public logbook** is ticked.

**Why don't they count for badges?** UniFly's badges and leaderboards are for flying on UniFly, where the map saw the
flight itself. Imported flights are kept as your history instead.

**Some flights were left out.** The preview says why for each kind. Flights already on UniFly, already imported, or
never finished aren't brought in twice or half-done.

**An airport shows as unknown.** The code in your file isn't one UniFly knows (often an old or renamed airport). The
UniFly Team matches it, and every flight with that code is fixed.
