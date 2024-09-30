# Questions
These may or may not be relevant to the report.

* What does it mean for the magnetic field to rotate if it is rotationally symmetric around the dipole axis?

I guess there are variations in the magnetic field (making it deviate from the symmetry) arising from the structure of Saturn's magnetic core, and it is really the core that is rotating and causing the magnetic field variations to rotate. However I've read that saturn's magnetic field is axisymmetric.

* How does the magnetic field generation in Saturn work? (MHD dynamo)

* What exactly are the mechanisms that make Saturn's magnetospheric plasma corotate with the planet?

Charged particles gyrate about magnetic field lines, but in reality there are no "lines", only a continuous vector field. But if the magnetic field varies in magnitude in the angular direction then this might carry the particles somehow, via grad-B drifts maybe. Gravitational drifts are too small (electrons drift about 56 micrometres per second in the orbital direction at Titan's orbit, positive ions drift *against* the orbit). Blanc et al (2004) and Regoli (2016) explain that the co-rotation is due to friction in the atmosphere and ionosphere of Saturn. But the angular speed of neutral particles decreases slowly with distance while the angular speed of ions increases (as expected for co-rotation, $v_\theta=\Omega^2r$) so my guess is that the friction is higher for ions which interact via coloumb forces as well (within a Debye length each).

* How is Titan's induced magnetosphere formed?

* What are pickup ions?

* What is mass loading?


# Terminology
If you are unsure about a word used in the sources and find out what it means then you can describe it here.

* The **ram** side of an object moving in a surrounding plasma or gas is the side where the particles are colliding with the object, and the **wake** side is the opposite side where a vacuum can form at high enough relative speeds.
* The **nose** of a magnetosphere is the region facing the external plasma flow, where the distance from the body to its magnetopause is the smallest. This is on the opposite side of the **magnetotail**.
* **Kronian** means "relating to Saturn" and **Jovian** means "relating to Jupiter".
* **cusps** are regions in the magnetosphere of a body near its magnetic poles where external charged particles can enter into its upper atmosphere.
* The **plasma sheet** is a region near the equator where the plasma density is high. In Earth's case it is located in the magnetotail while for Saturn it is found at all longitudes.
* **lobes** are the regions outside the plasma sheet where the plasma density is lower. There is a north lobe and south lobe.
* **substorms** are sudden (tens of minutes) decreases in meridional magnetic field strength at the surface of a planet, at latitudes of $65\degree$-$75\degree$ for Earth. These occur several times a day at Earth and are associated with aurora and particle precipitation. (Spohn et al, 2014, section 7.5).

# Sources
## Encyclopedia of the solar system, 3ed -- Tilman Spohn et al (2014)
Chapter 7 is about planetary magnetospheres and section 6 in the chapter is about interactions with moons. Chapter 6 is about magnetic field generation (dynamo). This book can provide explanations for concepts that are assumed to be familiar to the reader in published articles.

**Section 6.5.4**

Saturn's magnetic field multipole expansion is dominated by its dipole term, and is unique in that it only consists of axisymmetric terms (as far as has been observed). 

**Section 7.1**

A magnetosphere is a region around a body in space which is partially shielded from external plasma flow by its own magnetic field exerting magnetic pressure against the flow. However, even bodies with no intrinsic magnetic field can form cavities in the plasma flow which have properties that are similar to true magnetospheres. The magnetopause is the surface defining the boundary of the magnetosphere. The term magnetosphere was originally defined as a region above the Earth's ionosphere, but the term has since expanded to include similar phenomena around other bodies in space, including moons. 

Some bodies in the solar systems lack a substantial intrinsic magnetic field. Among these are Mars, Venus, and all moons except the Jovian moon Ganymede. If the body has a conductive interior or an ionosphere, then currents are induced that create forces that oppose the incoming external plasma flow (solar wind or magnetospheric plasma). This results in an induced magnetosphere around the body.

**Section 7.2.3**

In section 2.3 the newly ionized gases emitted from comets are referred to as "pickup ions". These are "swept up" by the solar wind, transferring energy from the wind to the pickup ions.

**Section 7.4.1**

Most of the plasma in planetary magnetospheres comes from the sun, and some comes from particles in the ionosphere which have gained enough energy to escape. The plasma in the ionosphere is generally cold in comparison to the magnetosphere and has a similar composition to the planet's atmosphere.

**Section 7.4.2 Energetic particles**

All magnetospheres in the solar system contain populations of highly energetic particles which deviate from the thermal equilibrium Maxwell-Boltzmann distribution function. The observed fluxes of such particles are too high to be solely accounted for by the solar wind. In the cases of the gas giants, some particles are accelerated to high energies by planetary rotation. These high-energy particles also create strong currents around the equator which in turn modify the magnetic field. The significant populations of energetic particles in the gas giants' magnetospheres result in an expanded magnetopause due to the increased pressure. Energetic particles at the gas giants can be lost via absorption by their rings and satellites.

**Section 7.5 Dynamics**

The Cassini spacecraft which was in orbit around Saturn for 13 years between 2004 and 2017 \parencite{cassini-2019} (it ended its mission by crashing into Saturn's atmosphere in 2017, the year after this edition of the book was published) has provided much more detailed observations of the dynamics of the Kronian magnetosphere than those from the Pioneer 10 and Voyager 1 and 2 spacecraft which only briefly passed through it. 

Saturn rotates at approximately the same rate as its magnetic field, and this rotation period changes during Saturn's orbit around the sun.

Cassini was equipped with an instrument that took pictures of particle fluxes in the magnetosphere. This detector can be likened to a telescope which collects neutral particles instead of photons. High-energy neutrals result from collisions with energetic ions and therefore the observations provide information about the magnetospheric plasma.

**Section 7.6 Interactions with moons**

Titan is a weaker plasma source than the inner moon Enceladus which emits large amounts of vapor that is quickly ionized, forming a torus of plasma around Saturn. 

The magnetic field around Titan changes rapidly only very close to its surface since it has no intrinsic magnetic field. In contrast to the planetary magnetospheres, the induced magnetosphere of Titan has no bow shock since the oncoming plasma flow is slower than both the Alfvén speed and the sound speed. Instead Alfvén wings form in front of the moon.

** Section 38.1.2 Titan's exploration

## Fundamental planetary science -- Jack J. Lissauer & Imke de Pater (2019)
A planet or moon that has an ionosphere will form an induced magnetosphere if charged particles are flowing past it (section 7.2.4). This induced magnetosphere shields the body from the external magnetic field. Titan in Saturn's magnetosphere is an example of this.

The interior of Saturn is fluid metallic hydrogen which is conductive (section 7.4.2). It is generally assumed that Saturn's magnetic field is produced by a process called "magnetohydrodynamic dynamo". Saturn's magnetic dipole moment is nearly exactly in the same direction as its angular velocity (geographic north and south poles coincide with the magnetic north and south poles) (section 8.2.3 and 7.3).

## Interaction of Titan's ionosphere with Saturn's magnetosphere -- Andrew J. Coates (2009)
This review focuses on particle measurement data from the Cassini flybys of Titan in 2004.

Titan has no internally generated magnetic field, but it has an ionosphere within a nitrogen-methane atmosphere. The moon is almost always within Saturn's magnetosphere, meaning it is (partially) shielded from the highly energetic solar wind. The closest Titan is to Saturn is $a(1-e)\approx 19.68 R$ where $R$ is the radius of Saturn. According to *Fundamental planetary science*, the magnetopause of Saturn is located at $19R$ at the sun-facing side. Since solar activity varies, this point probably also varies with time. The magnetic field drapes around the planet, so the moon only has a chance of entering the magnetosheath at this point.

There are two flows of charged particles across Titan. One is from the Sun and one is from Saturn's magnetospheric plasma. The plasma corotates with Saturn, which at titan's orbit (about 20 saturn radii) implies that it is orbiting faster than Titan is, or than what would be expected if the particles were simply following keplerian orbits (show this mathematically and quantify it). This means that the ram side of this plasma flux is in the opposite direction to the moon's velocity rather than in the same direction, at least in an inertial reference frame fixed to Saturn. The flow of particles from the sun and from the magnetospheric plasma have two different directions which change during the local day on Titan.

## Solar system magnetospheres -- Blanc, M., et al. (2004)
This article is from 2004 right before the Cassini flybys of Saturn, so the information is not completely up-to-date. They list some questions for the Cassini mission to answer, so it would be interesting to see if these questions are answered in other sources which discuss the Cassini observations.

Section 5 is about the interactions between satellites and the magnetospheres of giant planets and 5.3 is specifically about the interactions of Titan with Saturn's magnetosphere.

There are several sources and sinks of neutral and charged particles inside Saturn's magnetosphere. The sources include Titan's and Saturn's neutral atmospheres, their ionospheres, Saturn's rings and inner icy moons (sputtering), and the interstellar and solar winds. Saturn's magnetosphere actually consists mostly of neutral particles. Neutral particles follow keplerian orbits until they collide or get ionized by radiation or collisions with energetic ions or electrons.

The plasma of the magnetosphere co-rotates with Saturn due to friction with its atmosphere and ionosphere. It is mostly concentrated at the equator. However, while the rotation speed of ions increases with radial distance, the rotation speed of neutral particles decreases slowly (more slowly than $\sqrt{\mu/r}$?).

Titan forms a torus of ions (mainly $\text{N}^+$, $\text{N}_2^+$, $\text{H}_2\text{CN}^+$) around Saturn by releasing them via its plasma wake. This was detected by the Voyager 1 flyby in 1980.

## The interaction between the magnetosphere of Saturn and Titan's ionosphere -- Andrew F. Nagy, et al (2001)
This paper presents a 3D MHD simulation of the interaction between Saturn's magnetosphere and Titan's ionosphere. Before the Cassini flybys. 

Variations in the solar wind cause compression and expansion of Saturn's magnetosphere, meaning Titan can sometimes be outside the magnetosphere although it has not been observed yet (as of this paper! It has been observed to be in the magnetosheath and in the solar wind by the Cassini spacecraft, see WHERE? I don't remember where I read this...). When it is outside the magnetosphere, Titan's ionosphere interacts with the solar wind directly leading to very different conditions.

They study three different classes of ion species; light, medium and heavy. In the results they present plots of number density of these different species as well as plots of the magnetic field and plasma speed around Titan. These are nice images to include in the report.

The results of the paper might be slightly inaccurate since the gyroradius of the ions is large meaning the MHD model might exclude some observed details.

## Titan interaction with Saturn's magnetosphere: Voyager 1 results revisited -- E. C. Sittler Jr., et al (2005)
In this paper the authors present results from the re-analysises of the plasma measurement data from Titan flyby by Voyager 1 in 1980, using new (at the time) models.

## Titan's exosphere and its interaction with Saturn's magnetosphere -- Iannis Dandouras, et al (2008)
## Titan’s interaction with the Saturnian magnetosphere -- Leonardo H. Regoli (2016)
PHD thesis. I (björn) think we use this as a source sparingly if at all in the report and instead go to primary sources when possible. But it is useful for us to learn and get a picture of the subject.

A "ring current" is created in Saturn's magnetosphere from the opposing (gravitational, I assume) drifts of negatively and positively charged particles in the plasma. This is confined to the current sheet which is concentrated at the equator due to the centrifugal forces in the rotating noninertial reference frame.

## Discrete classification and electron energy spectra of Titan's varied magnetospheric environment -- A. M. Rymer et al (2009)
This study classifies the magnetospheric environment on Titan into four different categories based on electron thermal data from 54 encounters on titan by Cassini.

Plasma sheet:

The plasmasheet contains high energy electrons whose peak enegy is on the oder of 100s eV. The electron density is also high in this region with fluxes at $10^6cm^{-2}s^{-1}sr^{-1}$. This was the most common environment encountered with 19 encounters.

Lobe-like:

This class also has high energy electrons, with peak energies similar to or higher than that of the plasmasheath. The electron density is however smaller with fluxes an order of magnitude less. 8 encounters with this environment was made.

Magnetosheath:

This region is encountered outside of the magnetopause, and thus consists of plasma from the solar wind. In this region electrons are of lower energy, but higher density than the previous two classes. 2 encounters with this environment was made.

Bi-modal:

This classification is highly variable, containg two seperate electron populations, hence bi-modal. One is similar in energy to the plasma sheet or Lobe-like category. The other population is less energetic but more dense and consists of so called local pick-up population that comes from a neutral cloud, where produced electrons are quickly picked up by the co-rotation gaining energy in the order of tenths of eV. The electron energy seen is higher though, which is thought to be explained by these electrons originating from photoionization of larger ions where the energy released is on the order of 10eV. These heavy ions are believed to be water groups, which originate in the inner magnetosphere of Saturn, from the moon Enceladus and migrates outwards to Titan. 5 encounters of this environment was made.
## An empirical model for the plasma environment along Titan’s orbit based on Cassini plasma observations.  H. T. Smith and A. M. Rymer. (2014)
Continuation of pevious rymer paper. This paper further examines more encounters by cassini establishing that 45% of encounters are plasma sheath, 38% are lobe-like, 6% magnetosheath. The plasma envionment along Titans obit, when the planet is not cuently pesent is also examined, here 55% of encountes are plasma sheath, 24% are lobe like and 12% are magnetosheath. This suggest that the precence of Titan lowers the probablity of expeiencing the magnetosheath, meaning that Titan extends the magnetopause of Saturn outwards. This conclution cannot however yet be drawn due to, acording to the authors,possible sampling bias that needs to be analysed more rigouresly.   

## Alfvén Wing-Like Structures in Titan's Magnetotail During T122-T126 Flybys -- Niklas J. T. Edberg and Jan-Erik Wahlund and Erik Vigren (2024-06-09)


# Other notes
Saturn has a day of about $10.5\text{ hr}$ and an equatorial radius of about $58 232\text{ km}$. This implies a velocity of about $2\pi R/T\approx 9.7\text{ km/s}$ at the equator, compared to $464\text{ m/s}$ at Earth's equator. For this reason, Saturn's plasma sheet is spread out over all longitudes while Earth's plasma sheet only exists in the magnetotail on the night side.

Titan has no intrinsic magnetic field and is the only moon in the solar system with an atmosphere. Its interaction with the surrounding plasma is therefore unlike that of other moons and more similar to that of Venus and Mars.
