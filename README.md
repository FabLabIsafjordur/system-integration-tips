### System integration tips from Fab Lab Ísafjörður

Here are a few tips that might be useful for System integration week:

You can embed mesh fabric into 3D prints and make a cable carrier:

[![3D printed cable carrier](https://fab.cba.mit.edu/classes/865.24/people/svavar/components/images/cable_carrier/cable_carrier.jpg)](https://fab.cba.mit.edu/classes/865.24/people/svavar/components/cable_carrier/)

<a href="https://fab.cba.mit.edu/classes/865.24/people/svavar/components/cable_carrier/"><video autoplay="true" loop="true" src="<video controls src="https://fab.cba.mit.edu/classes/865.24/people/svavar/components/images/cable_carrier/cable_carrier.mp4" title="3D printed cable carrier"></video></a>

Svavar made this as a response to Nikhil Lal's question on Discord about how we were managing cables. Cedric Honnet posted this:

"Cables can be protected by [articulated](https://www.amazon.com/Plastic-Machine-Carrier-Ted-Lele/dp/B074S2GQ56/?th=1), [braided](https://www.amazon.com/Keco-100ft-Expandable-Braided-Sleeving/dp/B07K1WP871?th=1) or [hybrid wrappers](https://www.amazon.com/Management-Diameter-Organizer-Expandable-Concealer/dp/B07PPR47ZV/?th=1)".

Vineet Padia mentioned [a way to document wiring harnesses](https://github.com/wireviz/WireViz).

A nice example of the importance of packaging:
<table style="width:100%">
  <tr>
    <td>Virtual detents were developed by Jesse Schoch:
    
    <a href="https://youtu.be/1gPQfDkX3BU?si=Nw4lrJQ-mKGDoMy1&t=859"><video autoplay="true" loop="true" src="virtual_detents.mp4" title=""></video></a>
    </td>
    <td>But the method didn't become popular until it was packaged as the SmartKnob by Scott Bezek:

    <a href="https://youtu.be/ip641WmY4pA?si=FMXZIBXmvUoXk3_i"><video autoplay="true" loop="true" src="smartknob_detents.mp4" title=""></video></a>
    </td>
  </tr>
</table>

A good [quote](https://makezine.com/article/digital-fabrication/machining/18-lessons-smart-prototyping-self-made-billionaire/) from Dan Gelbart:
>I cannot overemphasise the importance of making everything with keyholes and slots and captive hardware. If you spend all your life in R&D you’ll spend about one year of your life taking screws out of covers, so if you do it in slots, it’s the same as extending your life by the same amount of health food plus exercise extends your life, and it’s much simpler.

Dan Gelbart's classic notes on quick prototyping: [Part 1](https://people.ece.ubc.ca/leos/pdf/tools/machine/DGCourseNotes.pdf), [Part 2](https://people.ece.ubc.ca/leos/pdf/tools/machine/DGCourseNotes2.pdf)

Good ways to document electronics on a website:
- [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom)
- [Kicanvas](https://kicanvas.org/)

[Food safe design principles](https://www.meatinstitute.org/sites/default/files/original%20documents/Sanitation%20booklet%202021.pdf) (inert materials, simple shapes that are easy to clean, smooth surfaces, no crevices where water collects and bacteria can grow)

Safety features: A colleague at an Icelandic company put two buttons far apart on a silicone molding press. The operator needs to push the buttons with both hands to operate the press, to eliminate the chance of getting their hand crushed:
![Design for safety](https://www.osha.gov/sites/default/files/inline-images/pb11.gif)*Image from [OSHA](https://www.osha.gov/etools/machine-guarding/presses/two-hand-controls#mod1)*

A QR code on the device that points to the manual can be a nice touch.

It's good for students to know that pogo pins and slip rings exist.

Design 3D printed enclosures with [shadow lines](https://youtu.be/8dhFhU7Nl_0?si=9pBpZQx7DmvqgBTx) like they do for injection molding.

Asymmetrical holes, so that you can't assemble the wrong way:
![Asymmetrical holes](https://files.svavar.cc/fab/fab_lab_isafjordur_injection_mold_by_johannes_konrad_weber.jpg)

Pre-load things to eliminate rattle - use e.g. spring washers. 
- [Automotive buzz, squeak and rattle book](https://www.amazon.com/Automotive-Buzz-Squeak-Rattle-Mechanisms-ebook/dp/B006NVY2VS) 
- [Development of the Saab squeak and rattle design guidelines](http://www.diva-portal.org/smash/get/diva2:215325/FULLTEXT01.pdf)

Usability: Would the device benefit from a small battery or capacitor to keep the clock running while it's not connected to power?

[The work that comes after the first rough prototype](https://youtu.be/caYl8u7Gd0A?si=M49v6m-484e8k_2f) 

Design for repair: The amplifier unit in this PA speaker has a generous cable length, so Þórarinn could pop it out and troubleshoot: 
![PA speaker repair](https://files.svavar.cc/fab/speaker_repair.jpg)

[Right to repair](https://en.wikipedia.org/wiki/) 

[Repair cafe](https://www.repaircafe.org/en/) (we host those at Fab Lab Ísafjörður, the atmosphere is great and it boosts community engagement with the lab)

