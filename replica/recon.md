# Recon map: open-world festival racing game (PC first), studied from Forza Horizon 6

Scope: the core loop of the genre (free roam, then events, then rewards, then new cars and upgrades, then more events), rebuilt clean-room as an **original game** on an original map of the **Côte d'Azur, from Menton to Fayence**. Forza Horizon 6 is the reference for *mechanics and UX patterns only*: no name, festival branding, characters, art, music, UI look, car models or map are reused.
For: the user's own project (an indie game). Platform: PC (Windows) first, controller + keyboard. Consoles later, if ever.
Date: 2026-11-08

Working title, to be replaced by `/replica-brand`: **"Riviera Run"** (placeholder only).

## Sources

All public. No game files, no network captures, no account used (the user has no access to their computer, so there is no "own account" pass; that is a gap, see the end).

| # | source | URL | notes |
| --- | --- | --- | --- |
| 1 | official feature list | https://forza.net/news/forza-horizon-6-features | 10 new systems: Horizon Rush, Wristbands, Time Attack Circuits, Car Meets, Drag Meets, Estate, garages, CoLab, seasons, proximity radar |
| 2 | latest update release notes | https://forza.net/news/forza-horizon-6-series-6-release-notes | live-service cadence: series, new rewards, treasure car |
| 3 | Developer Direct preview | https://gameinformer.com/xbox-developer-direct/2026/01/22/forza-horizon-6-gets-first-gameplay-details-and-may-launch-date | first gameplay details, prologue |
| 4 | dev details on touge / playlist | https://www.gosugamers.net/entertainment/news/78358-forza-horizon-6-devs-confirm-new-details-on-touge-battles-festival-playlist-and-more | touge not tied to festival progression |
| 5 | weekly playlist structure | https://windowscentral.com/gaming/forza/xboxs-forza-horizon-6-gets-its-first-festival-playlist-next-week-includes-10-new-cars-and-4-from-the-car-pass | 4-week series, 7-day seasons, ~1 h to unlock |
| 6 | Series 2 notes | https://gamermatters.com/forza-horizon-6-series-2-brings-10-new-cars-to-earn-evolving-car-meet-and-more/ | Trials: 6v6 co-op vs top AI |
| 7 | review (GTPlanet) | https://www.gtplanet.net/forza-horizon-6-review-ga-ii-desu-ne-20260514/ | map size, car count, structure |
| 8 | review (TechRadar) | https://www.techradar.com/gaming/forza/forza-horizon-6-review | what the map does well |
| 9 | review (COG Connected) | https://cogconnected.com/?p=386045 | criticism: "safe" formula |
| 10 | review (Maxim) | https://www.maxim.com/entertainment/forza-horizon-6-review-a-high-speed-love-letter-to-japanese-car-culture/ | criticism: radio |
| 11 | store page | https://www.playstation.com/games/forza-horizon-6/ | pitch, platforms |
| 12 | public walkthrough videos | to collect by hand | needed to count real clicks and menu states; not done yet |

Facts used: launched 19 May 2026 (Xbox Series X|S, PC; PS5 later); map built from several Japanese regions, reported as about twice FH5's size; 550+ cars at launch; 8 player houses plus "The Estate" (building in the open world); four seasons, with snow all year in the alpine zone.

## Core loop

Drive freely around a beautiful real region, find an event, race it, win credits, XP and a car, upgrade it, go further on the map, and keep coming back for the weekly seasonal playlist.

## The map: Côte d'Azur, Menton to Fayence

Real geography, compressed. Menton to Fayence is about 70 km in a straight line, and a little over 40 km inland as far as Col de Turini. **Recommended scale: 1:6 to 1:8**, giving a playable map of about 10 x 6 km, the same order as the genre's maps. The coast and the roads are kept, and the gaps between them are squeezed.

