---
layout: talk
title:  "Quantitative Structure-Property Relationship Modeling Using a Meshfree Approach"
speaker_name: "Hailong Chen" 
speaker_url: "megroup.engr.uky.edu/"
speaker_school: "University of Kentucky"
speaker_bio: "Dr. Hailong Chen is a tenure-track Assistant Professor at the University of Kentucky (UK) in the Mechanical
             Engineering Department. Since joining UK, Dr. Chen and his research group have been focusing on developing
             advanced nonlocal meshfree capabilities for multiscale multiphysics modeling and simulation of materials failure
             under extreme conditions. Prior to joining UK, Dr. Chen was a postdoctoral computational scientist at Idaho
             National Laboratory from Nov. 2015 to Aug. 2018, where he worked on developing MOOSE-based and BISON-
             coupled computational capabilities to meet DOE-NE’s strategic needs. Dr. Chen obtained his Ph.D. from Arizona
             State University in 2015 under Dr. Yongming Liu, with a research focus on developing computational models for
             materials failure modeling. Dr. Chen is a member of several research communities, such as Engineering Institute of
             Mechanics (EMI) and U.S. Association for Computational Mechanics (USACM)."
talk_date: "10:00 AM MST, Oct. 30, 2020"
date: 10-08-2020
image: _images/people/Hailong.jpg
abstract: "At the core of continuum-based constitutive modeling is the concept of homogenization. Continuum constitutive
           models have proven to be well-suited to predict deformation response, yet the ability to predict damage and life
           remains problematic, particular at extreme conditions such as high temperature. This is understandable since
           failure mechanisms are influenced to a greater extend by underlying, lower length scale features which are ignored
           or homogenized out at macroscale. Nonetheless, microstructure-based homogenization is still useful for material
           properties that are less sensitive to the underlying microstructure such as elastic modulus, but predictive
           microstructure-based modeling is needed for microstructure-sensitive material properties such as failure
           strength.Microstructure-level material mechanical behavior has been predominantly modeled using finite element
           method (FEM) and its variants. Due to the requirement of mesh generation, difficulties arise in these methods for
           complex microstructures when automatic quality mesh generation is impossible. More importantly, for
           simulation involving cracks and discontinuities, classical continuum mechanics-based approaches have the issue
           of stress singularity at the crack tip or interfaces. Effective modeling and simulation of crack nucleation and
           propagation using FEM-based approaches are problematic.To overcome these challenges, a nonlocal method
           called lattice particle model (LPM) was recently developed and has been successfully applied to both composites
           and metal alloys. Different from the classical continuum mechanics theory, LPM reformulates the equations of
           motion using integral (spatial) differential (temporal) equations rather than partial differential equations. For
           composite materials, LPM discretizes the material microstructure into pixels (2D) or voxels (3D). A pixel/voxel
           interacts with neighboring pixels/voxels up to the second nearest neighbors via bond-like force. As a result, LPM
           does not depend on mesh generation that is usually considered as the most difficult part in mesh-based approaches
           for complex microstructures. For polycrystalline materials, LPM discretizes individual grain into material
           particles which are packed according to the underlying lattice structure. Lattice rotation rather than coordinate
           transformation is used to represent the crystallographic orientation of a grain. Grain boundaries are automatically
           generated at the crossing where differently oriented grains intersect. Thanks to these distinct features, LPM does
           not have the issue of stress singularity when spatial discontinuities exist in the domain of interest. In addition,
           LPM models crack initiation and growth using simple yet effective bond failure rule between otherwise interacting
           material particles.In this talk, quantitative structure-property relationship modeling using LPM will be presented.
           Applications of LPM to composites and metal alloys will be discussed."
categories: talk-current
---

