<p align="center"><img src="https://user-images.githubusercontent.com/67427045/226212356-eefd0fe9-49d8-40ac-b290-3c3e62376a7c.png" />
</p>
<br><br><br>

# Distributed Maptile Server
A distributed, serverless, global, maptile server, for free access to a map tile API for Your next location based application.
<br><br><br>

# Tile pipeline centralised (for your own (d)app) (working!)

1. One click import of OpenStreetMap with textured buildings, forests, satellite imagery, terrain for Blender https://github.com/ohadmanor/blender-osm-large-scale-creator
2. Style tiles to Google Maps style eventually (better perception and in turn acception of your app. automated scripts already existing, i am still searching for the name)
3. Upload tiles to map tile server
- classic centralized entity (10CPU 20$/month, unlimited bandwidth, https://www.strato.de/server/linux-vserver/ This one is fast, but speed is not even critically neccessary, the logic of caching tiles in your app saves a lot of bandwidth on both your back-end and client-side)

# Tile pipeline the decentralized way (in progress)
##### (needs only a minor modification to the serviceworker of the METAVERSE-DAO | CLOUD ATLAS repository, just had not the time yet)

- Thanks to the integration of GunJS into the service-worker's cache (currently in progress), every user of METAVERSE-DAO | CLOUD ATLAS, and consequently every user of your app, can now automatically share and distribute tiles with the entire community. As tiles fetched by the Cesium globe are automatically cached by the service-worker by default, this creates a distributed map-tile peer-to-peer (P2P) machine that allows each user to distribute their tiles to other network users and vice versa.
- This paves the way for a more collaborative and interconnected experience on mapping data. It presents a unique opportunity to invest our time and energy in improving the collaborative OpenStreetMap project, rather than scattering our efforts among different projects over which we have little influence. Let's embrace this new way of working together and unlock the potential of collaborative mapping! At the end of the day, this approach empowers the people to own the maps of their world.

btw: volunteers could add support machines, by installing a free PC background app and/or renting one of these 20$ servers above and/or for instance via a 1-click install on Digital Ocean)
