# The Corrib 🍺

A browser-based Irish pub bartending simulation by [Adam Lozo](https://adamlozo-landing.onrender.com). You're behind the bar at The Corrib — pour proper pints of Guinness, keep the regulars happy, and try not to get fired. One HTML file, no dependencies.

## Play

Open `index.html` in any modern browser, give your bartender a name (John, Pete, Lindsay, Maryann — or your own), and start the shift.

## How it works

**The pour** is the heart of it, mimicking the real two-part Guinness ritual:

1. **First pour** — hold the tap and ease off at the ¾ line. Too shallow or overfilled hurts the pint.
2. **The settle** — wait. The surge visibly cascades and clears over a few real seconds. Pulling the tap early is the classic mistake, and the pint never forgives you.
3. **Top-off** — slow pour to just proud of the rim for a proper creamy head.

Every pint is graded **Perfect / Good / Rushed / Sloppy**, and the grade drives tips and reputation.

**The bar** runs on simple clicks under growing pressure:

- Customers cycle through arriving, ordering drinks (and sometimes food), drinking, refills, and the bill — each with a visible **patience meter** that drains while they wait.
- Food orders go to the kitchen hatch; grab the plate when it's up and get it to the right punter.
- Every departing customer leaves a **mess** — wipe it, or it sours the next punter, drains patience faster, and trims tips.
- Every pint raises a **drunkenness meter**. Past the threshold customers turn rowdy, and two rowdies on adjacent stools start a fight fuse — **calm** one down or **cut them off** before glasses fly. Over-serving a drunk costs you the tip and the owner's goodwill.

**The stakes:** tips scale with pour quality, speed, and judgment. Reputation builds from happy customers and drives how fast new ones arrive. The shift never ends — difficulty climbs forever — and the **owner's confidence** falls with every walk-out, fight, filthy stretch of bar, and stingy tip. When it hits zero, you're handed your apron: final tips, pints poured by grade, customers served, and how long you lasted.

## Development

Built as a single self-contained `index.html`. The commit history tells the story feature by feature: scaffold → core customer loop → the Guinness pour → food & cleanliness → drunkenness & fights → endless mode & the sack.
