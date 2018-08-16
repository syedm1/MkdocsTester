# Visualiser with unity
The Visualiser component of project Planning visualisation deals with rendering visual objects and thier animation for solutions generated for the given problem in selected domain using a custom constraint solver.

The Visulaiser component UI is created using unity to make sure the application performance is at its best. UI and rendering of solution into visual file components is developed in same environment together to keep the flows consistent.
## Overall file structure
This is overall file structure of the Visualiser
```bash


+---Visualiser
|   +---Animations
|   +---Fonts
|   +---Images
|   +---Resources
|   +---Scenes
|   +---Scripts
|   |   +---FileUpload
|   |   \---Visualisation
|   |       +---AnimationControl
|   |       +---TransferPack
|   |       |   \---TransferItemPack
|   |       \---VisualisationModels
|   \---Sprites
\---WebGLTemplates
    \---NewTemplate

```
## Architecture
Glance at file structure represents that all the components are seperated and modular. As the visualiser is rendering the files from different UI elements and generating objects automaatically there will always be dependencies involved in it. Before adding new visual components or adding new functionalities understanding of dependencies is required.
