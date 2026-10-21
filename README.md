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

## Saving and Carrying On Elsewhere

Press **💾 Save / Load** for a **save link**: the whole railway is compressed
into the link itself (in the `#save=` part, which never leaves your browser,
so nothing is uploaded). **Copy** it, **email it to yourself**, or **download**
it as a small text file. Opening the link on any device (another computer, a
phone, the Pi) asks whether to load that railway. You can also paste a link or
open a save file from the same dialog.

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

The **Line Map** tab draws the railway with the River Raven, the moors,
viaduct, tunnel and the main line. Press play to watch the planned
timetable (or the last day you ran) with the trains moving along the line.

## How to Play

Each turn is one week. Plan the weekend on the **Timetable** tab, then press
**Run the Weekend**.

1. **Timetable.** Every train is a round trip from Ravensgill Junction to
   Moorend and back, about two hours with turn-rounds. A *diagram* is one
   locomotive (and its carriage set) with a list of departure times. The
   quick-pattern buttons build an even-interval service for you, testing
   different intervals in the simulator and keeping the one that gets the
   most trains round on time.
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
4. **Events** are booked on the **Events Calendar**, ideally four weeks ahead
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
open it as a file. Graphics are SVG and DOM only, with no WebGL, so they run
smoothly on the Pi.
