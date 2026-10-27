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

## Drive a Service

When you press **Run the Weekend**, you can also take a train out on the line
yourself. Pick any train in the timetable and the trip to start from, and drive
it from the cab (leaning out of the cab side of a steam or diesel engine, or from
a DMU's driving seat) for the rest of its day.

The 3D line is built from the map's own alignment: all seven stations with
their platforms and nameboards, the passing loops, Brackenby Viaduct's twelve
arches over the River Raven, Highmoor Tunnel through the fell, the climb to the
summit, the B6481 and Highmoor Reservoir. Along it:

- **Stations:** booking halls with windows, doors and chimneys, canopies on
  iron columns, white palings, benches, flower tubs, milk churns, barrows and
  clocks; signal boxes, footbridges and waiting shelters at the loops; water
  columns; car parks full of cars; Ravensgill's engine shed, coaling stage and
  a siding of wagons.
- **Places to eat and drink:** the Thorpe Arms by Kirkby Thorpe crossing, the
  Goods Shed Tea Room at Lowerdale, the Viaduct Inn at Brackenby, the Junction
  Inn and the Station Buffet at Ravensgill, the Fellside Café, the Summit Tea
  Hut and the Reservoir Café, each with its sign.
- **Villages:** terraces of stone cottages, houses with garden walls,
  churches with towers, farms with barns and bales, and lanes down to every
  station.
- **Crossings and bridges:** level crossings with white gates, red targets and
  lamps, keepers' cottages and whistle boards; farm crossings; stone arched
  overbridges with their approach ramps.
- **The lineside:** telegraph poles with their wires, quarter-mile posts,
  platelayers' huts, stone walls, hedgerows and hedgerow trees, sheep on the
  fells and cattle in the pastures. It is squeezed five times (about
4.5 km end to end, with the stations 600 m to 1 km apart) and the clock runs
four times as fast, so a round trip takes about half an hour instead of two
(less if you wait out the layovers with ⏩), and the booked timetable still fits.
Each engine's best speed on each section is the one the timetable was worked
out from, for its load, its pace and the climb; downhill the train will run
away with you if you let it.

| Control | Keys / on screen |
|---------|------------------|
| Power and brake lever | ↑ / ↓ or W / S, or hold Power ▲ / ▼ Brake |
| Emergency brake | Space, or hold ■ Emergency |
| Look round | ← / → or A / D, or drag |
| Change view | C, or 🎥 View (cab or lineside chase) |
| Wait for the right away | T, or ⏩ Wait |
| Hand over | H or Esc, or ✋ Hand over |
| Whistle or horn | Q (hold), or hold 📯 |
| Sound on or off | M, or 🔊 Sound |

Stop with the front of the train near the stop board at each booked call; the
passengers board, and you get the right away at the booked time. At the loops
the starter signal stays at danger until then, and while another train is in
the section ahead. The rest of the day's timetabled trains run too, in full view: in the
platforms, out on the line, and crossing you at the loops on the loop road. They
keep to their booked times, but each waits at its loop while you hold the single
line section it wants, so if you run late they're held for you (and run late
themselves). You hear them rumble past, and whistle or sound their horns as they
leave a station near you. At the end of the line the engine runs round its train (or
you change ends of a DMU). Arrive on time on average, with no signal passed at
danger, no overruns and no long spells over the 25 mph limit, for ★★★ (+2
reputation). Hand over at any time and another driver finishes the day.

## Coaches and Their Liveries

Every carriage set is built coach by coach from its real make-up, as carefully as
the engines: BR Mk1 brake compartments, compartments, opens, composites,
restaurant buffets and an observation car, each with its own window and door
layout, aluminium window frames with sliding toplights, slam doors with
droplights, gangways, torpedo roof vents, battery boxes and vacuum cylinders on
BR1 bogies; Mk2s with their smoother roof and big windows on B4 bogies;
Gresley teak with its panel joints on double-bolster bogies; Thompson
steel-panelled coaches with their round lavatory windows; Pullmans with their
table lamps in the windows; Victorian six-wheelers and four-wheelers with a door
to every compartment and oil-lamp pots on the roof; BR goods brake vans with
verandas, duckets and the stove pipe; and the Royal Mail TPO with its pick-up
net.

