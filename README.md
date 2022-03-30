# MAPTILE-DSERVER
A distributed, global tile server, for free access to a map tile API for Your next location based application https://maptile.io
<br><br><br>

# Tile pipeline

1. Create tiles from sourcemaps https://github.com/worldpeaceenginelabs/blender-osm-large-scale-creator
2. Style tiles to Google Maps style (automated script already existing, i am searching for the name)
3. Upload tiles to map tile server (classic centralized entity first, to feed the "4. p2p upload". Later, map updates via p2p only and volunteers having a relay app installed for support, PC background)
4. Upload the tiles to P2P Network(s) (if your app's (with CesiumJS) back-end caches content p2p, tiles become distributed automatically)
