# Plumbing Refactor

My house was built in 1927 and still had galvanized steel pipes possibly from the original construction under the house. Galvanized pipes rust on the inside, impeding water flow. Sometimes the rusty bits break off, get stuck in plumbing fixtures, and further impede flow until you take the fixture apart and clean them out. Also because of the thermal mass of the galvanized pipes, along with the traditional trunk-and-branch layout (large main water pipes with smaller pipes going to individual fixtures), it would take >60s for the master bathroom shower to get hot, wasting a ton of water every time we showered.

I wanted to replace these with more modern PEX-A plumbing. Goals of this project were

* Increase water pressure throughout the house
* Decrease regular maintenance (no more rusty bits!)
* Get hot water to the back of the house faster

Thankfully a prior remodel had replaced the pipes in the walls with PEX-B to all the fixtures, so I didn't need to rip any walls open, I just needed to relpace all the pipes in the crawl space.

As a bonus I also added an expansion tank (to prevent high pressure as the water expands when heating) and a [Moen Flo](https://www.moen.com/flo) to monitor flow and pressure.

## Design

### PEX

I went with PEX-A tubing. I used 3/4" from the main entry into the house, and then 1/2" to the individual zones. PEX-A is really neat, you use a special tool that stretches the PEX-A tubing, you then attach it to a PEX-A fitting, and slowly the tubing contracts around the fitting, creating a simple but sturdy seal. It was an absolute joy to use. Because the pipe is stretched wider, the fittings are able to have an inner diameter about the same size as the inner diameter of the tubing itself, so there's less impedence to the water flow.

In the walls, there was already PEX-B tubing. PEX-B does not support the expansion fittings, so I needed to adapt PEX-A to PEX-B. The officially supported way, according to Uponor (the main manufacturer of PEX-A) is to go from `PEX-A` -> `PEX-A expansion to threaded fitting` -> `threaded fitting to PEX-B compression fitting` -> `PEX-B`. This seemed way too complex (and expensive!). Instead, I just go PEX-B compression fittings and a PEX-B compression tool. These use a smaller diameter fitting that fits inside the tubing (without expansion) and then a copper ring that fits around the tubing. The copper ring is compressed with a special tool to squeeze the tubing to the fitting. While not officially supported by the manufacturer for PEX-A it works just fine.

See also:
* [Video about pex fitting options](https://youtu.be/PaouJskWAXc).
* [Another one](https://youtu.be/xCwxbT_hhFQ)

### Layout

There are several layout options. Here's a [good overview](https://www.finehomebuilding.com/2009/03/02/three-designs-for-pex-plumbing-systems). On one extreme there's trunk-and-branch where you use single big pipes that snake throughout the house and then smaller pipes branch directly off that pipe to go to the fixtures. On the other extreme there's the "home run" design where you have one big manifold near your hot water heater, and then you run individual pipes to each fixture. There's also designs in-between (sometimes called submanifold or logic plumbing). Trunk-and-branch is the traditional option, but it wastes a ton of hot water at the furthest fixture since there's a ton of water that needs to be cleared from the pipe. I opted for something mostly like a "home run" design except that some of the lines supply several fixtures.

## Parts list

These are from my unformatted notes, but perhaps it's useful to others.

- Manifold w/ expansion fittings (liking the copper expansion ones)
	- $75 https://www.supplyhouse.com/Uponor-Wirsbo-LF2811050-1-Copper-Branch-Manifold-1-2-ProPEX-Outlets-6-Outlets-Lead-Free-Brass
    - It sure would have been neater to have ball valves but not for 3-4x more expensive. It also adds complexity https://www.supplyhouse.com/Uponor-Wirsbo-LF2500800-1-Copper-Manifold-w-LF-Brass-1-2-ProPEX-Ball-Valve-8-Outlets-Lead-Free-Brass
- Expansion tool
	- $120 - https://www.amazon.com/IWISS-1-inch-ProPEX-Expander-Uponor/dp/B078MVXP5V
- Expansion Rings
	- 3/4" 
		- $0.41 each https://www.supplyhouse.com/Wirsbo-Uponor-Q4690752-ProPEX-Ring-with-Stop-3-4-blue-print-2299000-p
		- $4 each https://www.amazon.com/dp/B01069UNJM
	- 1/2"
		- $9.50 box of 50 - https://www.supplyhouse.com/Wirsbo-Uponor-Q4690512-ProPEX-Ring-with-Stop-1-2-blue-print-2298000-p
		- 50-Pack $15 - https://www.amazon.com/Uponor-Q4690512-Inch-ProPEX-50-Pack/dp/B07736WT6T
- Connectors
	- To sharkbite
		- 12 pex-a to pex-b compression 1/2"
			- Sharkbites are $6ea - https://www.supplyhouse.com/SharkBite-U008LF-1-2-x-1-2-SharkBite-Coupling-Lead-Free
			- Probably just pex-b compression fittings as per this guy
		- Compression rings
		- Compression tool
			- $30 clamp tool with clamps - https://www.amazon.com/IWISS-Fastening-Stainless-8-Inch-1-inch-Non-F2098/dp/B0196DLLWM
			- $90 Copper ring tool - https://www.amazon.com/IWISS%C2%AE-F1807-Copper-Ring-Crimping/dp/B01FJA96X2
				- 1/2" copper rings https://www.amazon.com/IWISS-Skid-Proof-Plumbing-Fittings-36pcs-Accurate/dp/B07F24ZNR9
		- 4x pex-b endcaps
			- (not seeing any brass)
			- https://www.supplyhouse.com/Viega-43723-1-2-PureFlow-Poly-PEX-Crimp-Test-Plug
	- Connection to main water
		- Sharkbite or Sweat to expansion
		- See also connection to the moen flo
		- Probably a 3/4" pex-a elbow - https://www.supplyhouse.com/Wirsbo-Uponor-LF4710750-ProPEX-Brass-Elbow-3-4-PEX-x-3-4-PEX
	- 1/2" npt male to pex-a
		- https://www.supplyhouse.com/Wirsbo-Uponor-LF4525050-ProPEX-LF-Brass-Male-Threaded-Adapter-1-2-PEX-x-1-2-NPT
	- TODO: Hardware to connect to the hot water heater
		- Tee to split off cold water https://www.supplyhouse.com/Wirsbo-Uponor-LF4707575-ProPEX-LF-Brass-Tee-3-4-PEX-x-3-4-PEX-x-3-4-PEX
		- 3/4" NPT male -> pex???
		- https://diy.stackexchange.com/questions/80445/connecting-a-water-heater-what-kind-of-fittings-valves-and-adapters
- PEX Mounts?
	- https://www.amazon.com/Everflow-HC012-J-Hook-Tubing-Support/dp/B07D92FN2M
- Pressure guage
	- 1/4" NPT $5 https://www.supplyhouse.com/Bluefin-GEP2-100-BM-1-4-NPT-2-Dial-Lower-Mount-No-Lead-Pressure-Gauge-0-100-PSI
	- TODO: Hardware to hook up
- Pex pipe
	- 93ft hot 1/2" pex-a
		- 100' - $50 https://www.supplyhouse.com/Uponor-Wirsbo-F4240500-1-2-Uponor-AquaPEX-White-w-Red-Print-100-ft-coil
	- 125 cold 1/2" pex-a
		- 100' - $50 https://www.supplyhouse.com/Uponor-Wirsbo-F4340500-1-2-Uponor-AquaPEX-White-w-Blue-Print-100-ft-coil
	- 25' 3/4" pex-a
		- 100' - $75 https://www.supplyhouse.com/Wirsbo-Uponor-F1040750-3-4-AQUAPEX-100-ft-coil-2174000-p
- Stuff to hook up to Can Bal's 1" moen flo
	- https://www.moen.com/shared/docs/product-specifications/900-006sp.pdf
	- 3/4 female sweat to 1" male npt
	- 1" male npt to 3/4" pex-a expansion - https://www.supplyhouse.com/Wirsbo-Uponor-LF4527510-ProPEX-LF-Brass-Male-Threaded-Adapter-3-4-PEX-x-1-NPT
- Misc
	- Solder and flux
	- Pipe dope

Connections to existing plumbing
- Guest bath (all connected for simplicity could just hook them all together to start)
	- Sink (hot & cold) - 1/2" sharkbite pex (near water heater)
	- Toilet (cold) - 1/2" sharkbite pex
	- Bath (hot & cold) - 1/2" sharkbite pex
	- Washer (hot & cold) - 1/2" sharkbite pex 
- Backyard faucet - 1/2" Brass thread  (0.84in od thread)
- Kitchen
	- Sink and washer (hot & cold) - 1/2" sharkbite pex
	- Ice maker (cold) - 1/2" sharkbite pex
- Master bath (all on the same group)
	- Sink (hot & cold) - 1/2" sharkbite pex
	- Toilet (cold) - 1/2" sharkbite pex
	- Bath (hot & cold) - 1/2" sharkbite pex
	- Back yard - generic PEX-b 1/2" connected with sharkbite tee
- To main
	- 3/4" sweat brass (to 3/4" pex-a expansion)
- To water heater
	- 3/4" NPT (in & out) (female on the water heater side)
