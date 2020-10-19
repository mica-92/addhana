---
title: "QM"
date: 2020-09-29T00:19:29-04:00
slug: "QM"
description: "Short post"
keywords: ["lists"]
draft: false
tags: ["graduate", "studynotes", "MSE"]
math: false
toc: true
---

A week in MSE 570
<i>This page is a trial for exporting notes between Notion and OneNote. I'm still figuring out which one will work best for me.</i> 

# Introduction to QM

- Class: MSE 570
- Reviewed: No
- Type: Study Notes
- Week: 37- 2020

## A little bit of history

- The main inconvenience with the classical view of the atom, the Rutherford model, was that it was known already that a particle accelerating in an EM field would eradiate its energy. In these models the atom is unstable meaning that eventually the electrons would collide and merge with the nucleus.
- Discoveries in atomic spectra showed that each element emits light of specific energies when excited by an electric discharge or heat.
- In 1885, Balmer showed that the energies of visible light emitted by the hydrogen atom are given by the equation

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled.png)

and the energy of the light emitted is related to the wavelength, frequency, and wavenumber of the light, as given by the equation

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%201.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%201.png)

The origin of this energy was unknown until Niels Bohr’s quantum theory of the atom, first published in 1913 and refined over the following decade. This theory assumed that negatively charged electrons in atoms move in stable circular orbits around the positively charged nucleus with no absorption or emission of energy. However, electrons may absorb light of certain specific energies.

- The origin of this energy was unknown until **Niels Bohr’s quantum theory of the atom**, first published in 1913. This theory assumed that negatively charged electrons in atoms move in stable circular orbits around the positively charged nucleus with no absorption or emission of energy. However, electrons may absorb light of certain specific energies and be excited to orbits of higher energy; they may also emit light of specific energies and fall to orbits of lower energy. The energy of the light emitted or absorbed can be found, according to the Bohr model of the hydrogen atom, from the equation

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%202.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%202.png)

- As the electrons drop from level nh to nl, energy is released in the form of **electromagnetic radiation**.
- When applied to the hydrogen atom, Bohr’s theory worked well; however, the theory failed when atoms with two or more electrons were considered.

## Quantum Mechanics

- The **de Broglie equation**, proposed in the 1920s, accounted for the electron’s wave nature. According to de Broglie, all moving particles have wave properties described by the equation

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%203.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%203.png)

- **Particles massive enough to be visible have very short wavelengths, too small to be measured. Electrons, on the other hand, have observable wave properties because of their very small mass**
- **Heisenberg’s uncertainty principle,** states that there is a relationship between the inherent uncertainties in the location and momentum of an electron. Now, instead of being able to describe **precise orbits of electrons, as in the Bohr theory**, we can only describe **orbitals, regions that describe the probable location of electrons**. **The probability of finding the electron at a particular point in space, also called the electron density**, can be calculated—at least in principle. The x component of this uncertainty is described as:

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%204.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%204.png)

The **Schrödinger equation** describes the wave properties of an electron in terms of its position, mass, total energy, and potential energy. Because n varies from 1 to ∞, and every atomic orbital is described by a unique φ, there is no limit to the number of solutions of the Schrödinger equation for an atom. Each φ describes the wave properties of a given electron in a particular orbital. The probability of finding an electron at a given point in space is proportional to φ². A number of conditions are required for a physically realistic solution for φ:

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%205.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%205.png)

## Quantum Mechanics - Axioms

### Axiom 1

- The wave function is a probability wave of finding the electron at a time in a box volume at point d³r at point r

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%206.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%206.png)

- Assuming that the wave function is properly **normalized**. So, if you add up the probability of the particle appearing at every possible location, the sum should be exactly 1. This means that if I integrate the wave function on all space I'll get a value of 1.

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%207.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%207.png)

- So if the value of φ² is low, the probability of finding the electron at that location is low. And these probability waves interfere with one another, in the same way classical waves do.

### Axiom 2

- Just as Newton’s laws (F = ma) govern particle motion in classical mechanics, an equation called the **Schrödinger equation governs the evolution of the wave**, and hence the spatial changes to probabilities as a function of time:

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%208.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%208.png)

- **Correspondence Principle** - For large systems, or high n, or high mass, the behavior predicted by the Schrödinger equation should map to that predicted by Newton

### Axiom 3

- We have a probability wave function Ѱ and a fundamental equation describing how Ѱ evolves---but how do these relate to physical, measurable properties? Every property (“observable”) we’d be interested in measuring, such as the particle’s position or speed, has its own “operator” that we apply to the wave function to obtain the desired information. S**ince the wave function relates to probability, the operator produces an “expectation value” that is a statistical quantity---i.e., the average**.

## The Infinite Well

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%209.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%209.png)

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2010.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2010.png)

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2011.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2011.png)

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2012.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2012.png)

## The Hydrogen Atom and the Schrödinger Equation

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2013.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2013.png)

- **The solutions of each of these ordinary differential equation is what gives rise to the difference quantum numbers and therefore force the quantization.**
- We are using the Schrödinger Equation that does not have time as a variable.

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2014.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2014.png)

- **Probability distribution.** As we increase the principal QN (n) we find **nodes**, places where we have a zero probability of finding the electron, and **peaks,** multiple preferred distance away from the nucleus. Solutions to the equation are called **Eigenvalues.**

![Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2015.png](/Introduction%20to%20QM%20e31ae4a337b3480ca6ac8a5208e36829/Untitled%2015.png)

The shapes of the orbitals come from the values of these **eigenvalues.**

## Degeneracy

In QM for the Hydrogen atom, there are multiple solutions with the same energy level. This particularity is called **degeneracy**.

- The degenerate state with energy En = 2n²

In atoms with more than one electron the degeneracy id broken due to the
interactions between the electrons. This means that electrons start interacting with each other, creating repulsion, and this breaks the "same energy" state that occur in the H atom

**Also, for H there is a perfect balancing between the Coulomb and the Centrifugal barrier that cancel out and the Eigenvalues do not depend on the quantum number *l*. But for more electrons, because the Coulomb is acting on its entirety because of the screening, these two forces are no longer cancel out.**

## Pauli exclusion principle

Stipulates that each electron state can hold no more than two electrons that must have opposite spins. Thus, s, p, d, and f subshells may each accommodate,??