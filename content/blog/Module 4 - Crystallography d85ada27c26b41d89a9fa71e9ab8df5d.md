---
title: "Module 4"
date: 2010-10-06T00:19:29-04:00
slug: "module4"
description: "A brief guide to setup KaTeX"
keywords: []
draft: false
tags: ["MSE"]
math: true
toc: false
---

# Module 4 - Crystallography

# Lecture 1 - Foundations of Crystallography, Symmetric Operations

**Basic Definitions**

What would be the difference between the unite cell and the basis/ motif?

**Symmetry operations**

- **Symmetry** - formal mathematical description of order.
- **Crystallography** - includes ideas of symmetry and the notations used solid-state physics and material sciences.
- **Diffraction** - experimental approach of crystallography.
- **Crystal structures** - Defining features: long-range order and periodicity.
- **Amorphous materials -** short-range orders (different regions will have different charges and this will influence each other), you can tell what is going to happen a couple of nanometers away from that area.
- **Unit Cell** - the pattern that is repeated over time in the crystal structure.
    - The unit cell of a crystal is defined by the lattice points. The unit cell is the smallest part of a crystal that repeated regularly through translation in three dimensions creates the whole crystal.
- **Space Lattice** - set of points that relate to the propagation of a unit cell. A mathematical construct, the peg. It is assumed it is infinite.
    - A lattice is an ordered array of points describing the arrangement of particles that form a crystal.

        The yellow dots will be the unit cells, while the points were this unit cells are locates would be the lattice point

        ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled.png)

- **Basis or Motif -**  The physical thing that is hanging at each point, the hat I hang from the peg.
- **Lattice point** - the same physical structure (that is every other figure, so everyone is associated with one figure point up + one figure pointing down).

## Symmetry Operations

- **Translation** - vector, symmetry operation. (!) Since the system is infinite, if the entire chain were shifted by this amount, you wouldn’t be able to tell that anything had happened
    - The location of the lattice point can be randomly assigned (that is, it could be in the center of the "down" figure, but the translation operation is a fundamental feature of the pattern. Again, the separation of the lattice point is going to be the same no matter where we put the lattice points.
    - Does not change the sense of the coordinated.

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%201.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%201.png)

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%202.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%202.png)

- **Reflection** - 1D. Mirror image. Example (a) we can't because of the chirality of the system. They are asymmetric, they have handiness.

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%203.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%203.png)

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%204.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%204.png)

- **Rotation** - In 2D, rotation must be defined about a specific point (and in 3D, it must be defined about a specific axis).

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%205.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%205.png)

    For example, We could rotate the entire system by 𝜋 radians (180°) about any of these points. (C2 every 180, C4 every 90).

    - Rotation can change the sense of two coordinated in 2D and

**SUMMARY:**  We defined some important terms such as symmetry, crystallography, diffraction, crystal structure vs. amorphous materials, the difference between the lattice cell and cell unit. And symmetry operations: translation (1D), reflection (1D) and rotation (2D)

# Lecture 2 - Bravais lattices

**N-fold rotations in 2D**

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%206.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%206.png)

**Unit Cell**

**Bravais Lattice**

### What types of lattices are possible given the known symmetry operations?

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%207.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%207.png)

*m in an integer and cos α can only generate values between -1 and 1 so.* 

- "Fold" refers to the number of times I have to rotate the lattice to come back to the starting point, i.e., 3-fold triangular symmetry. 1-fold identity axes. You cannot have a 5-fold symmetry in a 2D lattice, it cannot do space-fillings you are going to have gaps.

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%208.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%208.png)

## Unit Cell and Primitive Unit Cells

- Unit cell - repetitive unit in an infinite lattice. I translate integer multiples throughout the lattice.
- **Primitive unit cell** - associated with one lattice point.

    A, B, E and F are primitive. B, D not primitive (4 corners, each 1/4 and each other point contribute to another unit cell). F is called **Wigner-Seitz** Bisecting lines with the neighbors, where they intercept the smallest area enclosed in the shaded region.

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%209.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%209.png)

    2- fold rotation needs to be defined by two vectors that provide information about the other rows (T₁ and T₂)

    ## Construction of Bravais Lattices in 2D

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2010.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2010.png)

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2011.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2011.png)

    ## Bravais Lattice in 3D and Crystal Groups

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2012.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2012.png)

**SUMMARY:** 

# Lecture 3 & 4 - Crystallographic Notation

**Additional 3D Symmetry Operations**

**Point Group Notation**

**Stereographic projection**

**Space Group**

**Point Coordinates**

**Crystallographic Direction**

**Crystallographic Planes**

## Additional Symmetry Operations in 3D

- **Inversion** - if you take any point and you invert the sign of each coordinate

    ![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2013.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2013.png)

    - **Rotary inversion, Rotary Reflection** (n overline) - Rotation + inversion
- **Glide -** Reflection + Translation. In a crystal with a lattice parameter, *i* is *a/2.* 2D is associated with a line, 3D a plane.
- **Screw -** Rotation + Translation. In a crystal with lattice parameter *a*, the screw operation nₘ is an n-fold rotation followed by a translation of a(m/n); i.e., 6₃ is a rotation of 2π/6 and a translation of (3/6)a or a/2.

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/folds.jpg](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/folds.jpg)

## Point Group Notation

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2014.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2014.png)

### Example - Group 4mm

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2015.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2015.png)

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2016.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2016.png)

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2017.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2017.png)

## Stereographic Projection

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2018.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2018.png)

## Space Group Notation

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2019.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2019.png)

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2020.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2020.png)

There are in total 230 space groups (see International Tables for Crystallography)

## Point Coordinates

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2021.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2021.png)

## Crystallographic Directions

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2022.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2022.png)

## Crystallographic Planes

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2023.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2023.png)

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2024.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2024.png)

![Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2025.png](/Module%204%20-%20Crystallography%20d85ada27c26b41d89a9fa71e9ab8df5d/Untitled%2025.png)

**SUMMARY:**