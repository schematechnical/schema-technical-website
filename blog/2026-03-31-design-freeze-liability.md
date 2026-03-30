---
title: "Design Freeze Checklist: The Serviceability Questions Your R&D Team
  Forgot to Ask"
date: 2026-03-31T08:15:00.000+01:00
---
By Dan Howes, Schema Technical

**Zone 19 and the Cost of an Afterthought**

On the Tornado GR4, there was a zone called Zone 19.

It sat just behind the cockpit. A tight tunnel running top to bottom of the aircraft. Control rods, cockpit wiring, Environmental Control System (ECS) pipework, all crammed into a space barely big enough to work in.

The ECS pipework failed regularly. That was the routine problem.

But to get to it, you had to enter from the bottom. The pipes were at the top. And sitting right in the way was the Radar Homing Warning Receiver (RHWR) crate, a heavy unit packed with computers that really did not like being disturbed. Remove it to access the pipes, and you triggered a cascade of functional tests. Tests that almost always failed. Days of fault-finding, just to get back to where you started.

In a deep maintenance bay, it was manageable. You would fit the crate last and move on.

On a front-line squadron, the situation was entirely different. The workaround became institutional. Jets would have a Limitation (LIM) written in the LIM LOG: RHWR crate removed, radar warning system not functioning.

They just left it out.

A mission-critical system, routinely absent from front-line aircraft, not because it was broken, but because the cost of reinstating it was too high.

Nobody designed Zone 19 to be a liability. But that is exactly what it became. The pipework failure was not the problem. The access was not the problem. The crate was not the problem. It was the combination, and nobody had modelled what that combination would cost once the aircraft was in operational service.

I saw this pattern more than once during my time in the RAF. Designs that made complete sense on paper, but had never been examined from a maintenance perspective. The result was always the same: workarounds became policy, and limitations became normal.

**A Hole Two Millimetres Too Small**

Years later, working in field service on complex life science capital equipment, I encountered a different aircraft. Different stakes, different environment, but a remarkably familiar story.

The single cell isolation device. Precision engineering, genuinely impressive clinical capability. One of its core components is a machined aluminium block, the base for a linear actuator that drives a flat plate through a controlled vertical movement.

The actuator wire runs from the unit and connects directly to a PCBA. To allow the cable to pass through the aluminium block, the design team had machined an arch-shaped cutout into the base.

The cutout was too small.

Not by much. But enough that when the actuator needed replacing, the connector on the end of the cable could not pass through the hole. You could not remove the actuator without first removing the aluminium block. You could not remove the aluminium block without disassembling the entire base structure to reach the fixing screws on its underside. A straightforward component swap became a full structural disassembly, a significant labour cost, and a device that was out of service for far longer than necessary.

The fix would have been a single line change in the CNC programme. A marginally larger radius on the cutout. It would have made no difference whatsoever to the structural integrity or stability of the block.

The person who designed that cutout was almost certainly not thinking about field replacement. They were thinking about the actuator, the cable routing, and the structural requirements of the block. All entirely reasonable things to think about. But nobody in that design process asked the question: what happens when this part needs to come out in the field?

That question was never asked. So it was never answered.
