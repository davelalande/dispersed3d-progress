<p align="center"><a href="https://momatio.com/dispersed3d/"><img src="media/share/lolo-national-forest.jpg" alt="Dispersed 3D: a truck with its tent up beside a campfire at dusk, in the Lolo National Forest" width="100%"></a></p>

# Dispersed 3D

**A free overland AI/human adventure game and dispersed camping simulation on real public land.** Drive the forest roads, pick a camp, and light a fire under tonight's real sky, on your own or with your AI. It plays in your browser, on a phone or a computer.

<h2 align="center"><a href="https://momatio.com/dispersed3d/">Play it free</a> &nbsp;&nbsp;|&nbsp;&nbsp; <a href="https://momatio.com/dispersed3d/try">Try the preview</a></h2>

<p align="center">The preview is the next version, with the newest things in it before they go live.</p>

New here? On the opening card, tap **Show me a night**. The game drives itself for 90 seconds and ends at a lit fire.

## What's real

This is a game laid over real places, and the real places do most of the work. Here is where each part comes from.

| What you see | Where it comes from |
|---|---|
| The ground | USGS 3DEP lidar elevation, about 1 meter close to the camps |
| The photograph on the ground | USGS NAIP aerial imagery. The color of a place is the photograph's color |
| The roads | The USGS road map, with the Forest Service's own road numbers, surfaces, maintenance levels and open dates where the agency records them |
| The creeks | The USGS NHDPlus HR stream map, and the USGS stream gauge's newest reading where one sits on a camp's named water |
| The wetlands on the map | The U.S. Fish and Wildlife Service's National Wetlands Inventory, mapped from aerial photographs. The edges are approximate |
| Peak names | GNIS, the federal place-name record |
| Tonight's weather and sky cover | The National Weather Service hourly forecast |
| Smoke | NOAA's satellite smoke maps |
| The Sun, the Moon and the stars | Computed for the place and the hour. The stars are the Yale Bright Star Catalogue; the Milky Way sits where the galactic plane really is |
| The campsites | [American Adventurer's](https://davelalande.com/map) public camping data: what the record says about cost, season, stay limits, rules and water |
| The campfire sound | A CC0 recording of a real campfire, by SKrafft on Freesound |
| The grain of the ground up close | CC0 ground photographs from Poly Haven and ambientCG |

**And plainly, what is the game's own:** the truck, the tent and the walk, the shapes of the clouds, the trees (placed where the photograph shows forest, but not one is a real tree), the grass, the rocks and stumps, the fire, the fuel and water in the rig, and the pictures the game draws for you to share. Where a record says nothing, the game says nothing. No cost on record does not mean free. The game has an About page that says all of this with the numbers.

## What's new

**November 14, 2026, 1:04 PM: Tomorrow's trouble, your morning card, and a quicker first roll**

- **Quicker to the first roll.** A first visit now starts the truck with one tap on "Your first night," and you can tap ahead while the ground is still loading. On a phone the scenery waits until you are rolling, so the first minute is lighter.
- **Never a blank screen.** If your device can't start the 3D view or it stalls, you get a plain message and a way forward instead of an empty page. Older phones are handled gently.
- **Call while it loads.** While the ground loads on a first phone visit, you can look at a few pictures of the forest and make one real call about where to camp.
- **Tomorrow's trouble.** At bed-down on night one (and night three, if you haven't been to town yet) a plate shows tomorrow's forecast next to your gas, your water and the road miles to town. You pick a town run or push on, and the morning card says what you chose. New challenges only; older ones play as before.
- **Your morning card.** After a night, one tall picture of your camp and what the game measured there, to save or share.
- **Night two is waiting.** Leave at dawn and the title says your camp is waiting. Continue picks the trip up on the same phone, you can text yourself the link, and a waiting camp is kept 14 days.
- **The morning after.** Each camp's Drive line says when the sun first reaches camp (bare ground, and trees may delay it). The morning card has one line, "The night, in words," and on a calm, warm evening beside a mapped wetland the game may say the bugs are out, marked as the game's guess. Challenges use the new rules number 19; older challenges are unchanged.
- **Where the AI camped.** After your first night, the morning card can quote a checked AI run that camped in the same forest, with its own reason. Only free sites, and not every forest has one.

