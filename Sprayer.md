# Low-Cost Greenhouse Insecticide Mist Sprayer Guide

**Goal:** Build a simple sprayer that makes small insecticide droplets and uses moving air inside a greenhouse to carry those droplets toward vegetable leaves, while reducing the amount that falls straight to the floor.

**Price check date:** September 6, 2026  
**Currency:** U.S. dollars

---

## 1. The main idea

Your idea is workable, but I would make one important change:

**Do not try to make the droplets as tiny as possible.**

If the droplets are too big, they fall quickly and a lot of the insecticide reaches the ground.

If the droplets are too small, they can stay in the greenhouse air for a long time, evaporate, move away from the plants, and become much easier to breathe.

For a simple greenhouse system, the goal should be:

> Make a fine mist, then use controlled airflow to carry that mist through the vegetable leaves.

The basic system is:

```text
Tank
  ↓
Filter
  ↓
12 V diaphragm pump
  ↓
Pressure gauge / regulator
  ↓
Nozzle filter
  ↓
Fine hollow-cone nozzle
  ↓
Small droplets
  ↓
Air from blower/fan
  ↓
Vegetable canopy
```

I would build this as an **air-assisted mist sprayer**, not as a room-filling fog machine.

---

# 2. Best droplet size for this idea

Greenhouse spray equipment is commonly divided roughly like this:

| Droplet size | What it acts like | My view for your project |
|---|---|---|
| Below 30 microns | Very fine fog | Avoid for a basic DIY insecticide system |
| 30–50 microns | Fog | Stays airborne easily, but has more inhalation/evaporation problems |
| **50–100 microns** | **Mist** | **Best range for the idea you described** |
| 100–150 microns | Fine spray | Easier to control and deposit on leaves |
| 200–400 microns | Normal hydraulic spray | More likely to fall quickly and create runoff |

UMass greenhouse guidance describes low-volume mist as about **50–100 microns**, while fog is below about 50 microns. It also explains that very small droplets evaporate more quickly and can have trouble reaching or sticking to the target.

### My recommended starting target

For a low-cost homemade greenhouse unit:

**Start around 70–100 microns if your pesticide label allows low-volume/mist application.**

That is small enough to move with air, but not as extreme as a 5–30 micron fog.

If you cannot measure the exact droplet size, do not worry at the beginning. Instead:

1. Use a proper agricultural hollow-cone nozzle.
2. Run it at the pressure shown in the nozzle maker's chart.
3. Start with water.
4. Put water-sensitive paper on the top, middle, bottom and underside of leaves.
5. Adjust pressure, nozzle distance and fan speed until you get lots of small spots without making the leaves drip.

### Important

The pesticide label comes first.

Some insecticides can be used with mist/low-volume equipment. Some cannot. Some products are not allowed as greenhouse fog treatments on edible crops.

**Do not turn a pesticide into a fog just because the machine can do it. The pesticide label must allow that application method and crop.**

Sources:

- UMass greenhouse sprayer guide: https://www.umass.edu/agriculture-food-environment/greenhouse-floriculture/fact-sheets/sprayers-spray-application-techniques
- UMass mist/fog guide: https://www.umass.edu/agriculture-food-environment/greenhouse-floriculture/fact-sheets/mist-fog-equipment-for-propagation

---

# 3. The nozzle I would use first

For a cheap prototype, I would start with a **ceramic hollow-cone agricultural nozzle**.

A hollow-cone nozzle is useful because it makes a fine spray and is commonly used for insecticides and fungicides where good leaf coverage is needed.

A good example is the **TeeJet TX / TXA / TXR ConeJet family**.

Typical current prices are around:

- TeeJet TXR ceramic hollow-cone tip: about **$5.65–$6.78 each**
- TeeJet stainless/ceramic ConeJet versions: roughly **$6–$13 each**
- Basic nozzle strainer: roughly **$1–$4 each**

TeeJet lists its TXA ConeJet as producing **fine to very-fine droplets** and rates it for insecticide use.

### Why ceramic?

Ceramic costs only a little more than very cheap plastic or brass tips, but it normally lasts longer.

It is also more resistant to wear from abrasive spray mixtures.

### What I would buy

For the first test:

- 2 ceramic hollow-cone tips
- 2 matching nozzle bodies/caps
- 2 nozzle strainers
- 2 spare tips

Do not buy 20 nozzles before testing two.

Sources:

