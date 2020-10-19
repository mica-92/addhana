---
title: "Bonding and forces"
date: 2010-10-06T00:19:29-04:00
slug: "BF"
description: "A brief guide to setup KaTeX"
keywords: []
draft: false
tags: ["MSE"]
math: true
toc: false
---
# Bonding & Bonding Forces and Energy


Atomic bonding (force and energy diagram)

## Bonding Forces and Energies

The net force (FN) between 2 atoms is just the sum of the attractive (FA) and repulsive (FR) force:

FN = FA + FR

The magnitude of each depends on the separation or interatomic distance (r). The origin of an attractive force FA depends on the particular type of bonding that exists between the two atoms. Repulsive forces arise from interactions between the negatively charged electron clouds for the two atoms and are important only at small values of r as the outer electron shells of the two atoms begin to overlap.

When FN = 0 the state equilibrium exists.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled.png)

We can write this as in terms of energy. EN (net energy) EA (attractive energy) and ER (repulsive energy)

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%201.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%201.png)

The bonding energy for two atoms corresponds to E₀, which is the energy at the minimum point, and r₀ is the equilibrium spacing between the two atoms.

### Properties of materials and bonding energies

- Materials having large bonding energies typically also have high melting temperatures; at room temperature, solid substances are formed for large bonding energies, whereas for small energies, the gaseous state is favored; liquids prevail when the energies are of intermediate magnitude.
- The mechanical stiffness (or modulus of elasticity) of a material is dependent on the shape of its force–versus–interatomic separation curve. The slope for a relatively stiff material at the r = r₀ position on the curve will be quite steep; slopes are shallower for more flexible materials.
- How much a material expands upon heating or contracts upon cooling (i.e., its linear coefficient of thermal expansion) is related to the shape of its E–versus–r curve. A deep and narrow “trough,” which typically occurs for materials having large bonding energies, normally correlates with a low coefficient of thermal expansion and relatively small dimensional alterations for changes in temperature.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%202.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%202.png)

### Thinking bonds as non-linear springs

Bonds can be thought of as a spring model. We can model the energy diagram, up till R₀, like a parabola and approximate it to a Hookean spring. 

In this analysis, we can relate the stiffness (K = U''(x) evaluated at R₀) with the molecules macroscopic properties

The 'problem' comes in R>R₀ where the graph starts being asymmetrical. 

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%203.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%203.png)

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%204.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%204.png)

**If materials were to behave like springs, the thermal coefficient would not exist**. That is while injecting energy into the system, the vibration becomes more violent, the average distance between atoms is increasing and this is what we term thermal expansion (blue line). 

### Pair potentials

To quantify the energy of a system of many atoms, we need to sum over many bonds. A **pair potential** is a function that describes the potential energy of two interacting objects. 

There are different pair potential models:

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%205.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%205.png)

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%206.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%206.png)

- **Hard Sphere Model** - Treat all the atoms as hard sphere the two different atoms have no interactive energy at all and if they interact they have infinite energy of repulsion.
- **Soft Sphere Model** Some kind of compressive interaction for lengths
- **Ionic/ Coulomb Model** - Ions can be capture their attractive interactions. You need something to represent the repulsive component (Born Mayer potential, the Madelung constant is always positive in order for crystals to be stable):

    ![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%207.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%207.png)

    ![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%208.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%208.png)

- **Lennard- Jones** - Both the attractive and repulsive component. It was obtained empirically**.**

    ![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%209.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%209.png)

    The r12 term, which is the repulsive term, describes Pauli repulsion at short ranges due to overlapping electron orbitals, and the r6 term, which is the attractive long-range term, describes attraction at long ranges (van der Waals force, or dispersion force).

    At rm the potential function has a value of -ε (this is the first derivative of U(x)), and the distance is related to rm = (2^1/6)σ = 1.22σ

    ![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2010.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2010.png)

- **Morse -** Similar to the Empirical approach that LJ. Longer distances go to 0 faster than LJ.

## Primary Bonds

## Ionic Bonds

Occurs between two atoms with disparate electronegativities (between a non-metal who accepts electrons and a metal element who donates the electrons). All the atoms acquire stable configurations and in the process they became electrically charged ions.

The attractive bonding forces are coulombic (positive and negative ions, by virtue of their net electrical charge, attract one another.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2011.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2011.png)

