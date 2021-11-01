# Plumbing Refactor

<a href="https://user-images.githubusercontent.com/218876/139624625-1bf0f75a-9190-4199-9b44-dde34361df85.jpg"><img src="https://user-images.githubusercontent.com/218876/139624625-1bf0f75a-9190-4199-9b44-dde34361df85.jpg" width="600" ></a>

My house was built in 1927 and still had galvanized steel pipes possibly from the original construction. Galvanized pipes rust on the inside, impeding water flow. Sometimes the rusty bits break off, get stuck in plumbing fixtures, and further impede flow until you take the fixture apart and clean it out. Also because of the thermal mass of the heavy pipes, along with the traditional trunk-and-branch layout (large main water pipes with smaller pipes going to individual fixtures), it would take >60s for the master bathroom shower to get hot, wasting a ton of water every time we showered.

I wanted to replace these with more modern PEX-A plumbing. Goals of this project were:

* Increase water pressure throughout the house
* Decrease regular maintenance (no more rusty bits!)
* Get hot water to the back of the house faster

Thankfully a prior remodel had replaced the pipes in the interior walls with PEX-B to all the fixtures, so I didn't need to rip any walls open, I just needed to replace all the pipes in the crawl space below the house.

As a bonus I also added an expansion tank (to prevent high pressure as the water expands when heating) and a [Moen Flo](https://www.moen.com/flo) to monitor flow and pressure.

Galvanized rusty bits I cleaned out of my fittings:

<a href="https://user-images.githubusercontent.com/218876/138945026-a012055f-d3df-4e9c-9b55-11ac66cb1c7f.jpg"><img src="https://user-images.githubusercontent.com/218876/138945026-a012055f-d3df-4e9c-9b55-11ac66cb1c7f.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138945498-3e075433-c55e-47c5-8f95-5b137a199bea.jpg"><img src="https://user-images.githubusercontent.com/218876/138945498-3e075433-c55e-47c5-8f95-5b137a199bea.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138965951-d0d78d7c-cabf-4159-bdaa-db0e9e239e62.jpg"><img src="https://user-images.githubusercontent.com/218876/138965951-d0d78d7c-cabf-4159-bdaa-db0e9e239e62.jpg" width="200" ></a>

Old pipes I replaced

<a href="https://user-images.githubusercontent.com/218876/138945678-c99bec25-e849-446f-a3ce-237f881fe63c.jpg"><img src="https://user-images.githubusercontent.com/218876/138945678-c99bec25-e849-446f-a3ce-237f881fe63c.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138945690-14bc3af4-f92f-4e44-bfaa-30aebd0f74c8.jpg"><img src="https://user-images.githubusercontent.com/218876/138945690-14bc3af4-f92f-4e44-bfaa-30aebd0f74c8.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138945983-f937c1bb-6925-462d-a552-a12c2a8d83e4.jpg"><img src="https://user-images.githubusercontent.com/218876/138945983-f937c1bb-6925-462d-a552-a12c2a8d83e4.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/139624805-540b92e8-6d21-433d-a20c-759e41926e30.jpg"><img src="https://user-images.githubusercontent.com/218876/139624805-540b92e8-6d21-433d-a20c-759e41926e30.jpg" width="200" ></a>

## Design

### PEX

I went with PEX-A tubing. I used 3/4" from the main entry into the house, and then 1/2" to the individual zones. PEX-A (sold by Uponor as AquaPex) is really neat, you use a special tool that stretches the PEX-A tubing, you then attach it to a PEX-A fitting, and slowly the tubing contracts around the fitting, creating a simple but sturdy seal. It was an absolute joy to use. Because the pipe is stretched wider when connecting to fittings, the fittings are able to have an inner diameter about the same size as the inner diameter of the tubing itself, so there's less impedence to the water flow.

From a prior remodel, there was already PEX-B tubing in the interior walls going to the fixtures. PEX-B does not work with expansion fittings, so I needed to adapt PEX-A to PEX-B. Ideally there would exist a PEX-B compression to PEX-A expansion adapter fitting, but I wasn't able to find a part like that. The officially supported way, according to Uponor is to go from `PEX-A` -> `PEX-A expansion to threaded fitting` -> `threaded fitting to PEX-B compression fitting` -> `PEX-B`. This seemed way too complex (and expensive!). Instead, I just used PEX-B compression fittings and a PEX-B compression tool. These use a smaller diameter fitting that fits inside the tubing (without expansion) and then a copper ring that fits around the tubing. The copper ring is compressed with a special tool to squeeze the tubing to the fitting. While not officially recommended by Uponor, it works just fine for PEX-A.

See also:
* [Video about pex fitting options](https://youtu.be/PaouJskWAXc).
* [Another one](https://youtu.be/xCwxbT_hhFQ)

<a href="https://user-images.githubusercontent.com/218876/138946190-193766ee-a60f-4aac-9a73-3b2210a0a10c.jpg"><img src="https://user-images.githubusercontent.com/218876/138946190-193766ee-a60f-4aac-9a73-3b2210a0a10c.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138946478-89950432-2f5a-48cf-aa1c-6be4e9f1e69c.jpg"><img src="https://user-images.githubusercontent.com/218876/138946478-89950432-2f5a-48cf-aa1c-6be4e9f1e69c.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138946667-8fe4bdc5-9b33-4eb0-bbfa-4567f7b6c407.jpg"><img src="https://user-images.githubusercontent.com/218876/138946667-8fe4bdc5-9b33-4eb0-bbfa-4567f7b6c407.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138946776-d2329c2b-488d-42b5-bb43-c9b877a5e0a9.jpg"><img src="https://user-images.githubusercontent.com/218876/138946776-d2329c2b-488d-42b5-bb43-c9b877a5e0a9.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138946844-89cfb94c-6d73-43d8-99ee-088e95a42ae6.jpg"><img src="https://user-images.githubusercontent.com/218876/138946844-89cfb94c-6d73-43d8-99ee-088e95a42ae6.jpg" width="200" ></a>
<a href="https://user-images.githubusercontent.com/218876/138946881-535c51c6-4d42-47b3-8b34-6f6730cf1d31.jpg"><img src="https://user-images.githubusercontent.com/218876/138946881-535c51c6-4d42-47b3-8b34-6f6730cf1d31.jpg" width="200" ></a>

### Layout

There are several layout options. Here's a [good overview](https://www.finehomebuilding.com/2009/03/02/three-designs-for-pex-plumbing-systems). On one extreme there's trunk-and-branch where you use big pipes that snake throughout the whole house and then smaller pipes branch directly off that pipe to go to the fixtures. On the other extreme there's the "home run" design where you have one big manifold near your hot water heater, and then you run individual skinny pipes to each fixture. There's also designs in-between (sometimes called submanifold or logic plumbing). Trunk-and-branch is the traditional option, but it wastes a ton of hot water at the furthest fixture since there's a ton of water that needs to be cleared from the pipe. I opted for something mostly like a "home run" design except that some of the lines supply several fixtures.

<a href="https://user-images.githubusercontent.com/218876/138947249-3f8913da-44d7-4358-a367-b2f60878969a.jpg"><img src="https://user-images.githubusercontent.com/218876/138947249-3f8913da-44d7-4358-a367-b2f60878969a.jpg" width="200" ></a>

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