- TeeJet TXA ConeJet: https://www.teejet.com/spray-application-products/spray-product-type/spray-tips/txa-conejet
- Current example retail price: https://floridasprayers.com/products/teejet-conejet-txr-hollow-cone-spray-tip-txr80036vk

---

# 4. How to stop the nozzle from blocking after long use

Clogging will probably be one of your biggest problems.

Small-droplet nozzles have small holes, so dirt, undissolved chemical, hard-water deposits and dried pesticide can block them.

The easiest solution is **good filtering + immediate cleaning**.

## Use three levels of protection

### Level 1 — Filter when filling the tank

Pour water through a simple coarse screen before it enters the tank.

This catches:

- sand
- rust
- plant material
- dirt
- pieces from chemical packaging

### Level 2 — Main line filter

Put a line strainer between the tank/pump and the nozzle manifold.

A **50-mesh line filter** is a good simple starting point for many agricultural spray systems, but the final mesh size should match the nozzle manufacturer's recommendation.

### Level 3 — Small filter at each nozzle

Put a tip strainer immediately before every nozzle.

Many TeeJet nozzles use 50- or 100-mesh strainers depending on the tip size.

Do not automatically use the finest filter you can find. A filter that is too fine can block constantly, especially with suspension or wettable-powder products.

---

## Simple anti-clog layout

```text
TANK
 │
 │ coarse fill screen
 ↓
PUMP
 │
 ↓
50-mesh main line filter
 │
 ↓
pressure gauge
 │
 ↓
manifold
 ├───────────┐
 ↓           ↓
tip filter   tip filter
 ↓           ↓
nozzle       nozzle
```

---

## Clean it every time you spray

The biggest mistake is leaving pesticide mixture sitting inside the nozzle and hose overnight.

After use:

1. Empty the system according to the pesticide label.
2. Rinse the tank.
3. Add clean rinse water.
4. Run clean water through the pump, hose and nozzles.
5. Remove nozzle strainers.
6. Check for dirt.
7. Let removable parts dry before storage when appropriate.

For products that leave residue, use only a cleaner/rinse method that is compatible with the product label and equipment.

### Never clean the nozzle hole with metal wire

Do not use:

- needle
- nail
- safety pin
- steel wire

That can enlarge or scratch the nozzle hole and permanently change its spray pattern.

TeeJet recommends a soft brush rather than a metal object.

Also, **never put a pesticide nozzle in your mouth and blow through it.**

Keep a toothbrush-sized soft cleaning brush with the sprayer.

### Check nozzle wear

Once in a while:

1. Put clean water in the system.
2. Set the normal pressure.
3. Collect spray from each nozzle for one minute.
4. Measure the amount.
5. Compare it with a new nozzle of the same model.

TeeJet recommends replacement when nozzle flow is about **10% higher than a new nozzle**.

Sources:

- TeeJet spray-tip maintenance: https://www.teejet.com/en/-/media/dam/agricultural/usa/sales-material/catalog/technical_information.pdf
- UF/IFAS sprayer cleanout guide: https://ask.ifas.ufl.edu/publication/PI291

---

# 5. Simple device configuration I recommend

For your first real machine, do not build an automatic robot.

Build a simple stationary or movable unit and prove that the mist works.

## Basic version

```text
             greenhouse air

                 >>>>>>>>>>>>>>

                    mist
                • • • • •
              • • • • • •
                   ↓

Tank → Filter → Pump → Gauge → Nozzle
                               ↑
                               │
                            small fan

                         >>> 🌿🌿🌿
                            🌿🌿🌿
```

Another good layout is to place the nozzle just in front of the blower outlet:

```text
                 blower
             [ FAN >>>>>> ]
                       \
                        \  • • • • •
                         \ • • • • • >>> vegetables
                          NOZZLE
```

The fan should carry the droplets.

It should not be so strong that it blows the droplets straight past the plants.

You want the leaves to move a little, not violently shake.

---

# 6. Recommended basic parts

## Option A — Cheapest and easiest way

Instead of buying a tank, pump, hose and wiring separately, buy a basic **12 V spot sprayer** and modify it.

For example, a 15-gallon Greenwood spot sprayer was listed around **$89.99** and includes:

- 15-gallon polyethylene tank
- 12 V diaphragm pump
- about 1 GPM
- up to about 40 PSI
- hose
- wiring
- spray wand

That gives you most of the expensive plumbing in one purchase.

Then add your own fine nozzle, filters and fan.

### Problem with the 40 PSI version

