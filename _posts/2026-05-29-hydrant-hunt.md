---
layout: post
title: "I Fought Fires in NS. The Dashboard Was Useless."
date: 2026-05-29 00:00:00 +0800
description: "A 9-year fight to build a simple geo tool that tells firefighters which hydrant to use, how many hoses to lay, and where to park. Rejected twice at two different agencies."
categories: [ux, singapore, government, firefighting]
tags: [scdf, ns, hydrant, govtech, open-data, firefighting]
---

I was an NS firefighter. The dashboard in our fire engine had one job: show us where the fire hydrants are. It failed.

The screen was laggy and hard to read. We used it, but it didn't come close to providing the rich info that even the tech of that time could have delivered. So while racing to an incident, someone would stick their head out the window and scan the roadside for a red hydrant. You'd spot one, confirm the fire, then lay hoses on the fly. How many? You'd guess.

We carried three types of hoses. The 64mm ones for water supply from the hydrant to the fire engine, or for defensive firefighting. The 38mm ones for offensive firefighting going inside the building. The 64mm hoses come in 10, 20, and 30 metre lengths.

Take out too many hoses and they pile on the ground as a trip hazard. After the fire, you're already exhausted from fighting it. Having fewer hoses to roll back up can go a long way.

This is a straightforward geo problem. When a call comes in, the system knows the fire location. Your fire engine has GPS. The hydrants have coordinates. Combine those three data points and you can tell the crew: "Nearest accessible hydrant is at [X]. Park here. Lay two 20m hoses."

No guessing. No one craning their neck out the window. No extra hose connections that add risk and weight.

I proposed this in 2017 during my NS days (November 2017 to July 2019). The answer: they couldn't get the raw data, and I'd need to talk to officers higher up the chain. But there's no real mechanism for an NSF to escalate a ground-up idea like this. You can't just keep asking to speak to the next rank above you. These sorts of initiatives should come from the ground, and there should be a way to bring them up. But there isn't one for a 21-year-old full-time firefighter.

I joined GovTech in 2022 and thought: finally, I'm inside the machine. I pushed the same idea again. The answer was that this was probably something HTX should handle, not GovTech. What frustrated me was that GovTech could have engaged HTX, could have started a conversation across agencies. They didn't. They just defined it out of scope and the ball went dead.

It's 2026 and I don't see any sign of this out there, but that doesn't mean nobody's working on it. I just don't know anymore. There are more fires now than when I served, with shorter manpower.

The part that frustrates me most is the data argument. Fire hydrant locations are not sensitive. They are metal fixtures bolted to the pavement. Anyone with a phone could map every single one in Singapore by walking the streets for a few weekends. So why is this not on data.gov.sg?

If the data were public, civilians could have built this tool for free years ago. SCDF could trial it and if it works, hire the person or buy the solution. Agencies love to say they want innovation from the ground up. But they won't publish the data that would let people innovate.

Twice I brought this up. Twice it got handed off to someone else's problem. I'm not in a position to push anymore. But I still wonder: who owns this problem now?