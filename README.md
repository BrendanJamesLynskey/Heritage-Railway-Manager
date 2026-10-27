# Heritage Railway Manager

A browser-based management tycoon in which you run a preserved
**heritage railway** in the north of England: the fictional
**Ravensgill &amp; Highmoor Railway**, 14 miles of single line up a Pennine
dale. Timetable the normal service, organise **steam and diesel galas**,
**beer &amp; music festivals**, **1940s weekends** and **Santa specials**,
look after the locos and the volunteers, and grow the line until it's named
*Heritage Railway of the Year*.

A companion to [UK Railtour Manager](https://github.com/BrendanJamesLynskey/UK-Railtour-Manager).

[Play it here](https://brendanjameslynskey.github.io/Heritage-Railway-Manager/)

Everything runs in a single self-contained `index.html`: no build step, no
dependencies, no network after load. It runs comfortably in Chromium on a
Raspberry Pi 5. Progress auto-saves to your browser's local storage.

## The Laptop

The game runs on the general manager's laptop: a bezel frames the screen,
and the railway's apps sit on a desktop with a Pennine wallpaper. **Double-click
an icon** (or tap it on a touch screen) to open an app in its own window:
Timetable, Line Map, Events Calendar, Mail, Ravensgill Shed, Motive Power,
Carriages, Works, Volunteers &amp; Upgrades, Ledger and How to Play. Drag
windows by the title bar, resize them from the corner, minimise, maximise and
close them, and switch between them on the **taskbar**, which also holds the
**Run the Weekend** button, the balance, reputation, volunteers and week. The
**Start** button (the R&amp;H roundel) lists every app, plus Save / Load and
New Game. On a phone, windows open full screen.

## The Yard: Drive the Shunter

When you press **Run the Weekend** you're offered the chance to marshal the
first train yourself. Say yes and the laptop folds away: you're in the cab of
the Class 08 shunter in Ravensgill yard, in first person (a small built-in
WebGL renderer, so it still works offline).

The yard is a classic *Inglenook* shunting puzzle: a headshunt that holds the
shunter and three coaches, a three-way point, and three roads (the Platform
road, Siding A and Siding B). The day's train engine, three of its coaches and
a few spare vehicles start scattered across the sidings. Form the train on the
Platform road **in the order shown**, engine nearest the points.

| Control | Keys / on screen |
|---------|------------------|
| Drive forward / back | ↑ / ↓ or W / S, or hold ▶ / ◀ |
| Brake | Space, or hold ■ |
| Look round | ← / → or A / D, or drag (double-click to recentre) |
| Points | 1 Platform road · 2 Siding A · 3 Siding B (locked while anything stands over them) |
| Uncouple | U drops the far vehicle, or click ✂ between any two vehicles |

Buffer up at under 2 mph to couple to everything standing in that cut; faster
is a rough shunt, and over 5 mph is a crash. A mini-map and the job card show
progress. Finish quickly with no rough shunts for ★★★ (+2 reputation and a
morale boost), or leave the yard at any time and the shed staff finish the job.
Then the weekend runs as normal.

## Mail: Hiring Out Your Locomotives

Railtour companies and other heritage railways (all fictional) email asking
to hire your engines: a main-line railtour, a gala on another line, or a
winter loan of several weeks. Each email names the loco, the dates and an
opening offer. **Accept**, **decline** or **send a counter-offer**: each sender
has a private ceiling and limited patience, so ask for a bit more and they may
meet you, or meet you halfway; ask far too much and they'll find another
engine. Unanswered offers lapse. The fee is paid when you agree; the engine is
away for the agreed weeks (it can't run, be sold or go to the works then) and
comes back a little more worn, with a small boost to your reputation.

## Saving and Carrying On Elsewhere

Press **💾 Save / Load** for a **save link**: the whole railway is compressed
into the link itself (in the `#save=` part, which never leaves your browser,
so nothing is uploaded). **Copy** it, **email it to yourself**, or **download**
it as a small text file. Opening the link on any device (another computer, a
phone, the Pi) asks whether to load that railway. You can also paste a link or
open a save file from the same dialog.

To start from scratch, press **🆕 New Game** (next to Save / Load). It asks
first, so save a link beforehand if you might want the old railway back.

## The Line

| Station | Mile | Passing loop | Notes |
|---------|------|--------------|-------|
| Ravensgill Junction | 0.0 | Yes (3 platforms) | Main-line interchange, shed, works, car park |
| Kirkby Thorpe | 2.4 | — | Village halt |
| Lowerdale | 4.6 | Yes | Signal box and water column |
| Brackenby | 7.1 | Buildable | Beyond the twelve-arch Brackenby Viaduct |
| Fellside | 9.0 | Yes | Foot of the 1 in 60 climb |
| Highmoor Summit | 11.8 | Buildable | Summit, just beyond Highmoor Tunnel |
| Moorend | 14.0 | Yes (2 trains) | Moorland terminus by Highmoor Reservoir |

The **Line Map** app draws the railway with the River Raven, the moors,
viaduct, tunnel and the main line. Press play to watch the planned
timetable (or the last day you ran) with the trains moving along the line.

## How to Play

Each turn is one week. Plan the weekend in the **Timetable** app, then press
**Run the Weekend**. The weekend plays out live on the **Line Map**, all its
days together in the time of one, at the speed you pick there (6 minutes a
second by default, from 1 to 60), and the button
stays locked until the last train is home. Meanwhile the rest of the game is
open: book future events, buy stock, recruit volunteers or plan next week's
timetable. Locos and coaches out on the line can't be sold or sent to the
works, and the takings and the week report arrive when the weekend ends.

1. **Timetable.** Every train is a round trip from Ravensgill Junction to
   Moorend and back, about two hours with turn-rounds. A *diagram* is one
   locomotive (and its carriage set) with a list of departure times. The
   quick-pattern buttons build an even-interval service for you, testing
   different intervals in the simulator and keeping the one that gets the
   most trains round on time. Press **Double-head** on a diagram to add a
   pilot engine: the two engines' loads add together (a 4-coach and a 5-coach
   engine can take 9 coaches up the bank), with a small draw bonus and a
   double-header counting as two engines for galas. The costs: two crews, both
   engines' coal and wear, and the slower engine's pace.
   The Timetable app opens with the **printed timetable**: Up and Down tables,
   a column per train and a row per station, in the style of a heritage
   railway's leaflet. Times come from the simulated day, so trains held at
   loops show their real times, and `|` marks a train running through.
   Each train working has a row of **station toggles**: untick a station to
   run through it, or untick the ends to make a **shuttle** (e.g.
   Fellside–Moorend). A shuttle must start and turn back at a passing loop,
   runs out empty from the shed in the morning and back at night, and sells
   cheaper tickets for its shorter ride. Each station has its own queue of
   passengers, so a station nobody calls at earns nothing.
2. **Single-line working.** Only one train may be on each single-line
   section, and trains can pass only at the loops. Each loop has one road for
   each direction, so the line never locks solid, but too many trains for
   too few loops means trains are held and run late. The **train graph**
   (time across, distance up) shows every crossing. The steep
   Fellside–Moorend section is the bottleneck; a loop at Highmoor Summit
   lets a gala run far more trains.
3. **Passengers** arrive through the day and take the next train within two
   hours. Leave long gaps and they go elsewhere; run full trains and they're
   turned away. Steam draws more than diesel, and both more than a DMU.
4. **Events** are booked in the **Events Calendar**, ideally four weeks ahead
   for full publicity. A quarter of the cost is paid as a deposit.
5. **Volunteers** crew every train. If a day needs more than turn up, it
   can't run. Busy weekends tire them; quiet weeks and socials restore
   morale.
6. **Works.** Condition falls with every mile and worn locos fail at Moorend,
   blocking the line and refunding fares. Do heavy overhauls in winter.

**Goal:** a net worth of **£500,000** and a reputation of **110**. Steady
normal service alone won't get you there: reputation fades unless you run
galas and fill trains. Finish two weeks running overdrawn and the railway
closes.

## Events

| Event | Season | Needs | Effect |
|-------|--------|-------|--------|
| Steam Gala | Spring–Autumn | 3+ steam locos timetabled | Big crowds, higher fares; guest engines add draw; an intensive service pays |
| Diesel Gala | Spring–Autumn | 3+ diesels timetabled | As above, for the diesel crowd |
| Beer &amp; Music Festival | Spring–Autumn | 14 extra volunteers | Crowds peak in the evening; big bar takings |
| 1940s Wartime Weekend | Spring–Autumn | — | Steam and Gresley teak coaches add to the draw |
| Santa Specials | December weekends | — | The winter goldmine |
| Visiting Engine Running Days | Any time | — | Ordinary running days with visiting stock; you choose 1, 2 or (school holidays) 4 days |

## Visiting Stock

Any event can bring **visiting engines** (up to three) and **visiting
carriages** (up to two) on hire for that week. Each draws extra visitors.

- **Steam:** *Flying Scotsman*, *Union of South Africa*, *Tornado*, *Duchess of
  Sutherland*, *Royal Scot*, *Green Arrow*, *Bahamas*, *Braunton*, *Duke of
  Gloucester*, *The Great Marquess*, 9F, Q6, Ivatt 'Flying Pig', J72.
- **Diesel:** Deltic, 'Western', 'Hoover', 'Hymek', Class 40 *Andania*, Class
  56, 60, 33, 47, and pairs of Class 20s and 26s.
- **Carriages:** a Pullman train, Gresley teak, a Mk1 9-coach rake,
  observation saloons, Victorian four-wheelers and a Royal Mail TPO set.

## Motive Power and Stock

| Locomotive | Type | Draw | Max load on the bank |
|------------|------|------|----------------------|
| Austerity 0-6-0ST | Steam | 1.02× | 5 coaches |
| GWR 57xx Pannier Tank | Steam | 1.06× | 5 |
| LMS Ivatt 2MT 2-6-2T | Steam | 1.08× | 6 |
| NER J27 0-6-0 | Steam | 1.16× | 6 |
| BR Standard 4MT 2-6-4T | Steam | 1.18× | 7 |
| LMS 8F 2-8-0 | Steam | 1.20× | 9 |
| LNER B1 4-6-0 | Steam | 1.28× | 8 |
| LMS 'Black Five' | Steam | 1.30× | 8 |
| Class 14 'Teddy Bear' | Diesel | 1.00× | 5 |
| Class 25 | Diesel | 1.05× | 6 |
| Class 31 | Diesel | 1.07× | 7 |
| Class 37 | Diesel | 1.16× | 9 |
| Class 45 'Peak' | Diesel | 1.24× | 9 |
| Class 40 'Whistler' | Diesel | 1.27× | 9 |
| Class 101 (2-car) | DMU | 0.92× | 140 seats |
| Class 110 'Calder Valley' (3-car) | DMU | 0.98× | 210 seats |

Also for sale: Hunslet 'Jessie', LMS 'Jinty', L&Y Class 27, BR Standard 2MT
and 5MT, LMS 'Crab', LNER K1 and USATC S160 steam; Class 08, 20, 24, 26, 33,
46 and 47 diesels; Class 108, 104 and 144 'Pacer' units and a Wickham railbus.

Carriage sets: Mk1 4-, 6- and 8-coach, Mk2 7-coach, Mk1 with restaurant car,
Gresley teak, LNER Thompson, Victorian six-wheelers, an observation car set,
a Pullman dining set, and brake-van rides.

## Infrastructure

Passing loops at Brackenby and Highmoor Summit, a refreshment room and shop,
a car park extension, a Moorend turntable, a carriage shed and a loco works
extension.

## Raspberry Pi 5

Open the Pages link in Chromium on the Pi, or copy `index.html` across and
open it as a file. The management game is SVG and DOM only. The yard uses
WebGL, but only plain coloured boxes with no textures, and the picture is
capped at 1.5× resolution, so the Pi 5's GPU handles it easily. If WebGL is
turned off, the shed staff simply marshal the train for you.
