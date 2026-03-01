---
title: "Design for Manufacturing (DFM) vs Design for Service (DFS): "
date: 2026-02-28T19:32:00.000+00:00
thumbnail: /images/blog/dfm_vs_dfs.jpg
---
## How to stop building disposable hardware








#### The sealed unit trap

It’s a common experience: mobile phones, electric toothbrushes
and the majority of consumer electrical devices that we buy are not designed to
be repaired.

Use the electric toothbrush as an example. You can replace
the brush head easily enough. But 2 years down the line the battery is failing.
It barely holds a charge and needs to be placed on the charge base every day or
you may as well use a manual brush.

Can you replace the battery? It’s almost impossible because
it’s a sealed unit. It makes sense. Gluing the case shut is faster and easier
during production. It is also better for Ingress Protection. However, it does mean
that toothbrush that costs £100+ is now waste and you must get a new one.

Apply this same logic to an expensive new device designed
for use in a hospital environment and it has a battery that needs to be
replaced on the annual Planned Preventive Maintenance schedule. If it requires
a glued unit to be pried open to access it and then needs to be glued shut
again afterwards, this becomes a return-to-base operation and takes the device
out of service for weeks, impacting hospital throughput and patient care. It
could have been a Field Service Engineer’s job whom you are paying hundreds of
pounds per day already and the task could be completed within 15 minutes if a
different method had been considered.

#### Design for Manufacture vs Design for Service

It is understandable how these situations arise. A new
product is in the design phase; budgets need to be managed carefully. Overspend
could mean the end of the product entirely. 

R&D engineers have been asked to lower the Total Unit Cost.
Glue is used instead of screws to close the case. It’s cheaper and faster to
build so it does exactly what’s been asked.

However manufacturing happens once. Service happens for 10
years+. Not using screws on the case potentially saves £5 in the factory. But it
costs a field service engineer 30 minutes extra work to split the case open if
it’s glued. That’s £10 for the time alone not to mention the case has the
potential to get damaged which would impact the Ingress Protection.


The initial aim is to manufacture the device with cost
saving in mind, but it is certainly prudent to consider how the system will be
serviced in the future and weigh up the cost benefits of both DFM and DFS. Having
units shipped back to base for parts that can be replaced in the field just
because glue is cheaper has a longer-term cost than what it saves initially. 



#### Why this matters now

Currently in the EU there is the Right to Repair (EU
Directive 2024/1799) regulations for consumer goods. These state that:

Manufacturers must ensure:

1. Spare parts are available for a
   minimum period (usually 7-10 years).
2. Repair manuals are accessible to
   professional repairers.
3. Products can be disassembled
   using common tools (no glued casings or proprietary screws).

This means that the sealed unit strategy isn’t just annoying
anymore, but it is becoming illegal.

Whilst this is not a direct regulation for Medical Devices,
it is certainly something that should be considered. The EU's "Eco-design
for Sustainable Products Regulation" (ESPR Regulation (EU) 2024/1781) is
expanding. It pushes for durability, reusability and repairability across all
sectors.

Take the NHS Net Zero policy as a prime example of this.
They have legally committed that by 2040 they will be net zero on carbon emissions
(that they directly control, by 2045 emissions that they influence i.e.
suppliers). 

Since April 2023, for all contracts above £5m (and
increasingly for smaller ones), suppliers must have a published Carbon
Reduction Plan or Net Zero Commitment for smaller contracts. If you don't have
one, you cannot bid.

A large proportion of the NHS's carbon footprint comes from
the medical devices they buy. 62% of their carbon footprint is attributable to
the supply chain. Medical equipment and Pharmaceuticals making up most of that.

* Bad Design: A device that
  lasts 3 years and then goes to landfill = High Carbon Footprint.
* Good Design: A device that
  is modular, repairable, and lasts 10 years = Low Carbon Footprint.

A modular device that lasts 10 years distributes its
manufacturing carbon (embedded carbon) over a much longer service life than a
disposable device lasting 3 years. By facilitating repair (DFS), manufacturers
directly reduce the carbon intensity per year of service, a metric that is
becoming increasingly pivotal in "Value-Based Procurement”.

Design for Service isn't just about saving repair costs; it's
about reducing the carbon footprint of the device.

####  

#### Design for service quick tips

Here are three quick tips that are great for service and
sustainability.

* Captive Screws: Great for
  FOD (Foreign Object Debris) prevention. Critical in surgical environments.
  Various medical safety standards also encourage designs that prevent loss of
  fixings. Use quarter-turn fasteners to reduce MTTR (Mean-Time-To-Repair).
* Error Logs: Use secure
  telemetry or an authenticated port to allow users to send encrypted log files
  via a hospital or cellular network back to customer support. Having error logs
  available before a site visit can often indicate user error, or specific part
  failures. Allowing Service Engineers to arrive onsite with the correct parts
  and tools for a First Time Fix (FTF).
* The "Wearable"
  Parts: Identify high-wear items (tubing, batteries) and aim to reduce MTTR.
  Most devices will require Planned Preventive Maintenance (PPM) on an annual
  basis (or at varying intervals). Consequently it is logical that the parts
  which need to be replaced are easily accessed. If a hospital has 10 of your
  devices on one ward, the difference between easy access and difficult to access
  could cost you an extra day on site just for PPM work.

#### Bridge that gap

By being mindful of Design for Manufacture and Design for
Service you can ensure that your device is built for total cost effectiveness.
Not necessarily the cheapest build, but long term the smartest choice is to let
Service work hand in hand with R&D.

Does your current prototype suffer from the ‘toothbrush trap’?
If you are unsure then it might be time for a Service Design Review before it’s
too late.
