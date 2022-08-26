---
title : "Start Cutting Somewhere Else"
description: 
excerpt:
date: false
lastmod: false
draft: false
weight: 2
images: ["wrongstart.png"]
url: "/machines/hpclasercutter/wrongstart/"
pinned: true
homepage: false
---
<br>

1. Check if "immediate" is enabled, by clicking it the nozzle will start where ever it's left in the machine when downloading "current" to the machine.

<br>

![immediate](immediate.PNG)

<br>

2. If "immdeidate" is disabled, the nozzle will start where the blue dot is, relatively in the software.

<br>

![nonimmediate](nozzleposition.jpeg)

## Root Cause

With "Immediate" enabled, nozzle position of the **MACHINE** overwrites the software.

<br>

With "Immediate" disabled, nozzle position of the **SOFTWARE** overwrites the machine.

<br>

**NOTE**: it may cause SOFT STOP error as well.

## Fix

Both works fine, choose an option that you prefer.


<br>
<br>

##### If still not working, please contact hardware team##### If have any other problems or still not working, please contact hardware team