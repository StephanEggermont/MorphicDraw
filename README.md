# MorphicDraw
MorphicDraw is a drawing application demonstrating some of the power of Morphic.
Morphic is a powerful graphics environment, used in Self, Squeak, Cuis and Pharo.
In an iterative and incremental process, build up an application that supports
drawing connected figures. 

This application is build embedded in the three commonly available higher level 
ui frameworks in Pharo, Polymorph, Glamour and Spec.

![Screenshot of MorphicDraw](https://github.com/StephanEggermont/MorphicDraw/blob/master/SimpleMorphicDrawWindow.png)

## Contents:
- A Morphic Application with a Window
  - Using Polymorph
  - Using Glamour
  - Using Spec
- Shapes and PasteUpMorph
- Icons
- Colors
- Selection and resizing
  - Corner handles
- Context menu
- Connecting
- Z-order
- Selections (work in progress)
- Loading the code

## Loading the code
MorphicDraw was created in Pharo (version 4). To load the code:
Open the Monticello Browser. Add a new repository of type smalltalkhub.com. 
The owner is StephanEggermont, the project is MorphicDraw. User and password are only needed
when you want to commit changes to the repository. Open the repository and load the latest version of
MorphicDraw. You may do this by loading the latest version of ConfigurationOfMorphicDraw with Monticello. Then open a Playground and DoIt: ConfigurationOfMorphicDraw load.

The application can be started by opening a Playground and DoIt: MorphicDraw open.

The .tex file was compiled with xeLaTeX
