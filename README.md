# Jeepney Ride

Explore the Philippines by jeepney before the trip: open the map, tap any attraction and **🚙 Ride here** – in real Google Street View or Google's 3D world. Start points: **Manila (Intramuros)**, **Urdaneta, Pangasinan**, and **Iža, Slovakia**.

**Play:** https://alexcalex1.github.io/jeepney-ride/

- ▲ GAS / ▼ BRAKE change gear, ◀ ▶ are turn signals (the jeepney turns at the next junction on that side), ↶ U-turn, tap the steering wheel to honk.
- **Things to do:** beaches 🏖️, waterfalls 💧, hiking 🥾, sights ⭐, islands 🏝️, viewpoints 🌄 (+ museums, diving, food, hotels) from Google Places as map markers. Tap one for **📷 Photos** or **🚙 Ride here**. While riding, a card pops up when you pass one — tap it to stop and see photos. Needs **Places API (New)** on the key.
- **🧳 My trip:** tap ☆ Trip on any place, plan it by day, then open it as a **route in Google Maps**, make a **Google Maps list link** (Maps Tools Resolution API – enable *Maps Experience agent tools*), download a **.kml for Google My Maps** / .csv, or **share** the plan.
- 🎥 / 🚐 switches between the **chase camera** (3D jeepney seen from behind) and the **cab view**.
- Tap the map to see all Street View roads (blue) and where you've driven (yellow), and to jump to any road.

## API key

The game needs your own Google Maps JavaScript API key. It is typed into the page and stored only in your browser — it is not in this repo.
Restrict the key to the website `https://alexcalex1.github.io/*` and to the Maps JavaScript API.
Each press of **Start** uses one Dynamic Street View session.

**🌍 3D world (beta):** ☰ → 3D world drives smoothly through Google's Photorealistic 3D Tiles along the same real roads. Needs the **Map Tiles API** enabled for the key. Where Google has no 3D model you'll see flat satellite ground.

**Black screen instead of streets?** Open ☰ and switch on **📷 Photo mode**. It shows Street View as plain pictures and needs the **Street View Static API** enabled for the same key (one image per hop).