| zone | real places (geography only) | gameplay role | biome / surfaces |
| --- | --- | --- | --- |
| Z1 Menton & the Italian border | Menton, old town, Garavan, Roquebrune-Cap-Martin | start of the prologue, first house | Mediterranean town, narrow streets |
| Z2 Monaco *(see legal note)* | the principality's streets, tunnel, port | night street circuit, showcase | dense city, tunnel, port |
| Z3 The three Corniches | Basse / Moyenne / Grande Corniche, Èze, Beausoleil, La Turbie | signature high-speed sea roads, panoramas | cliffs, hairpins, tunnels |
| Z4 Nice | Promenade, Port, Vieux-Nice, Mont Boron, the airport | city hub, festival hub, drag strip (fictional airfield) | city, wide boulevards |
| Z5 Cap & Antibes | Villefranche, Cap Ferrat, Antibes, Juan-les-Pins, Cap d'Antibes | coastal roads, beaches, marina | sand, coast |
| Z6 Cannes & the Estérel | Cannes, Croisette, Mandelieu, Théoule, Corniche d'Or (red rocks) | coastal sprints, off-road in the massif | red rock, gravel tracks |
| Z7 Arrière-pays (perched villages) | Saint-Paul-de-Vence, Vence, Tourrettes-sur-Loup, Gourdon, Gorges du Loup | narrow pass battles ("col duels") | stone, gorges |
| Z8 Grasse & Route Napoléon | Grasse, N85, Saint-Vallier, Plateau de Caussols | fast flowing road, plateau off-road, observatory | limestone plateau, scrubland |
| Z9 Fayence & Lac de Saint-Cassien | Fayence, Tourrettes, Montauroux, the lake | west end, glider airfield (fictional), lake | hills, vineyards, water |
| Z10 High country | Col de Turini, Sospel, Col de Braus, Peille, Col de Vence | rally stages, **snow all winter**, mountain pass duels | mountain, snow, ice |

Note: the Col de Turini roads are famous from the Monte-Carlo Rally. The roads themselves are public geography and can be used; the rally's name and branding cannot. Real buildings get generic facades, with no real shop or hotel brands.

## Screens

Screens are menus and HUD states. The open world itself is S04.

| ID | screen | route / how to reach | purpose | key components | states seen |
| --- | --- | --- | --- | --- | --- |
| S01 | Boot / title | launch | start, continue, settings | logo, Press Start, profile | first launch, returning, offline |
| S02 | Prologue drive | new game | 3-4 scripted events, one per biome, to show the map | HUD, scripted transitions | first run only |
| S03 | Car pick at arrival | end of prologue | choose 1 of 3 starter cars | car carousel, stats card | — |
| S04 | Open world HUD | default | free roam | minimap, speed/gear, notifications, nav line, radar | day/night, season, weather, online/offline |
| S05 | Pause menu (tab hub) | Start / Esc | gateway to everything | tabs: Campaign, Cars, Online, Profile, Settings | — |
| S06 | World map | from S05 / Map key | browse, filter, fast travel, set route | map, icon filters, legend, zone names | fog of war (undiscovered roads), filtered |
| S07 | Event card | approach an event marker | event info and start | type, class rule, rewards, best time, "Start / Edit car / Rivals" | locked, unlocked, done (stars) |
| S08 | Pre-race lobby / car select | from S07 | pick an eligible car, difficulty | garage filtered by class, AI difficulty slider, tune | no eligible car (offer to buy) |
| S09 | Race HUD | race start | position, laps, checkpoints, rewind | countdown, position, laps, checkpoint arrows, mini leaderboard | rewind active, wrong way, DNF |
| S10 | Results | race end | rewards | podium, time, XP, credits, skill points, "continue / replay / rivals" | win, lose, new record |
| S11 | Garage | S05 > Cars | collection | grid by maker/class, sort, filter | empty (start), filled |
| S12 | Upgrade & tune | S11 > car | performance parts, class (PI) | part categories, before/after stat bars, PI gauge | can't afford, class limit |
| S13 | Paint / livery editor | S11 > car | design | layers, shapes, colours, windows | new, saved, shared |
| S14 | Car dealer | S05 > Cars > Buy | buy new cars | catalogue, price, preview | can't afford |
| S15 | Aftermarket (used cars) | approach a parked car in the world | test drive, buy at a discount | price, mileage, test drive | sold, test-drive timer |
| S16 | Houses | house marker on S06 | buy, set as spawn point, perks | house card, price, perks | owned, locked |
| S17 | Estate / build mode | own house > Build | build on a plot in the world | prop palette, grid, budget | empty plot, built |
| S18 | Progression / journal | S05 > Campaign | % of map, zones, accolades | progress bars per zone and discipline | 0%, partial, 100% |
| S19 | Seasonal playlist | S05 > Playlist | weekly challenges | season card, challenge list, reward track | locked (before unlock), active, done |
| S20 | Skills / perk tree per car | S11 > car > Mastery | spend skill points | node grid | — |
| S21 | Photo mode | pause in free roam | photos | camera, filters, time, focus | — |
| S22 | Online: shared world / meets | S05 > Online | see other players, join a meet | player list, session, invite | solo, online, joining |
| S23 | Settings | S05 > Settings | controls, aids, graphics, audio | sliders, toggles, key remap | — |
| S24 | Radio / music | in car, d-pad | choose a station | station wheel | radio off |