40 PSI is enough to begin testing some hollow-cone nozzles, but it gives you less pressure adjustment.

If your budget allows it, a **60–70 PSI diaphragm pump** gives you more room to tune the spray.

A 2.2 GPM / 70 PSI Everflo pump was around **$90** at the time of this check.

---

# 7. Low-cost parts list

Prices below are normal example prices I found in September 2026. They can change.

| Part | Suggested type | Rough cost |
|---|---|---:|
| Tank + pump base | 15-gal 12 V spot sprayer | $90–$130 |
| Or pump only | 12 V diaphragm, 1–2.2 GPM, 40–70 PSI | $40–$95 |
| Hollow-cone nozzle | Ceramic TeeJet-style agricultural tip | $6–$13 each |
| Tip strainer | 50/100 mesh, matched to tip | $1–$5 each |
| Main line filter | 50-mesh sprayer strainer | $18–$30 |
| Pressure gauge | 0–60 or 0–100 PSI | $8–$20 |
| Small air blower | 12 V 3-inch blower around 130 CFM | $34–$50 |
| Hose/tube/fittings | Chemical-compatible | $20–$40 |
| Ball valve / shutoff | Chemical-compatible | $5–$15 |
| Fuse + switch + wire | 12 V electrical | $10–$25 |
| Spare nozzle/filter parts | Keep on hand | $10–$25 |
| Water-sensitive paper | For testing | $10–$30 |

### Realistic first-build budget

If you start with a cheap spot sprayer:

**About $180–$300 total** is a reasonable target for a simple working prototype.

If you already have a tank, pump or greenhouse fan:

**You may be able to test the idea for around $80–$150.**

Do not spend money on cameras, electrostatic charging, high-pressure fog pumps or automatic robotics yet.

---

# 8. A fan that is cheap enough for a prototype

A small 12 V marine/bilge blower is useful for experiments because it is:

- cheap
- compact
- moisture resistant
- easy to power from the same 12 V supply as the pump

One current example:

- 3-inch 12 V blower
- about 130 CFM
- about **$34**

You may also already have horizontal-airflow fans in the greenhouse. Those can help move air around the greenhouse, but the first prototype should have a **local fan close to the nozzle** so you can control exactly where the droplets go.

Source example:

https://www.five-oceans.com/products/3-in-line-bilge-blower-130-cfm-12v-fo4333-fo-4333

---

# 9. Existing machines that already do something similar

Yes. Commercial ULV cold foggers already make very small droplets and move them through indoor air.

Current examples include:

| Machine | Approx. droplet size | Example price |
|---|---:|---:|
| XPOWER F-8 ULV | fine fog | ~$179 |
| XPOWER F-16 ULV | average below 50 μm | ~$235 |
| Air Fog ULV | about 10–50 μm | ~$350 |
| Vectorfog C150+ | about 5–50 μm | ~$479 |
| Larger greenhouse fog systems | ULV/fog | $1,000–$3,000+ |

These are useful references, but **I would not buy one first** for your project.

Why?

Your main problem is pesticide falling to the ground.

A true fogger can create droplets so small that they stay in the greenhouse air, but that does not automatically mean more insecticide ends up on the vegetable leaves.

A simple **50–100 μm air-assisted mist** can be easier to control.

Sources:

- XPOWER F-16: https://www.homedepot.com/p/313939096
- Air Fog ULV: https://www.agristoreusa.com/products/air-fog-ulv-cold-fogger
- Vectorfog C150+: https://www.plantlifeco.com/products/c150-ulv-cold-fogger

---

# 10. Problems you may face while building it

## Problem 1 — The nozzle keeps blocking

**Cause:**

- dirty water
- dried chemical
- particles in pesticide
- hard-water deposits
- wrong filter

**Fix:**

- fill filter
- main line filter
- tip filter
- flush after every use
- keep spare nozzles

---

## Problem 2 — Droplets are too big

**What you will see:**

- leaves become very wet quickly
- drops join together
- water runs from leaves
- lots of liquid on greenhouse floor

**Possible fixes:**

- check nozzle type
- raise pressure only within the nozzle rating
- use a smaller appropriate hollow-cone tip
- improve airflow
- reduce liquid flow

---

## Problem 3 — Droplets are too small

**What you will see:**

- mist hangs around for a very long time
- very little visible deposition on leaves
- mist reaches unwanted parts of greenhouse
- strong airborne pesticide exposure risk

**Possible fixes:**

