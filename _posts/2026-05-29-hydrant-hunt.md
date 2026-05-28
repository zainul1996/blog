---
layout: post
title: "I Fought Fires in NS. The Dashboard Was Useless."
date: 2026-05-29 00:00:00 +0800
description: "A 9-year fight to build a simple geo tool that tells firefighters which hydrant to use, how many hoses to lay, and where to park. Rejected three times by three different agencies."
categories: [ux, singapore, government, firefighting]
tags: [scdf, ns, hydrant, govtech, open-data, firefighting]
---

I was an NS firefighter. The dashboard in our engine had one job: show us where the fire hydrants are. It failed.

The screen was laggy, hard to read, and honestly nobody used it for much. So while racing to an incident, someone would stick their head out the window and scan the roadside for the familiar white hydrant sign. You'd spot one, confirm the fire, then lay hoses on the fly. How many? You'd guess.

We carried three types of hoses. The 64mm ones for water supply from the hydrant to the engine, or for defensive firefighting from a distance. The 38mm ones for offensive firefighting going inside the building. The 64mm hoses come in 10, 20, and 30 metre lengths. The longer the lay, the more you lose water pressure. The more connections you add, the higher the chance of a fault or a burst. Connect too many and you're fighting the equipment as much as the fire. Connect too few and you run short.

Take out too many hoses and they pile on the ground as a trip hazard. After the fire, you have to roll every single one back up by hand. That extra effort adds up over a career.

This is a straightforward geo problem. When a call comes in, the system knows the fire location. Your engine has GPS. The hydrants have coordinates. Combine those three data points and you can tell the crew: "Nearest accessible hydrant is at [X]. Park here. Lay two 20m hoses."

No guessing. No one craning their neck out the window. No extra hose connections that add risk and pressure loss.

I proposed this in 2017 during my NS days. The answer: "Data can't be gotten."

I joined GovTech in 2022 and thought: finally, I'm inside the machine. I pushed the same idea again. The answer: "This is not GovTech's jurisdiction. Talk to HTX."

I don't work in government anymore. It's 2026 and the feature still doesn't exist. There are more fires now than when I served, with shorter manpower.

The part that frustrates me most is the data argument. Fire hydrant locations are not sensitive. They are metal fixtures bolted to the pavement. Anyone with a phone could map every single one in Singapore by walking the streets for a few weekends. So why is this not on data.gov.sg?

If the data were public, civilians could have built this tool for free years ago. SCDF could trial it and if it works, hire the person or buy the solution. Agencies love to say they want innovation from the ground up. But they won't publish the data that would let people innovate.

Three times I brought this up. Three times it got handed off to someone else's problem. I'm not in a position to push anymore. But I still wonder: who owns this problem now?