Ionic bonding is **non-directional** that is, the magnitude of the bond is equal in all directions around an ion. It is a very strong type of bond and molecules usually have high melting points. Energies range between 600 and 1500 kJ/mol

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2012.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2012.png)

**Increasing the distance means weaker ionic bond, since the center of charge is farther apart. Increasing charge for a given r greatly increases strength of bond**

## Covalent Bond

Found on molecules whose atoms have similar electronegativities, and the stable configuration is achieved by the sharing of electrons. Each atom contributes at least one electron to electronic configuration and valence shell electrons are shared. 

The bond is **directional,** meaning that the electronic density is aggregated between the two atoms. This feature may play an important role in polymers. 

Molecules formed may be polar or non-polar. In the latter electrons do not 'pick' one atom over another in proximity, while polar molecules (such as water) where there is an electronegativity different between atoms electrons will be selectively aggregated on the more electronegativity atoms (O). 

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2013.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2013.png)

### Bond Hybridization

**Hybridization** is the mixing of two or more atomic orbitals with the result that more orbitals overlap during bonding results. The main driver is energy minimization. 

This is very common in **Carbon (electronic configuration 1*s*²2*s*²2*p*²)**

- ***sp*³** - an electron from the 2s shell is promoted to the 2p shell. The resulting shells are similar in energy and give rise to four *sp*³ that are equivalent to one another. They form a tetrahedron surrounding the C- atom with 109.5 angles. Examples methane (CH4) and diamonds (C)
- ***sp*² -** in which an s orbital and only two p orbitals are hybridized (pz remains unhybridized). The angle between the atoms is 120 in this case. They are strong in the planar direction but not in the z- axes associated with the unhybridized bond. Example: graphite (C)

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/INK1.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/INK1.png)

- *sp*³*d*² - ****hybridization of 1s, 3p and 2d orbitals creating a total of 6 *sp*³*d*². Example SF6

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2014.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2014.png)

**What is going on in the electron cloud?** Since electrons are shared in a covalent bond, the strength of the bond depends on the degree of orbital overlap. This is affected by the proximity and shapes of the orbitals involved. 

Every time a bond is created a new QM system is born and that is going to be subject to its principles. There is a QM of quantify the overlap degree (overlap integral).

### Sigma and pi bonds

A **sigma bond (σ bond)** is a bond formed by the overlap of orbitals in an end-to-end fashion, with the electron density concentrated between the nuclei of the bonding atoms. There free rotation associated with sigma bonds.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2015.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2015.png)

A **pi bond (π bond)** is a bond formed by the overlap of orbitals in a side-by-side fashion with the electron density concentrated above and below the plane of the nuclei of the bonding atoms. They interact laterally instead of axially. There is a large energy cost for this type of molecules to rotate (they have to break the bond are re-form it; this is important in polymers, and creates issues such as cis/trans configuration).

- A covalent “double” bond has one σ bond and one π bond
- A covalent “triple” bond has one σ and two π bonds

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2016.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2016.png)

The C2H2 molecule contains a triple bond between the two carbon atoms, one of which is a sigma bond, and two of which are pi bonds.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2017.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2017.png)

### Bonding and anti-bonding molecular orbitals

When two atoms came together, example two H each with its own 1s atomic orbital, a new quantum system is form and the exclusion principle must be taken into consideration. The result is that the two identical levels 1s) must split, with one higher energy than the original level (antibonding orbital) and the other lower than the original level (bonding orbital). The number of atomic orbitals is always conserved the difference is the energy.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/INK2.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/INK2.png)

Bond Order = ½ [(# electrons in bonding MO) - (# electrons in antibonding MO)]

There is a correlation between a high bond order a the strength of the bond. Theoretically any BO>0 can be created but there might other reasons at play by which this are not stable molecules. Example HeH.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2018.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2018.png)

Only diatomic molecules can be truly covalent (Ne2), all other have an ionic character of varying degree. This explains why although Ne2 and CO have the same bond order (3), CO has a higher melting temperature (the % of ionic character makes the bond stronger).

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2019.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2019.png)

## Metallic Bonding

This type of bond is found in metallic elements (Group IA and IIA). The valence electrons are not bound to any atom in particular but they belong to the *metal as a whole,* usually called the electron cloud*.* The remaining non-valence electrons and its nuclei form the ion cores. **

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2020.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2020.png)

