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
a DMU's driving seat) for the rest of its day, or just one way.

The 3D line is built from the map's own alignment: all seven stations with
their platforms and nameboards, the passing loops, Brackenby Viaduct's twelve
arches over the River Raven, Highmoor Tunnel through the fell (a stone portal across the end of each cutting, as high as the hill behind it), the climb to the
summit, the B6481 and Highmoor Reservoir. Along it:

- **The River Raven** only ever runs downhill. Where the land rises across its
  course it has cut a channel, and where its bed drops away it falls. Raven
  Force and a second fall below it pour into rocky pools, with the water
  animated as it tumbles. The B6481 runs along the river on a walled causeway.
- **Brackenby Viaduct** stands on embankments whose sides fall away and narrow
  to the abutments. The telegraph poles leave the line there and stride down
  across the valley floor. Highmoor Tunnel's hill runs unbroken over the bore
  right up to each portal face.

- **Stations:** booking halls with windows, doors and chimneys, canopies on
  iron columns, white palings, benches, flower tubs, milk churns, barrows and
  clocks; signal boxes, footbridges and waiting shelters at the loops; water
  columns; car parks full of cars; Ravensgill's engine shed and works (the same
  yard you shunt in), and a siding of wagons.
- **Places to eat and drink:** the Thorpe Arms by Kirkby Thorpe crossing, the
  Goods Shed Tea Room at Lowerdale, the Viaduct Inn at Brackenby, the Junction
  Inn and the Station Buffet at Ravensgill, the Fellside Café, the Summit Tea
  Hut and the Reservoir Café, each with its sign.
- **Towns, villages and woods:** Ravensgill is a small town round its
  junction, and Lowerdale, Fellside and Moorend are villages round their
  stations: terraces of stone cottages, houses with garden walls, churches
  with towers, farms with barns and bales, and lanes down to every station.
  The halts (Kirkby Thorpe, Brackenby and Highmoor Summit) stand on their own
  in the woods, with a conifer plantation up at the summit.
- **Curves before the stations:** between stations the line swings out round
  a bend and back, with a wood on the inside of the curve, so the next station
  only comes into sight as you round the last bend.
- **Crossings and bridges:** level crossings with white gates, red targets and
  lamps, keepers' cottages and whistle boards; farm crossings; stone arched
  overbridges with their approach ramps.
- **The lineside:** telegraph poles with their wires, quarter-mile posts,
  platelayers' huts, stone walls, hedgerows and hedgerow trees, sheep on the
  fells and cattle in the pastures. It is squeezed 3.8 times (about
6 km end to end, with the stations 0.8 to 1.3 km apart), so each way takes
about a quarter of an hour. The clock runs a little over three times as fast
while you're moving, so the booked timetable still fits at line speed, and
faster while you stand at a station with no other train about, so the dwells
and layovers don't drag (wait them out altogether with ⏩).
In the Drive a Service picker choose **the rest of its day** (from any of its
trips), or **one way**: out to Moorend, or back from Moorend to Ravensgill.
Each engine's best speed on each section is the one the timetable was worked
out from, for its load, its pace and the climb; downhill the train will run
away with you if you let it.

The throttle and the brake are separate handles, as in a real cab, and each
stays where you leave it: open the throttle to get away, shut it to coast, put
the brake on to slow down and take it off again before you start away. The
driving panel shows both, and warns you if you're working the engine against
the brake.

**The weekend runs behind the drive.** When you take the cab the weekend starts
at once: the other trains you meet are the weekend's own trains, the panel
counts the weekend's passengers as you go, and when you climb down (journey
done or handed over) the laptop map carries on from the cab's clock rather
than starting the day again. Your own train never fails under you on the day
you drive it.

| Control | Keys / on screen |
|---------|------------------|
| Throttle (regulator on steam) | W / S or ↑ / ↓, or hold Throttle ▲ / ▼ |
| Train brake | E (on) / D (off), or PgDn / PgUp, or hold Brake on ▲ / Brake off ▼ |
| Emergency brake | Space, or hold ■ Emergency |
| Look round | ← / →, or drag |
| Change view | C, or 🎥 View: leaning out of the cab, sitting in the driver's seat (an engine), or the lineside chase |
| Wait for the right away | T, or ⏩ Wait |
| Hand over | H or Esc, or ✋ Hand over |
| Whistle or horn | Q (hold), or hold 📯 |
| Sound on or off | M, or 🔊 Sound |
| Uncouple (running round) | U, or 🔗 Uncouple |
| Reverser (running round) | R, or ⇄ Reverser |
| Points (running round) | P, or 🔀 Points: the set nearer the engine |

Stop with the front of the train near the stop board at each booked call; the
passengers board, and you get the right away at the booked time. At the loops
the starter signal stays at danger until then, and while another train is in
the section ahead. The rest of the day's timetabled trains run too, in full view: in the
platforms, out on the line, and crossing you at the loops on the loop road. They
keep to their booked times, but each waits at its loop while you hold the single
line section it wants, so if you run late they're held for you (and run late
themselves). You hear them rumble past, and whistle or sound their horns as they
leave a station near you.

**Running round.** Wherever your train turns back (both termini, the far end of
a shuttle, and the end of a one-way trip out) you run the engine round it
yourself:

1. Uncouple (U).
2. Draw forward over the points at that end of the loop. At Ravensgill and
   Moorend the loop rejoins the main line beyond the platform, and a short
   headshunt runs on to the buffer stops. Stop clear of the points.
