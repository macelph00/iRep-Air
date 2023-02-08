---
title : "Not Cutting Through Even With Cutting Power +50%"
description: 
excerpt: 
date: false
lastmod: false
draft: false
weight: 2
images: ["notcuttingthrough.jpg"]
url: "/machines/denfordlasercutter/notcutthingthrough/"
pinned: true
homepage: false
---
---

## Root Cause

1. The Z axis (bed) is not calibrated correctly

This means the lens are out of focus, which will either cause a power insufficiency or burns the material

2. The mirror is not clean (**this is very unlikely but could happen**)

## Fix

1. Make sure there is no obstruction under the bed, nothing stands in the way. Open the ULS software, click 'Home Z', the bed will then move all the way down, which will activated the limit switch and zero the Z axis correctly. 

2. Contact hardware team to perform maintenance on it.

---

##### If have any other problems or still not working, please contact hardware team (Slack #hardware).