[Every release, in the changelog](https://github.com/davelalande/dispersed3d-progress/blob/main/CHANGELOG.md)

## Pictures

<table>
<tr>
<td width="50%" valign="top"><img src="media/star-trails.jpg" alt="Star trails at Lakeside Campground, Lolo National Forest: an hour of the real sky in one picture." width="100%"><br><sub>Star trails at Lakeside Campground, Lolo National Forest: an hour of the real sky in one picture.</sub></td>
<td width="50%" valign="top"><img src="media/campfire-postcard.jpg" alt="The postcard from Langohr, Custer Gallatin National Forest: your camp, under tonight's sky." width="100%"><br><sub>The postcard from Langohr, Custer Gallatin National Forest: your camp, under tonight's sky.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="media/creek-jug.jpg" alt="Hyalite Creek in the Custer Gallatin National Forest. Walk to the real creek and fill the jug." width="100%"><br><sub>Hyalite Creek in the Custer Gallatin National Forest. Walk to the real creek and fill the jug.</sub></td>
<td width="50%" valign="top"><img src="media/dusk-ridge.jpg" alt="Dusk in the Beaverhead-Deerlodge National Forest, with the camps ahead named from the public record." width="100%"><br><sub>Dusk in the Beaverhead-Deerlodge National Forest, with the camps ahead named from the public record.</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="media/sunset-sky.jpg" alt="Sunset over the hills, with clouds in the sky." width="100%"><br><sub>Sunset over the hills, with clouds in the sky.</sub></td>
<td width="50%" valign="top"><img src="media/share/quartzsite-yuma-field-office.jpg" alt="Quartzsite, Arizona: the desert world, at tonight's camp near sunset." width="100%"><br><sub>Quartzsite, Arizona: the desert world, at tonight's camp near sunset.</sub></td>
</tr>
<tr><td width="50%" valign="top"><img src="media/fire-on-phone.jpg" alt="The fire at Lakeside Campground, on a phone." width="60%"><br><sub>The fire at Lakeside Campground, on a phone.</sub></td><td width="50%" valign="middle">It plays on a phone, with a thumbstick on the screen and a drawer of buttons you pull up, and on a computer, where the mouse steers with no click.</td></tr>
</table>

## Built in the open: the Asset Lab

Some of the things you see in the game, like the road-number posts at the forks, come from **[Momatio's Asset Lab](https://momatio.com/assets/)**: an AI agent writes a Blender script for each model, renders it, looks at its own renders, fixes what is wrong, and a person reviews the result. Every step is recorded, so you can spin each model and **watch it being made**. Nothing is bought, scanned or copied: each model is built from scratch by its script.

## The four forests

Each one has its own page with a picture of a real camp near sunset, dated on the card. New pictures come with each release.

<table>
<tr><td width="240"><a href="https://momatio.com/dispersed3d/share/lolo-national-forest.html"><img src="media/title/lolo-national-forest-wide.jpg" alt="Lolo National Forest" width="240"></a></td><td valign="middle"><strong>Lolo National Forest</strong>, Montana<br><a href="https://momatio.com/dispersed3d/share/lolo-national-forest.html">Tonight's camp, as a picture</a> &nbsp;|&nbsp; <a href="https://momatio.com/dispersed3d/">Play it</a></td></tr>
<tr><td width="240"><a href="https://momatio.com/dispersed3d/share/custer-gallatin-national-forest.html"><img src="media/title/custer-gallatin-national-forest-wide.jpg" alt="Custer Gallatin National Forest" width="240"></a></td><td valign="middle"><strong>Custer Gallatin National Forest</strong>, Montana<br><a href="https://momatio.com/dispersed3d/share/custer-gallatin-national-forest.html">Tonight's camp, as a picture</a> &nbsp;|&nbsp; <a href="https://momatio.com/dispersed3d/">Play it</a></td></tr>
<tr><td width="240"><a href="https://momatio.com/dispersed3d/share/beaverhead-deerlodge-national-forest.html"><img src="media/title/beaverhead-deerlodge-national-forest-wide.jpg" alt="Beaverhead-Deerlodge National Forest" width="240"></a></td><td valign="middle"><strong>Beaverhead-Deerlodge National Forest</strong>, Montana<br><a href="https://momatio.com/dispersed3d/share/beaverhead-deerlodge-national-forest.html">Tonight's camp, as a picture</a> &nbsp;|&nbsp; <a href="https://momatio.com/dispersed3d/">Play it</a></td></tr>
<tr><td width="240"><a href="https://momatio.com/dispersed3d/share/quartzsite-yuma-field-office.html"><img src="media/title/quartzsite-yuma-field-office-wide.jpg" alt="Quartzsite, BLM Yuma Field Office" width="240"></a></td><td valign="middle"><strong>Quartzsite, BLM Yuma Field Office</strong>, Arizona<br><a href="https://momatio.com/dispersed3d/share/quartzsite-yuma-field-office.html">Tonight's camp, as a picture</a> &nbsp;|&nbsp; <a href="https://momatio.com/dispersed3d/">Play it</a></td></tr>
</table>

## Where it's headed

**Up next**

- **Press Play and you are rolling.** On a first visit, Play skips the welcome and starts the truck toward tonight's camp, with one line on how to take the wheel.
- **A quieter AI turn bar.** Fold your AI's turn box away and it stays folded, with one slim line saying which turn it is on and why.
- **Tracks that load.** The Tracks switch gets its data for Custer-Gallatin and the Quartzsite desert, so it has something to draw.
- **A lighter first page load.** About 50 KB less to download up front: the trip, map and morning cards load just after the first roll.
- **Standard driving camera views.** Cockpit view with free look, Hood cam and Chase cam, with one key to switch between them.
- **A second desert world: Hurricane Cliffs, Utah.** A desert near St. George, to go with Quartzsite, Arizona.
- **An on-foot character.** Walk around as a person, with first-person and third-person views.

**Ideas we're weighing** (nothing is built until we decide)

- Smaller, faster photos on phones
- Wildlife: a deer or an elk at dusk
- Read this card aloud, in the phone's own voice

[The whole roadmap](https://github.com/davelalande/dispersed3d-progress/blob/main/ROADMAP.md)

## Tell us

Got an idea, or did something break? Say what you'd like, or what happened, and what you were playing on. No code needed.

- [Tell us an idea](https://github.com/davelalande/dispersed3d-progress/issues/new?template=idea.yml)
- [Report a bug](https://github.com/davelalande/dispersed3d-progress/issues/new?template=bug.yml)
- [See what others have said](https://github.com/davelalande/dispersed3d-progress/issues)

---

<sub>Dispersed 3D is made by Momatio. © 2026 Momatio. All rights reserved. This repository holds the project's progress, not its source code.</sub>