24 screens.

## Flows

```
F01 First session: from launch to free roam
    S01 -> S02 (4 scripted events, one per biome: Menton town, Corniche, Estérel, Turini snow) -> S03 -> S04
    happy path: ~5 inputs before driving; first car in hand within 10 minutes
    edge: skip prologue for returning players, controller not detected

F02 Do an event (the core loop)
    S04 -> drive to marker -> S07 -> S08 -> S09 -> S10 -> S04
    happy path clicks: 3 (Start, Car, Go) - the number to beat
    edge: no eligible car, rewind, restart, quit mid-race, record broken

F03 Upgrade a car for a class
    S05 -> S11 -> S12 -> pick parts -> PI goes up to class limit -> save
    edge: not enough credits, auto-upgrade, a part pushes it over the class

F04 Buy a car (new or used)
    S14 buy  /  S04 -> parked aftermarket car -> S15 test drive -> buy
    edge: can't afford, already owned

F05 Discover the map
    S04 drive -> road segments discovered -> S06 fog lifts -> zone % in S18
    edge: fast travel only once a house is owned in that zone

F06 Buy a house and use it
    S06 -> house marker -> S16 -> buy -> fast travel unlocked -> S17 build
    edge: can't afford

F07 Weekly seasonal playlist
    S05 -> S19 -> pick challenge -> do it in the world -> points -> reward
    edge: season changes mid-session (weather, snow on Turini), challenges expire

F08 Col duel (one-on-one on a mountain road)
    S04 -> challenge a rival at a col start -> S09 (point-to-point, narrow road) -> S10
    edge: collision rules, rival takes the lead

F09 Online: join a meet / shared event
    S05 -> S22 -> join -> drive to the meet in the world, no loading screen
    edge: offline, session full, NAT problems
```

## Components

| component | variants | states | used on |
| --- | --- | --- | --- |
| Tab menu | top tabs + cards | focus, locked | S05, S11, S18 |
| Card (tile) | event, car, house, challenge | locked, available, done, new | S05, S07, S11, S14, S16, S19 |
| Stat bars | speed, handling, accel, launch, braking | before/after, over limit | S03, S08, S12, S14 |
| Class / PI badge | D, C, B, A, S1, S2, X (letters to replace with your own) | — | everywhere for cars |
| Minimap + nav line | normal, race, fog of war | — | S04, S09 |
| World map | icon filters, legend | zoom, filter, fast travel | S06 |
| Notification toast | skill chain, discovery, reward | stacking | S04, S09 |
| Skill-chain meter | drift, near miss, air, speed | combo, broken | S04 |
| Race HUD | position, laps, checkpoint, timer | rewind, wrong way | S09 |
| Rewind control | — | available, used | S09 |
| Reward screen | XP bar, credits counter, items | — | S10, S19 |
| Countdown | 3-2-1 | — | S09, drag meets |
| Prompt / button hint | controller, keyboard | — | everywhere |
| Slider / toggle | — | default, focus | S08, S23 |
| Radio wheel | stations | — | S24 |

## Inferred data model

