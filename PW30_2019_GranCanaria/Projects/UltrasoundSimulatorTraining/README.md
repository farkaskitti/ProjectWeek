Back to [Projects List](../../README.md#ProjectsList)

# New features for an ultrasound training system

## Key Investigators

- José-Carlos Ruiz-Luque (ULPGC - GTMA - MACbioIDi)
- Guillermo Valentín Socorro-Marrero (ULPGC - GTMA - MACbioIDi)
- Samba Diaw (Université Cheikh Anta DIOP)
- Oumar Kane (Centre Hospitalier National Fann Dakar)
- Joseane Ferreira (Hospital Agostinho Neto de Praia)
- Juan Ruiz-Alzola (ULPGC - GTMA - MACbioIDi)

## Participating

- [Csaba Pinter](http://perk.cs.queensu.ca/users/pinter) (Queen's University, Canada)

# Project Description

This project is a next step in the one presented during 28th PW NA-MIC and it aims to add new features both the graphic user interface (GUI) and the functionalities of the training system.

## Objectives

1. Supporting the multi-language (Spanish, French, English, Portuguese, and Arabic). 
2. Registering several custom layouts. 
3. Calculating the angle between a plane of the US image and a needle and it will be shown in a 3D scene or a 2D viewer.
4. Visualizing the image orientation marker symbol in an US image.
5. Selection of various clinical procedures for training. 


## Approach and Plan

1. A multi-language proposal was implemented in a Guidelet-based GUI for Slicer 4.8 using to the module “gettext” in Python. We would like to implement this proposal in SlicerIGT for Slicer 4.10.
2. The design of new custom layouts in Guidelet-based GUIs was implemented in collaboration with the Perklab team.
3. Designing a proposal for the angle between a plane of the US image and a needle. At first, we will study the VTK if there is a filter for this objective or other 3D Slicer modules.
4. Studying the MicrUs SDK to visualize the image orientation marker symbol and it will be implemented in the Plus Toolkit or 3D Slicer. 

## Progress and Next Steps


# Illustrations

Guidelet muli-language interface:

<img src="MultilanguageGUI.png"  >

Figure1. Language selection for the Guidelet-based GUI 

<img src="MultilanguageArabic.png"  >

Figure 2. Guidelet-based GUI in Arabic 

<img src="MultilanguageSpanish.png" >

Figure 3. Guidelet-based GUI in Spanish

Sketches:

<img src="SketchAngle.png" width="150" height="110" >

Figure 4.  An angle between a plane of the US image and a needle

<img src="ImageOrientationMarkerSymbol.png" width="150" height="190" >

Figure 5. An image orientation marker symbol (in blue color)


# Background and References

-	[Slicelet documentation](https://www.slicer.org/wiki/Documentation/Nightly/Developers/Slicelets)
-	[Guidelet documentation](http://www.slicerigt.org/wp/developer-tutorial/)
-	[Multi-language GUI](https://github.com/mt4sd/UltrasoundTrainingSystem/tree/i18n_l10n)
-	[Guidelet-based GUI](https://github.com/mt4sd/UltrasoundTrainingSystem/tree/master)
