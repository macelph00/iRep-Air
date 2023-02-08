---
title : "Parts came out with tapered wall"
description: 
excerpt: "Image of the laser beam cutting through ⬆️"
date: false
lastmod: false
draft: false
weight: 3
images: ["taperwall.png"]
url: "/machines/denfordlasercutter/taperwall/"
pinned: true
homepage: false
---
---

## Root Cause

1. Material is too thick

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mostly happen on >9 mm Acrylic, Plywood, MDF. This is a common issue &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;because the nature of a laser beam will exert more heat on the surface of the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;material than the bottom (think of it as drilling through the material), thus the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;kerf is wider on top than bottom.

2. Material is not flat/placed flat on the bed

3. The mirror is misaligned (**this is very unlikely since Denford doesn't have mirror misalignment issue as HPC does**)

## Fix

1. This is not really fixable, you'll get a certain level of taper on all cuts depending on the thickness.

2. Place the workpiece flat. You can use mini weights to press the workpiece down flat. **You <span style="color:red">MUST make sure</span> the nozzle does not hit the weight while running**. You can check this by running 'test', do be very careful not to let the nozzle crash into the weight.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Check if there are any bits on bed causing the material not placed flat, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;remove them. There could be damage on the honeycomb bed that cause this &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;as well. The honeycomb bed is consumable, if you think the condition is &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;critical, please contact hardware team.

3. Contact hardware team.
---

##### If have any other problems or still not working, please contact hardware team (Slack #hardware).
