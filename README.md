# MAPTILE-DSERVER
A distributed, global tile server, for free access to a map tile API for Your next location based application https://maptile.io
<br><br><br>

# Tile pipeline

1. Create tiles from sourcemaps https://github.com/worldpeaceenginelabs/blender-osm-large-scale-creator
2. Style tiles to Google Maps style (automated script already existing, i am searching for the name)
3. Upload tiles to map tile server
- first classic centralized entity (10CPU 20$/month, unlimited bandwidth, fast but speed is not even critical neccessary)(You could do it from a Notebook even)
- feed the "p2p upload"
- Later with more nodes, map updates get injected via p2p only and volunteers having a relay app installed for support, PC background)
4. Upload the tiles to P2P Network(s) (if your app's (with CesiumJS) back-end caches content p2p, tiles become distributed automatically)
