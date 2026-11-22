# Jeepney Ride

Plan a trip by exploring it first: find beaches, waterfalls, hikes, islands and sights on the map, look at their photos, save them to the days of your trip, and ride there in real Google Street View (or Google's 3D world). Regions: **Metro Manila**, **Pangasinan** and **Iža, Slovakia**, or start anywhere by searching a town.

**Open:** https://alexcalex1.github.io/jeepney-ride/

Three tabs:

- **Explore**: a full-screen map with search, category chips and a panel of place cards (swipe them, or switch to a list). After you move the map, **Search this area** appears. **Tap any road** to get its name and a **Drive** button that starts the ride right there. Tap a card, a pin or any Google place on the map to open its page.
- **Place page**: photos (swipe them, or tap to see them full screen) and **Ride there**, which starts about 700 m away and drives you in. **Look around** puts you right at the place. Tap a day to plan the place, and use **Directions** for real navigation in Google Maps. **Save in Maps** opens the place in Google Maps, where you can add it to your lists.
- **Ride**: press play, pick Slow / Cruise / Fast, and switch between Street View, Chase and 3D.
  - At a junction you get Left / Straight / Right buttons. The road toward your destination is highlighted and taken automatically after a short countdown.
  - A card pops up when you pass something worth seeing — tap **Stop & look**.
- **Trip**: your trip dates as a strip of days, numbered stops with distances (drag to reorder), **Route in Maps** for each day, and one **Share** button that shares the plan, opens a Google Maps list, or downloads a `.kml` (Google My Maps) or `.csv` file.

Tap the region name on the map for settings: region, sound, card photos, Street View roads, Photo mode and trip dates.

Keyboard: `Space` play/pause · `←` `↑` `→` pick a road · `↓` slower · `U` U-turn · `M` map / ride · `Esc` back.

## API key

The app needs your own Google Maps API key. You type it into the page and it is stored only in your browser — it is not in this repo.
Restrict the key to the website `https://alexcalex1.github.io/*`. Enable these APIs:

- **Maps JavaScript API**
- **Places API (New)**, for things to do, search and photos
- **Street View Static API**, for Photo mode
- **Map Tiles API**, for the 3D view

Street View is loaded once each time you open the app and ride. Each photo on a place card counts toward the Places photo quota; you can turn card photos off in settings.

**Black screen instead of streets?** In settings, turn on **Photo mode**. It shows Street View as plain pictures and needs the Street View Static API.