Repaint a set in the **Ravensgill Shed** (the carriage volunteers, two weekends)
or at the **Works** (a week, with a works finish), in the liveries that stock
really carried: BR maroon, crimson and cream ("blood and custard"), Western
Region chocolate and cream, Southern Region green and blue and grey for the
Mk1s; blue and grey, InterCity, Network SouthEast and Regional Railways for the
Mk2s; LNER teak and its BR successors for the Gresley and Thompson stock; NER
crimson lake, Midland crimson lake, L&Y brown, GNR teak and GWR chocolate and
cream for the Victorian set; bauxite, BR grey and LMS grey for the brake vans.
A 3D preview shows the set in each one, and a well-loved livery draws a few
more passengers. Visiting sets come in their owners' colours.

## Sound

Everything you hear is synthesised in the browser with the Web Audio API, from
published figures rather than recordings:

- **Steam:** an exhaust beat for every cylinder stroke (four per turn of the
  driving wheels for two- and four-cylinder engines, six for three-cylinder ones,
  with the Gresley engines' uneven middle-cylinder beat), sharp and loud at long
  cut-off when starting, softer and faster as the engine is linked up, blurring
  into a roar at speed. Cylinder drain cocks hiss for the first few turns after a
  stand, the blower roars at a stand, and the safety valves lift if you wait long
  enough. Whistles by company: the GWR's high note, the deep Stanier hooter, the
  A4's three-note chime, LNER, Southern, BR Standard, NER, L&Y and the little
  industrial tanks.
- **Diesels:** each engine's real cylinder count and idle-to-full rpm (the
  Class 08's slow chug, the English Electric "whistlers" with their turbos, the
  Sulzers, the two buzzing Deltic engines beating against each other, the
  Western's Maybachs), and two-tone horns, high then low.
- **DMUs:** two underfloor engines revving through a four-speed gearbox, with
  the drop in revs and the clunk at each change.
- **On the move:** the wheels over every 60 ft rail joint (the "diddly-dum"
  of each bogie), rumble that rises with speed, flange squeal on curves, the
  brakes going on and the blocks squealing as you stop, and the tunnel's echo.
- **At stations:** doors slamming as passengers board, then the guard's whistle
  for the right away. In the yard: buffers and couplings clanking, and your
  footsteps on the ballast.

Every engine has its own voice on top of its class: how sharp or soft its
exhaust is (the Caprotti Duke of Gloucester's clipped beat, the soft roar of a
double chimney, the woofly J27 and Q6, the Austerity's harsh bark), how uneven
its rhythm, its own whistle note (Flying Scotsman's bell whistle, the J72's
small high one, the S160's American chime), and extras: the GWR pannier's
vacuum pump, the S160's Westinghouse pump panting at a stand, rods knocking on
the 8F, Q6 and Austerity when coasting, the Crab's long cylinder-cock roar, the
injector singing and the fireman's shovel. Diesels too: the Class 40's turbos
whistling even at idle, the Class 50's "hoover", the 56's grind, the 60's turbo
scream, the Western's transmission whine, the Hymek's Mekydro gear steps and
the 08's single horn and gear whine. The Pacer has one long hydraulic rise and
no gear changes, and its four wheels thump over every joint.

The pitches of whistles and horns are estimates from descriptions of them,
since no measured figures are published; the beat counts and engine speeds are
the real ones.

## The Yard: Drive the Shunter

When you press **Run the Weekend** you're offered the chance to marshal the
first train yourself. Say yes and the laptop folds away: you're in the cab of
the Class 08 shunter in Ravensgill yard, in first person (a small built-in
WebGL renderer, so it still works offline).

The coaches are already formed up on the Platform road. The job is to fetch
the right engine from the **engine shed**: a brick shed with two roads, holding
the train engine (and the pilot, for a double-header) plus the rest of the
fleet, every engine standing chimney or nose towards the shunter. Set the
three-way point for the right shed road, buffer up to the engine, draw it out
onto the headshunt, set the road for the Platform road and buffer it up to the
coaches, then uncouple.

Every locomotive class is modelled individually, checked against photographs
of the real engines and their published dimensions (cylinders and panels as well
as boxes): steam engines from their real wheel arrangement, wheel diameter,
length, boiler pitch, taper or parallel boiler, Belpaire or wide firebox,
running plate height, inside or outside cylinders with Walschaerts or Caprotti
valve gear, spoked wheels with balance weights, cab and tender type, chimney,
dome, smoke deflectors and livery (the A4's wedge front and the Bulleid casing
with BFB wheels are modelled too); diesels from their real height and body
style (cab ends with raked windscreens, noses, hood and single cab, the
Western), bogies with axleboxes and springs (Bo-Bo, Co-Co, A1A, 1Co-Co1,
coupled rods), headcode boxes, discs or roof domes, grilles, cab doors,
warning panels and livery bands, with the Class 20 and 26 pairs as two locos;
the visiting engines from their published dimensions and current liveries (the A3 and V2 banjo domes, Gresley corridor tenders, the 9F's wheel spacing and high firebox, real bogie and trailing wheel sizes; the Deltic's white cab band and nose headcode box, the Western's outside-frame bogies, brow and valance, the Class 40's nose doors, roof fans on the 50 and 56, the Hymek's window band, and the Class 20 and 26 pairs in two liveries); the Class 08 with its stepped radiator end, diagonal wasp stripes on the ends and buffer beams, outside coupling rods on quartered crankpins with balance weights, cab doors with steps, exhaust and horn (the yard shunter is the same model with its cab open, so you drive from the seat behind the control desk); DMUs from their car length and count, bogies or four-wheel axles, window and
door layout, underfloor engines and their front ends (Metro-Cammell, Derby
three-window, Calder Valley four-window, Pacer, Wickham railbus).

| Control | Keys / on screen |
|---------|------------------|
| Drive forward / back | ↑ / ↓ or W / S, or hold ▶ / ◀ |
| Brake | Space, or hold ■ |
| Look round | ← / → or A / D, or drag (double-click to recentre) |
| Points | 1 Platform road · 2 Shed road 1 · 3 Shed road 2 (locked while anything stands over them) |
| Uncouple | U uncouples the shunter, or click ✂ between any two vehicles |
| Change ends (DMU) | E, or click ⇄ Change ends (stopped only) |
| Climb down / climb in | F, or click the Climb button (stopped only; walk up to a cab door to climb in) |
| On foot | ↑ / ↓ walk, ← / → turn, hold Shift or ⚡ Sprint to run |

Buffer up at under 2 mph to couple (engines in the shed stand apart, so you
pick up only the one you buffer up to); faster
is a rough shunt, and over 5 mph is a crash. A mini-map and the job card show
progress. Finish quickly (under 6 minutes an engine) with no rough shunts for ★★★ (+2 reputation and a
morale boost), or leave the yard at any time and the shed staff finish the job.
Then the weekend runs as normal.

**Driving a DMU off shed.** If the timetable has DMU services, every unit in
it gets its own job too, offered alongside the shunter, and you drive it from
inside its cab: look out through the unit's own windscreen (two, three or
four windows, or the Pacer's one big screen) over the desk and gauges. Start
either in the unit's cab, facing the shed doors, or in the shunter on the
headshunt: drive that nearer the shed if you like, climb down (F) and walk or
sprint over to the unit and climb in at a cab door. Leave the shunter where it
won't block the unit's way out, or go back and move it. There's no coupling. Drive
it out onto the headshunt clear of the points, change ends (E) and walk
through to the other cab, set the points for the Platform road and draw up
gently to the STOP board near the end of the platform (within 10 m of the
buffer stops). Each car follows the track on its own, so a three-car 110
bends round the points. Under 4 minutes with no bumps earns ★★★ (6 minutes
if you start in the shunter). You can climb down and walk about in the yard
on the coach job too.

## Liveries

Every engine arrives in a real livery its class carried and can be repainted
in any other it really wore: BR lined black or green, BR express blue, LMS
crimson lake, LNER apple green and garter blue (with red wheels), GWR green,
SR malachite, NER and L&Y lined liveries, London Transport maroon, industrial
colours, and for the diesels BR green (plain, small panel or two-tone), BR blue,
large logo, Railfreight grey and triple grey, InterCity, Network SouthEast,
EWS, Loadhaul and DB, plus the Western's maroon, golden ochre and desert sand.
The diesel multiple units are modelled and liveried too (BR green with cat's
whiskers or a yellow panel, BR blue, blue and grey, white with a blue stripe,
Regional Railways, Network SouthEast, and for the Pacer West Yorkshire Metro,
Northern Spirit and Northern), and they stable in the engine shed with the rest
of the fleet. Visiting engines arrive in their owners' liveries, shown when you
book them.

Repaint in the **Ravensgill Shed** (the volunteer painting gang: cheaper, two
weeks) or at the **Works** (a contract paint shop: dearer, one week, with a
lined works finish that draws a little more). The repaint window shows the
engine in each livery in 3D. Historic and famous liveries bring more visitors,
and the yard shows each engine in its current colours.

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
