#Discussion Post-mortem with Esri

- Viani
- Allen
- Smith
- Scott
- Lofgren
- Kiniry
- Brasseur
- French
- Berg

#Feedback @ Esri
- Description column to go along with the attributes - metadata about each field name. "Data dictionary"
- No control on the ODP charts (style, sort, formatting)
  - Number of records limitation - summary tables?
- How does this compare to others? What could we borrow from others?
  - We'll provide a shortlist
  - "You're already doing the 'fancy stuff'" from what I've seen
- Analytics within ODP or AGO?
  - "Interesting... don't know"
  - Geocortex has detailed analytics including geographic
- We have pre-set boundaries - a spatial query would be very helpfuls
  - Ex: Regional dataset filter (county, district, etc)
- Sorting datasets in AGO map - can't sort layers. Berg:
  - Tiled image service = basemap 
  - Dynamic map service - ArcServer - always underneath...
  - Feature services - Raw data (_url_/#) - always on top
- Services - when to restart/republish/re-add to map
  - Nothing should require re-add to map unless URL change
  - From Server - hit the live database so editing local data (even with local cache) - no restart
  - Cartographic changes (MXD changes) - require republish(Overwrite)
  - Next ArcServer - persistent layer IDs - reorder layers doesn't change URL

 
#Feedback @ VTrans
###French:
- "Overwhelmingly positive feedback from Open Data team and others @ Esri"
- "Sprint is brilliant - it's tough to get alignment when people are separate. I wish more customers would do it."
- Turner - head of open data team - loved it
- Sharing the documentation was very helpful helping us understand your target
- Persistence in the ODP is a problem - we're working on it
- Dataset attributes - using dataset aliases
- Scroll bars on the images - something to work on?
- ODP charts for metrics - how is that working for you?
- ODP link is small - could it be more prominent?
  - Link from the map/app
- Metadata - do you have "full" metadata? FGDC style?
  - Should we link to the metadata?
  - We'll link back to the business owners sites for methodology and metadata
  - Future AGOL/ODP will link back to original metadata for those who need it
- ~~Liked the top 10 maintenance activities~~
  - Could that be shared as a story map?
  - We're talking about that for future work - sharing upcoming projects
  - Actually meant the maintenance district static map - this could be the story map
- Contacts map could be more descriptive
  - "Search for an address"
- Promotions goal?
  - Agency rollout this week, get feedback, setup for the Legislature
  - "Leading the way with open data"
  - It's much easier for us - to share, publish, own, sustain
  - ODP allows us to establish how the data looks - make available vs field a custom request

###Berg
- ODP images scrollbars - override ODP CSS in the config page
  - Simple to fix by targeting the classes
- Informal API for ODP charting?
  - Not sure - using a couple different tools - ODP unique and JS library. Will look into
- "Summary tables" - chart values from a table vs counting number of records