Metals are good conductors of both electricity and heat as a consequence of their free electrons. Energies range from 62 kJ/mol for mercury to 850 kJ/mol for tungsten

## Secondary Bonds

## Van Der Walls/ London bond

Weak in comparison with primary bonds (bonding energies range between about 4 and 30 kJ/mol). 

Secondary bonding forces arise from atomic or molecular dipoles. In essence, an electric dipole exists whenever there is some separation of positive and negative portions of an atom or molecule. The bonding results from the coulombic attraction between the positive end of one dipole and the negative region of an adjacent one. Dipole interactions occur between induced dipoles, between induced dipoles and polar molecules (which have permanent dipoles), and between polar molecules. 

VDW bonds explain why He atoms at -272 can form solid crystals. 

Dipoles may be permanent, meaning the molecule in itself if polar or induced, otherwise non-polar molecules when they come in close proximity they induce a dipole (like two H2 interacting with one another. The net effect of dipole-dipole interaction is to induce correlation and aggregation.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/INK3.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/INK3.png)

The strongest secondary bonding type, the hydrogen bond, is a special case of polar molecule bonding. It occurs between molecules in which hydrogen is covalently bonded to fluorine (as in HF), oxygen (as in H2O), or nitrogen (as in NH3). For each H-F, H-O, or H-N bond, the single hydrogen electron is shared with the other atom. Thus, the hydrogen end of the bond is essentially a positively charged bare proton unscreened by any electrons. This highly positively charged end of the molecule is capable of a strong attractive force with the negative end of an adjacent molecule. In essence, this single proton forms a bridge between two negatively charged atoms.

The magnitude of the hydrogen bond is generally greater than that of the other types of secondary bonds and may be as high as 51 kJ/mol. Melting and boiling temperatures for hydrogen fluoride, ammonia, and water are abnormally high in light of their low molecular weights, as a consequence of hydrogen bonding

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2021.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2021.png)

## Larger molecules

When we have systems that are bigger than two atoms what we observe is the same splitting of energy levels, that will only affect the valence electrons. 

The combination would then create energy bands with allowed energy stated separated by energy gaps. 

the closer you are getting closer to valence electrons , yo interact sooner with the other electrons they interact (splitting) at larger distance.

frequency of the photon is proportional to the energy 13ev(H). core lecetrons tightyl bonds, energy well very deep, more energy to exite a core electron out. 

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2022.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2022.png)

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2023.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2023.png)

These gaps have an important effect on the material properties (whether the material is an insulator or a conductor). 

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2024.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2024.png)

### Fermi- Dirac Distribution

For a system of identical fermions in thermodynamic equilibrium, the average number of fermions (electrons) in a single-particle state *i* is given by a logistic function, or sigmoid function: the Fermi–Dirac (F–D) distribution, which is a special case of the complete Fermi–Dirac integral:

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2025.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2025.png)

where kB is Boltzmann's constant, T is the absolute temperature, εi is the energy of the single-particle state *i*, and μ is the total chemical potential.

At zero absolute temperature, *μ* is equal to the Fermi energy plus the potential energy per fermion, provided it is in a neighborhood of positive spectral density. In the case of a spectral gap, such as for electrons in a semiconductor, *μ*, the point of symmetry, is typically called the Fermi level or—for electrons—the electrochemical potential, and will be located in the middle of the gap.

The F–D distribution is only valid if the number of fermions in the system is large enough so that adding one more fermion to the system has negligible effect on *μ.*

Since the F–D distribution was derived using the Pauli exclusion principle, which allows at most one fermion to occupy each possible state, a result is that 0 < n*i* < 1.

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2026.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2026.png)

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2027.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2027.png)

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2028.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2028.png)

quantum dots - small enough we no logner asume continum behaviour absotion or release of photos. same conposition you can chaneg the color of the photon. bulk lots pf atoms. the valence of bulk stops growing eventually the reason is beccause the quantum mechanic system is not and specially the atoms do not form an enture QM system 

## Bonding & materials

![Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2029.png](/Bonding%20&%20Bonding%20Forces%20and%20Energy%20811412e7ac424a1cb4fcaf49f11e09b0/Untitled%2029.png)