- use a larger tip
- lower pressure
- reduce blower speed
- move nozzle closer to plants
- do not try to make a 5–20 μm fog unless the pesticide and equipment are specifically intended for it

---

## Problem 4 — Fan is too powerful

A big fan can actually increase waste.

The spray may fly through the vegetable row and hit:

- wall
- floor
- other greenhouse section
- ventilation outlet

Start with low airflow and increase slowly.

---

## Problem 5 — Fan is too weak

The fine spray may fall before entering the middle of the plant.

Move the nozzle/fan closer or increase airflow slightly.

---

## Problem 6 — Uneven pressure

A small diaphragm pump can pulse.

This can make the spray pattern change every second.

A pressure regulator, small accumulator/pulsation damper and a good pressure gauge can help.

For version 1, a gauge is more important than electronic control.

---

## Problem 7 — Chemical settles in the tank

Some pesticide formulations do not stay perfectly mixed.

If the label requires agitation, a simple recirculation line can help:

```text
pump
  │
  ├────→ nozzles
  │
  └────→ small return line → tank
```

Do not add strong agitation unless the product instructions allow it.

---

## Problem 8 — Nozzle material wears out

As the hole becomes larger:

- flow increases
- droplets change
- coverage changes
- pesticide use increases

Ceramic tips normally give better wear life than cheap soft tips.

---

## Problem 9 — Hose and seals get damaged

Different pesticide formulations can attack some plastics and rubber.

Use components sold for agricultural chemical spraying.

EPDM, Viton and other seal materials have different chemical resistance.

Check the pesticide/equipment compatibility information before leaving chemical in the system.

---

## Problem 10 — Electrical problems in the greenhouse

A greenhouse is humid.

Protect:

- wire connections
- switches
- battery terminals
- controller
- pump connectors

Use a fuse close to the battery/power supply.

Keep electrical connections away from the direct spray.

Do not use an open, sparking motor inside a pesticide cloud.

---

## Problem 11 — The mist reaches you

This is one of the biggest reasons I do not recommend chasing extremely tiny droplets.

When spraying:

- nobody should stand in the mist
- follow the label PPE requirements
- keep other people and animals out
- follow the product's re-entry interval
- follow required ventilation instructions

EPA guidance says fogging/misting products must be specifically registered/labeled for that use and users must follow their ventilation, PPE and re-entry directions.

EPA safety guidance:

https://nepis.epa.gov/Exe/ZyPURL.cgi?Dockey=P101FA9B.txt

---

# 11. Best way to turn the idea into a real greenhouse system

Do it in small steps.

## Step 1 — Make a water-only test rig

Buy:

- one small pump or spot sprayer
- one or two hollow-cone nozzles
- filters
- pressure gauge
- small fan

Use only water.

Do not start with pesticide.

---

## Step 2 — Test nozzle without the fan

Watch:

- spray shape
- pressure
- how much liquid comes out
- how quickly it wets the leaf

Put collection cups under the plants to see how much reaches the ground.

---

## Step 3 — Add the fan

Mount the fan so its air catches the spray immediately after it leaves the nozzle.

Try:

- low fan speed
- medium fan speed
- different nozzle angles
- different distances from the plants

Your goal is to get mist **inside the canopy**, not simply make a cloud.

---

## Step 4 — Use water-sensitive paper

Put cards in these places:

```text
             TOP
              [card]

 outside [card] 🌿🌿 [card]

              🌿🌿
            [card]
             inside

       underside [card]

-------------------------
ground        [card]
```

A successful setup should give many small marks on leaf-position cards and much less coverage on the ground card.

---

## Step 5 — Find the simplest good setting

Write down:

- nozzle model
- pressure
- fan setting
- nozzle distance
- nozzle angle
- amount of water used per minute

Do not keep changing everything.

Once you have a setting that works, repeat the test several times.

---

## Step 6 — Only then test a labeled crop product

Before putting insecticide in the unit, confirm on the label:

- your vegetable crop is listed
- greenhouse use is allowed
- mist/low-volume/fog application is allowed if that is how you will use it
- correct application amount
- required PPE
- re-entry interval
- pre-harvest interval
- ventilation requirements

The machine should control the **delivery method**.

It should not be used to guess or change the pesticide dose.

---

# 12. My recommended Version 1

If I were building this cheaply, I would buy:

