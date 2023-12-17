# Van Automotive High-Side 8-channel Electronic Relay PCB
These boards are 8-channel Electronic Relays - where you can turn things on/off on the plus wire. This is also called 'High-Side switching'. For simplicity these boards use P-channel MOSFETs (Positive Channel MOSFETs)

```
 Q: What is this board good for?
 A: Automotive (Car, Van and RV) use - as this board turns power on/off on the plus wire
```

Being able to switch on/off on the plus wire is of particular use in Cars and Vans, as the minus wire is typically replaced by using the metallic chassis of a car or van. And thus it becomes very necessary to be able to operate on/off switches on the plus wire. 

These boards will work for both 12V and 24V battery systems.

> The design of these PCBs are inspired by [Everlanders.com](https://everlanders.com/)
> 
> Especially this YouTube Video: [Designing and Building Custom P-Channel Driver PCB's in Mexican Lockdown](https://www.youtube.com/watch?v=AL1_fvPZXMk&t=2029s&ab_channel=Everlanders)
>
> These PCBs are however a complete re-design. Only some placements, of some of the components, are the same. 

So far this collection of PCBs consists of 
 - Version C3
    - 104 x 80 mm PCB - 114 x 80 mm Envelope
 - Version C4
    - dual MOSFETs - for each channel
    - 100 x 84 mm PCB - 100 x 84 mm Envelope
 - Version C4-F
    - dual MOSFETs and a fuse on the PCB - for each channel
    - 100 x 84 mm PCB - 100 x 84 mm Envelope


These PCBs can be made/configured in different modes of how many ampere each channel can handle. 

 - Mode A) - Each channel can handle about 5 amp
 - Mode B) - Each channel can handle about 10 amp 
 - Mode C) - Each channel can handle up to about 30 amp 
 
 Mode C) will for the C3-F PCB, and the C4-F PCB require the use of blade connectors, and not the otherwise very nice 45-degree-angled spring-loaded Molex connectors.

It is possible to combine channels (in parallel) so larger amp loads can be controlled. 

For further details see the [Wiki](../../wiki)

### What is unique about versions C3 and C4?
**The C3 versions** of PCBs are 104 x 80 mm
 - An envelope of 114 x 84 mm is needed when mounting the MOSFETS for mode B) or mode C). 
 - All components can be placed on one side of the PCB, except the MOSFETs. 
 - in mode A) the MOSFETSs are placed on the underside of the PCB
 - in mode B) or mode C) the MOSFETs are placed on an underlying heatsink (114 x 80 mm)


**The C4 versions** of PCBs are contained within a 100 x 83 mm PCB envelope 
 - the 100 x 83 mm include corner mounts, screw holes and PCB, 
 - and includes mounting holes for the underlying MOSFETs - for all modes of mounting the MOSFETs. 
 - Components are placed on both sides of the PCB, and some components are very finicky to place, and require hand soldering.
 - in mode A) the MOSFETSs are placed on the underside of the PCB
 - in mode B) or mode C) the MOSFETs are placed on an underlying heatsink (100 x 80 mm, or possibly 100 x 100 mm).

For further details see the [Wiki](../../wiki)
