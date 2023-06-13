![[Layout.png]]


> [!col] >> [!info] Callouts >> Stuff inside the callout >> More stuff inside. >>> [!ERROR] Error description >>> Nested callout >>> - example MD code >>> - more stuff > >> [!col-md-2.5] >> # Text annotation example: >>> [!col] >>>> [!col-md] >>>> 1. Function name **a** should be more descriptive >>>> 2. Remove **if/else** by using **||** >>> >>>> [!col-md-2] >>>> ```js >>>> function a(word) { >>>> if (word != null) { >>>> console.log(word); >>>> } else { >>>> console.log("a"); >>>> } >>>> } >>>> let msg = "Hello, world!"; >>>> console.log(msg)
# Processors

## approachsettlment-v1.0
### Required
<span class="purple"> Color ref for color coding by data-module</span>
- TimeStamp
- Event
- StarSystem
	- name
- StarPos
	- coords
- SystemAddress
	- int??
- Name
	- Settlement Name
- BodyID
- BodyName
- Latitude
- Longitude

## blackmarket-v1.0
### Required
- SystemName
- StationName
- MarketID
- TimeStamp
- Name
	- commodity name
- SellPrice
	- price to sell to market
- Prohibited
	- boolean

## codexentry-v1.0
### Required
- timestamp
- event
	- CodexEntry
- System
	- Name
- StarPos
	- Coords
- SystemAddress
	- int
- EntryID
### Optional
