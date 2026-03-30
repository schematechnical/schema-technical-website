---
title: "Design Freeze Checklist: The Serviceability Questions Your R&D Team
  Forgot to Ask "
date: 2026-03-30T13:09:00.000+01:00
thumbnail: /images/blog/gr4.jpg
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

**Why This Keeps Happening**

These two examples are separated by industry, by decade, and by context. One is a combat aircraft. The other is a laboratory instrument. But the failure mode is identical.

In both cases, the design was technically sound. In both cases, the component performed its intended function. In both cases, the problem only became visible once the device left the controlled environment it was built in and entered the reality of operational use.

This is not a story about bad engineers. The engineers who designed Zone 19 and the Cell Isolation device base structure were not incompetent. They were focused on performance, on function, on getting the design to the point where it worked. That focus is exactly what you want from an R&D team.

The problem is structural, not individual. In most hardware development programmes, serviceability is either addressed too late, or not addressed at all. It is not part of the design conversation. It surfaces for the first time when a field engineer opens a panel and realises what they are actually dealing with.

By that point, the bill of materials is locked. The tooling is cut. The validation is complete. Any change carries a cost that the business is rarely willing to absorb. So the field engineer adapts. The workaround becomes the process. The limitation becomes the norm.

And somewhere in the background, margins erode.

**The Questions That Should Be Asked Before Design Freeze**

The good news is that serviceability problems are almost always preventable. Not through expensive redesigns or late-stage interventions, but through asking the right questions at the right point in the development process, before the design is locked.

These are the questions that should be part of every design review for any hardware that will require maintenance in the field.

**Access**

Can a field engineer physically reach every component that is likely to need replacement? Is the access route clear of other systems that will require removal first? If the answer is no, what is the maintenance burden of that access path?

**Connector and cable clearance**

Can every connector, cable assembly, and harness be removed and refitted without disassembling surrounding structures? Have clearance requirements been modelled with the connector fitted, not just the cable?

**Removal sequence**

What is the complete removal sequence for every Field Replaceable Unit? How many steps does it involve? How many other components need to be disturbed? Has anyone timed it?

**Functional test impact**

Which components, when removed, trigger functional tests or recalibration requirements on reinstatement? What is the realistic time and failure rate associated with those tests? Has that cost been factored into the service model?

**No Fault Found risk**

Which components are most likely to generate No Fault Found returns? Are those components easy to remove and refit, or does the removal process itself introduce risk of damage or misalignment?

**Tooling and access equipment**

Can all maintenance tasks be completed with standard field service tooling? Are there tasks that require proprietary jigs, fixtures, or calibration equipment that a third-party engineer would not have access to?

**Documentation readiness**

Does validated, visual work instruction documentation exist for every maintenance task? Is it written for a competent engineer who has never seen this device before, or does it assume knowledge that only your R&D team holds?

None of these questions require a serviceability specialist to ask them. But in practice, they are rarely asked systematically, and almost never asked early enough. The consequence is a device that performs brilliantly in clinical evaluation and becomes an operational liability at commercial scale.

If your device is approaching design freeze and these questions have not been formally addressed, that is the moment to act. Not after the first field return. Not after the first warranty claim. Now, while changes are still possible and the cost of addressing them is measured in engineering hours rather than margin erosion.

At Schema Technical, the Service Design Review exists specifically for this stage of development. A structured, forensic audit of your hardware before the design locks, identifying the maintenance risks that are invisible on a CAD model but unavoidable in the field.

If you would like to understand where your device sits before freeze, get in touch directly at dan@schematechnical.co.uk
