# Day 4 – Clusters

**#30DayMapChallenge 2026**

Interactive 3D globe of the Starlink constellation.  
~3,268 satellites shown as elevated points; switch to hexbin clusters to see density hotspots in low Earth orbit (~550 km).

## Features
- Points view (color by version or orbital height)
- Cluster / hexbin mode with adjustable resolution
- Auto-rotation, hover tooltips, live stats

## Run it
Open `starlink_clusters.html` in any modern browser (or host it on GitHub Pages / Netlify).

## Data
Snapshot positions from the supplied Starlink CSV (valid lat/lon/height records only).  
Not live-propagated orbits.

## Tech
[globe.gl](https://globe.gl) + Three.js