1. **15-gallon 12 V spot sprayer** — about $90–$130
2. **Two ceramic TeeJet-style hollow-cone nozzles** — about $12–$25 total
3. **Two tip filters** — about $2–$10
4. **50-mesh main filter** — about $18–$25
5. **Pressure gauge** — about $10–$20
6. **12 V 130 CFM blower** — about $34–$50
7. **Fittings, hose, valve and wire** — about $30–$60
8. **Water-sensitive cards** — about $10–$30

Expected total:

**roughly $200–$300**

You can reduce that if you already own a sprayer or greenhouse fan.

---

# 13. What I would NOT buy yet

For the first version, skip:

- electrostatic charging
- LiDAR
- cameras
- AI
- robot cart
- 1,000+ PSI fog pump
- thermal fogger
- expensive rotary atomizer
- automatic dosing equipment
- very tiny 5–20 micron fog nozzles

First prove one thing:

> Can a cheap fine nozzle + controlled airflow put more liquid on the vegetables and less liquid on the floor?

If the answer is yes, then automation is worth adding.

---

# 14. Best simple design

This is the design I think gives the best balance of cost, reliability and performance:

```text
             12 V POWER
                 │
          ┌──────┴──────┐
          ↓             ↓
        PUMP           BLOWER
          │             │
TANK → FILTER           │
          │             │
       GAUGE             │
          │             │
       MANIFOLD          │
       /      \          │
  FILTER      FILTER     │
    ↓            ↓       │
 NOZZLE       NOZZLE     │
       \       /         │
        • • • •    <<<<<< airflow
       • • • • •
          ↓
       🌿🌿🌿🌿
       🌿🌿🌿🌿
```

### Target

- Droplet range: **about 50–100 μm**
- DIY starting target: **around 70–100 μm**
- Pressure: use the nozzle manufacturer's chart; a **40–70 PSI-capable** starter system is practical
- Nozzle type: **fine hollow-cone**
- Nozzle material: **ceramic preferred**
- Main filter: **around 50 mesh**
- Tip filter: **50 or 100 mesh depending on the exact nozzle**
- Airflow: enough to move droplets through the leaves, not enough to blow them past the crop

---

# 15. Final recommendation

For your greenhouse, I would **not buy a commercial fogger first**.

The best low-cost path is:

> **cheap 12 V spot sprayer + agricultural hollow-cone nozzle + good filtration + pressure gauge + small blower**

That lets you learn the most important things:

- what droplet size works
- how much airflow is needed
- how much falls on the floor
- how often the nozzle blocks
- which pressure gives good coverage
- where to mount the nozzle
- whether two nozzles are better than one

After that works reliably, the next upgrade should be automatic timing/valves, not a more complicated fogging system.

---

# Sources used

1. UMass Amherst — Sprayers and Spray Application Techniques  
   https://www.umass.edu/agriculture-food-environment/greenhouse-floriculture/fact-sheets/sprayers-spray-application-techniques

2. UMass Amherst — Mist and Fog Equipment for Propagation  
   https://www.umass.edu/agriculture-food-environment/greenhouse-floriculture/fact-sheets/mist-fog-equipment-for-propagation

3. TeeJet — TXA ConeJet  
   https://www.teejet.com/spray-application-products/spray-product-type/spray-tips/txa-conejet

4. TeeJet — Spray Tip Wear and Maintenance  
   https://www.teejet.com/en/-/media/dam/agricultural/usa/sales-material/catalog/technical_information.pdf

5. UF/IFAS — Sprayer Cleanout Procedures  
   https://ask.ifas.ufl.edu/publication/PI291

6. EPA — Safety Tips for Using Foggers and Misters Indoors  
   https://nepis.epa.gov/Exe/ZyPURL.cgi?Dockey=P101FA9B.txt

7. Harbor Freight — Greenwood 15-gallon 12 V spot sprayer  
   https://www.harborfreight.com/15-gallon-spot-sprayer-12-volt-61263.html

8. Five Oceans — 12 V 130 CFM blower  
   https://www.five-oceans.com/products/3-in-line-bilge-blower-130-cfm-12v-fo4333-fo-4333

9. Air Fog ULV cold fogger  
   https://www.agristoreusa.com/products/air-fog-ulv-cold-fogger

10. XPOWER F-16 ULV cold fogger  
    https://www.homedepot.com/p/313939096

---

## One safety rule worth remembering

**Do not use the machine to aerosolize an insecticide unless the product label allows that greenhouse/crop/application method.**

A machine can make almost any liquid into mist. That does **not** mean every pesticide is safe or legal to apply that way.
