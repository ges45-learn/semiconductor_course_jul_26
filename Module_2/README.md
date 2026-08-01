# Module 2: Semiconductor Materials and Their Properties

## 2.1 Goals
* Classify the range of materials used to manufacture integrated circuits: semiconductor – silicon, germanium; insulator and conductor materials like silicon dioxide, copper
* Explain the preparation of semiconductor materials and the photolithographic process in semiconductor manufacturing
* Explore the engineering of new semiconductor materials

## 2.2 Discussion: defining a semiconductor

## 2.3 Atomic structure and electron behaviour
* Are electrons really free particles that travel around the material?
* Why do some materials conduct electricity well, but some don't?
* To visualise this, draw a diagram of a photoelectric effect experiment setup
  * https://openstax.org/books/university-physics-volume-3/pages/6-2-photoelectric-effect
  * This setup **includes** a quartz tube containing a vacuum with a red photocathode on the left and a blue anode on the right. Light is **shown** entering the tube and striking the photocathode, causing electrons **to be emitted** and move towards the anode. The circuit includes a voltage source for the stopping potential ($V$), connected in series with an ammeter ($A$)
* How does the photoelectric effect challenge classical physics, and what does its behaviour reveal about the nature of light and energy transfer at the quantum level?
* If a person is a wave, why don't they diffract when they walk through a door like light passing through a slit?
* How does the wave-particle duality of electrons challenge our classical understanding of motion and location, and what does this mean for how we observe and measure particles at the quantum level?
* link: https://openstax.org/details/books/university-physics-volume-3?Book%20details

## 2.4 Energy bands in solids
* Atomic structure
  * How many protons and neutrons are found in the nucleus of a **silicon** atom?
  * How many electrons surround the nucleus, and how are they distributed across electron shells?
* Bonding behaviour
  * When **silicon atoms** come close together, what type of bonding do they form?
  * How many neighbouring atoms does each silicon atom bond with?
  * How many electrons are shared in total during bonding?
* Crystalline structure
  * What type of lattice does silicon crystallise into?
  * Does this lattice share a similar pattern with any **other** element?
* Insulator, conductor and semiconductor
  * How does the difference between the energy levels of the valence **band** and **conduction** band affect the conductivity of the material?
    * Insulators: SiO2, Si3N4, low-k dielectrics (https://www.doitpoms.ac.uk/tlplib/dielectrics/intro.php)
    * Conductors: Cu, Al, W
    * Semiconductor: Si, polysilicon
* Quantum tunnelling
  * Does an insulator always stop electrons from passing through?

## 2.5 Charge carriers in semiconductors, carrier mobility and electric fields
* **For silicon** at 300 K, calculate:
  * electron mobility
  * hole mobility
  * Based on your results, which carrier is more mobile in silicon, and what does this imply about their effective mass?
  * If the electric field was halved, what would be the new drift velocity for both electrons and holes, assuming mobility remains constant?

## 2.6 Manufacturing: Silicon wafer production
* Why is high-purity **silicon** (11N) required? What is the impact of impurities?
* https://semiconductor.samsung.com/support/tools-resources/fabrication-process/eight-essential-semiconductor-fabrication-processes-part-1-what-is-a-wafer/

## 2.7 Manufacturing: Doping and photolithography
* How do precise fabrication techniques, like ion implantation, contribute to the performance and reliability of modern semiconductor devices?

## 2.8 Manufacturing: oxidation process
* https://tinyurl.com/33k99vbt
* Research and draw a cross-section of a typical transistor used in integrated circuit fabrication. On your diagram, try to label regions that are **intrinsic** and **extrinsic**. Once your drawing is complete, label the following:
  * pure silicon
  * doped **silicon**
  * silicon dioxide
  * deposited material

## 2.9 Engineering gallium nitride (GaN)
* https://www.doitpoms.ac.uk/tlplib/epitaxial-growth/printall.php
* How do material properties **influence** the performance of **electronic** devices, and why might engineers choose compound semiconductors over **silicon** for certain applications?
* https://lampz.tugraz.at/~hadley/ss1/crystalstructure/structures/semiconductors/GaN.html
* https://www.powerwaywafer.com/1-1crystal-structure-of-nitrides.html
* Using the visualisation of GaN: examine the unit cell parameters, adjust the visual representation **and** interact with the hkl planes:
  1. Explore the cell parameters: use the information to identify the lattice parameters ($a$, $b$, $c$, $\alpha$, $\beta$, $\gamma$) for the wurtzite structure
     * How do these **parameters** reflect the characteristics of a hexagonal crystal system?
  2. Manipulate the visualisation. Use the JSmol controls to switch between the conventional unit cell, **asymmetric** unit, and different display styles such as Ball and Spacefill
     * What differences do you notice between the conventional and asymmetric unit cells?
  3. Investigate hkl planes
     * What roles do these planes play in XRD and crystal orientation (**Bloch's** theorem)?

## 2.10 GaN in action: real-world applications
* Think back to what mobile and laptop chargers were like when you first started using these devices:
  * What **do** you remember about the size, weight, and durability?
  * Were they convenient?
* Current expectations:
  * What qualities do you value most in a phone charger that you use every day?
  * Consider aspects like portability, charging speed, energy efficiency, and longevity
* How GaN might meet expectations:
  * In what ways could GaN-based chargers improve **your** daily experience compared to older technologies?

## 2.11 Quiz
* https://epc-co.com/epc/gallium-nitride/what-is-gan

## 2.12 Live session

## 2.13 Discussion: translating photolithography into semiconductor manufacturing
* What steps in the image translate directly to physical processes in a cleanroom?
  * draw the cross section from the layout
  * walk through the process
  * Ch 10.5 pg 428 CMOS technology, p 274 inversion layer 
* What challenges might arise when scaling this recipe to industrial **applications**?
* How might the materials, tools, and environmental conditions affect the outcome?

## Task 
* https://skywater-pdk.readthedocs.io/en/main/rules/layers.html#gds-layers-information
* chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://people.csail.mit.edu/brooks/idocs/JvN.pdf
* https://sky130-unofficial.readthedocs.io/en/latest/contents/libraries/sky130_fd_sc_hd/cells/nand2/README.html
  
