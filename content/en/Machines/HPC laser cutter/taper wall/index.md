---
title : "Parts came out with tapered wall"
description: 
excerpt: "Image of the laser beam cutting through ⬆️"
date: false
lastmod: false
draft: false
weight: 3
images: ["taperwall.png"]
url: "/machines/hpclasercutter/taperwall/"
pinned: true
homepage: false
---
---

## Root Cause

1. Material is too thick

Mostly happen on 9 mm Acrylic. This is a common issue because the nature of a laser beam will exert more heat on the surface of the material than the bottom (think of it as drilling through the material), thus the kerf is wider on top than bottom.

2. Material is not flat/placed flat on the bed

3. The mirror is misaligned

Normally mirror misalignment will either cause a power drop along the cuts or do a shadowing cut. However, it's still possible to give a tapered cut.

## Fix

1. This is not really fixable, you'll get a certain level of taper on all cuts depending on the thickness.

2. You can use mini weights to press the workpiece down flat. **You <span style="color:red">MUST make sure</span> the nozzle does not hit the weight while running**. You can check this by running 'test', do be very careful not to let the nozzle crash into the weight.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Check if there are any bits on/under the bed causing the material not placed &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;flat, remove them.

3. Contact hardware team.
---

##### If have any other problems or still not working, please contact hardware team (Slack #hardware).