```
Player       id, name, level, xp, credits, skill_points, current_house_id, settings (json)
             evidence: S10 rewards, S18 · confidence: high

CarModel     id, maker (fictional), name, year, class_base, pi_base, drivetrain, stats (json), price, rarity
             evidence: S11, S14 · confidence: high

OwnedCar     id, player_id, car_model_id, pi, class, upgrades (json), tune (json), livery_id, mileage, mastery (json)
             evidence: S11, S12, S20 · confidence: high

Upgrade      id, category (engine, tires, aero...), name, price, stat_effects (json), pi_delta
             evidence: S12 · confidence: high

Event        id, type (road, dirt, street, cross-country, drag, col duel, time attack, rush),
             zone_id, route_id, class_rule, laps, ai_count, rewards (json), unlock_rule
             evidence: S07, S09, source 1 · confidence: high

Route        id, name, waypoints (polyline), start, finish, length_m, surface_mix
             evidence: S06, S09 · confidence: medium

EventResult  id, player_id, event_id, owned_car_id, time_ms, position, stars, difficulty, at
             evidence: S10 · confidence: high

Zone         id, name (Menton, Corniches, Nice, Estérel, Turini...), bounds, roads_total, roads_found
             evidence: S06, S18 · confidence: medium

House        id, zone_id, name, price, perks (json), spawn_point
             evidence: S16, source 1 · confidence: high

EstateBuild  id, player_id, plot_id, props (json)
             evidence: S17, source 1 · confidence: medium

Season       id, series_no, season (spring|summer|autumn|winter), starts_at, ends_at, weather_profile
             evidence: S19, source 5 · confidence: high

Challenge    id, season_id, kind, target (json), points, reward
             evidence: S19 · confidence: high

Livery       id, owner_id, car_model_id, layers (json), shared (bool), downloads
             evidence: S13, source 1 · confidence: high

Collectible  id, kind (speed trap, speed zone, danger sign, discovery board, treasure car), zone_id, position, record
             evidence: S04, source 2 · confidence: medium (guess on exact names)
```

Relationships: Player 1-n OwnedCar, CarModel 1-n OwnedCar, OwnedCar n-n Upgrade, Zone 1-n Event, Event 1-1 Route, Player 1-n EventResult, Season 1-n Challenge, Player 1-n House, Player 1-n Livery.

## Feature matrix

See `features.csv`. Must: 16, should: 14, could: 10, skip: 7.

## Out of scope (cannot or should not be cloned)

- **The name, the festival, its branding, characters, UI look, music, voice lines.** All original, via `/replica-brand`.
- **Licensed cars.** Real car makes and models need a licence from each manufacturer (and their logos are trademarks). The clone uses **fictional cars and makes**. You can draw on eras and body styles (90s coupé, hot hatch, rally saloon) without copying a real car's shape.
- **Licensed music.** The radio needs your own tracks, royalty-free music or commissioned music.
- **Real trademarks in the world.** No real shops, hotels or race names (Monte-Carlo Rally, Grand Prix). The geography (roads, coast, villages) can be used.
- **Monaco.** The streets can be modelled as a fictional "principality" district. The Grand Prix name, logo and official circuit branding are protected.
- **The playerbase and live service.** Thousands of online players and a weekly content team: you start with solo + a small seasonal playlist.
- **Partner deals** (the in-game convenience-store brand, for example).

## Size

Screens 24, flows 9, entities 14.

Hard parts:
1. **The map.** 70 km of real coast and mountains to model, even at 1:7. Realistic approach: heightmap from public data (IGN RGE ALTI or SRTM, check licences) + roads from OpenStreetMap (ODbL licence: credit required) + procedural buildings. This is most of the work.
2. **Car physics that feel good.** Arcade-sim handling on asphalt, gravel, snow. Use an engine's vehicle system (Unreal Chaos Vehicles, Unity + a vehicle asset) rather than writing it.
3. **Content volume.** Dozens of fictional cars to model, events, seasons with weather (snow on Turini). Online shared world is a project in itself.

Size: **XL as stated.** Rescoped proposal:
- **Vertical slice (L, a quarter, small team / months solo):** one zone (the Corniches, Menton to Nice), 5 fictional cars, 4 event types, upgrades, garage, day/night, solo only.
- Then add zones one by one (Estérel, arrière-pays, Turini with snow, Fayence), then seasons, then online.

## Gaps to fill

- No hands-on session (user has no computer access): the click counts and screen states above come from public sources, not observed. A short pass on public walkthrough videos would confirm F01-F02.
- No screenshots saved in `replica/screens/` yet.
