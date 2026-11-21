# Jeepney Ride

Drive a jeepney through real Google Street View — start in **Urdaneta, Pangasinan** and find every road to the Lingayen Gulf beaches, or switch to **Iža, Slovakia** on the Danube.

**Play:** https://alexcalex1.github.io/jeepney-ride/

- ▲ GAS / ▼ BRAKE change gear, ◀ ▶ are turn signals (the jeepney turns at the next junction on that side), ↶ U-turn, tap the steering wheel to honk.
- Pasahero mode: passengers wave, stop to pick them up, stop again on “Para po!” to collect the fare.
- 🎥 / 🚐 switches between the **chase camera** (3D jeepney seen from behind) and the **cab view**.
- Tap the map to see all Street View roads (blue) and where you've driven (yellow), and to jump to any road.

## API key

The game needs your own Google Maps JavaScript API key. It is typed into the page and stored only in your browser — it is not in this repo.
Restrict the key to the website `https://alexcalex1.github.io/*` and to the Maps JavaScript API.
Each press of **Start** uses one Dynamic Street View session.

**🌍 3D world (beta):** ☰ → 3D world drives smoothly through Google's Photorealistic 3D Tiles along the same real roads. Needs the **Map Tiles API** enabled for the key. Where Google has no 3D model you'll see flat satellite ground.

**Black screen instead of streets?** Open ☰ and switch on **📷 Photo mode**. It shows Street View as plain pictures and needs the **Street View Static API** enabled for the same key (one image per hop).