3. Set the points for the loop (P), reverse (R) and run back along the loop
   past your coaches.
4. Set the far points for the loop before you run out over them. Running
   through points set against you counts against you.
5. Once you're clear of the far points, set them back to the main line,
   reverse, and buffer up gently (under 2 mph) to the other end of the coaches
   to couple on.

A light engine is held to 15 mph. Each set of points has a ground frame and a
white point indicator beside the line. The engines face up the line: they
aren't turned, so trains coming down from Moorend run tender first (bunker
first on a tank engine). The timetabled trains you meet do the same: once
they've stood at Moorend long enough to run round, they come down tender
first. With the Moorend turntable, steam engines are turned and run chimney
first both ways. A DMU simply changes ends.

Arrive on time on average, with no signal passed at
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

**One Ravensgill for shunting and driving.** The yard is Ravensgill station on
the line itself: the Platform road is the main line out of the terminus, the
headshunt runs out along it, and the two shed roads, the engine shed, the water
tower, ground frame and signal box are built into the line's scenery. So the
shunting view shows the town, the station building and the hills beyond, and
when you drive a service you pull out past the same shed. While you drive, every
engine of yours not out on the line that day stands on the shed roads, and you
see them through the open doors as you pass. The shed roads branch off beyond
the end of the platforms and run in behind the loop platform, so neither
platform stands in their way.

**The works.** A lean-to extension along the side of the shed, with its own
road off Shed road 2, its own door, roof lights, a travelling crane over the
road and benches along the wall, is where engines in the works stand, in both
the yard and the drive. An engine in for repairs or an overhaul is shown
partly taken apart: a steam engine is off its wheels and up on timber stands
with its boiler, smokebox and tanks lifted off the frames, and the boiler and
smokebox laid on trestles beside it; a diesel is off its bogies on stands with
its roof sections lifted off and laid on the floor, with a spare wheelset
beside it; a DMU is off its bogies with its roof off. One being repainted
stands there whole. Engines in the works no longer turn up on the shed roads to
be shunted round.

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
warning panels and livery bands, with the Class 20 and 26 pairs as two locos.
Each class's cab end has its own shape, from photographs: the Sulzer Type 2s'
well-rounded corners (a gangway door on the 24, the headcode box between the
screens on the 25), the BRCW Type 2's sealed gangway and deep roof curve, the
Class 31's leaning front under its roof dome, the Crompton's flat slab front
with valance and jumpers, the Class 47's chamfered corners and steeply raked
screens, the Class 50's square front with the headcode box above the screens,
the boxy cut-off-cornered Class 56 with its plough and headlight, the Class
60's long raked face, the Hymek's wrap-round screens and the curved-all-round
Western;
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

## Running Numbers

Every engine you buy gets its own running number, drawn from the real number
series of its class: a pannier tank is one of the 57xx family (5700–5799,
7700–7799, 8700–8799, 3600–3799, 4600–4699 or 9600–9799), a Black Five one of
44658–45499, a Class 37 one of 37001–37308, and so on, and never one you
already own. The number is painted on the engine itself: on the cab side (a
cast brass plate on a Great Western engine) and on the smokebox number plate
of a BR or LMS steam engine, under the cab windows of a diesel (or large on the
bodyside behind a wrap-round yellow cab), and low on the bodyside by the cab of
a DMU.

The number follows the era of the livery, so a repaint renumbers the engine as
it would have been at the time: an Ivatt tank is 41241 in BR lined black and
1241 in LMS black; a B1 is 61264 in BR black and 1264 in LNER apple green; a
pannier sold to London Transport becomes an L number; a J27 carries its NER
number in NER black; a diesel carries its D number in BR green and its TOPS
number from blue onwards (D5209 and 25059); a DMU car keeps its region letter
(E, M or Sc) until the prefixes were dropped. The repaint window shows the
number each livery would bring. The two engines you start with keep their
famous numbers (41241 and 25059) until you repaint them, and visiting engines
carry their own.

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
   Wear is gentle enough that a running repair every few weekends keeps an
   engine going, but breakdowns still happen at random.
7. **Boiler tickets.** A steam engine may only run while its boiler
   certificate is in date, and each certificate lasts a year. Renewing it
   takes a full overhaul in the Works, which also leaves the engine as new.
   Size and complexity set the bill: tender engines and eight-coupled
   engines take longest.

   | Engine | Overhaul |
   |---|---|
   | Hunslet 0-6-0ST | 5 weeks, about £6,900 |
   | Ivatt 2MT 2-6-2T | 7 weeks, about £11,200 |
   | J27 0-6-0 | 10 weeks, about £15,800 |
   | Black Five 4-6-0 / 8F 2-8-0 | 13 weeks, about £26,000–£29,000 |

   The Works upgrade takes 30% off and a week out. The Fleet shows each
   engine's ticket; the week report warns 12 and 4 weeks ahead. The Ivatt's
   first ticket runs out at the start of your second season, so give it its
   overhaul over the winter. Engines whose ticket would expire while away
   can't be hired out.

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
- **From other heritage lines:** every steam and diesel class you can buy in
  the shop can also be hired for an event, on loan from another line: a Black
  Five, a B1, an 8F, a pannier, a Class 37 or a 'Peak', and the rest. Each comes
  with a number of its own from its class's series (so it never clashes with
  your own engine of the same class), a hire fee of about 7% of its price and a
  crowd pull from its draw. They're listed under the star engines when you book.
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
