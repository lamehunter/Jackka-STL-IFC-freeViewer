# Jackka STL & IFC freeViewer

A free, browser-based viewer for **IFC** (BIM) and **STL** models with section-cut ("scissor") tools.

**Open it:** https://lamehunter.github.io/Jackka-STL-IFC-freeViewer/

Works in Edge, Chrome and Firefox on Windows. No install. Files you open stay on your computer and are never uploaded.

## Features
- Open `.ifc` and `.stl` files (button or drag-and-drop, several at once)
- **Scissors:** click any surface to cut through the model parallel to it
- Section planes on X / Y / Z with sliders, flip and on/off; drag the red frame to move a cut
- Section box with draggable knobs, fit to the selected element
- Floor-plan cut per storey
- Cut faces drawn hatched, solid or hollow
- Show/hide by IFC class and storey; hide, isolate and zoom to elements
- IFC properties and quantities for the selected element
- Edge outlines and standard views

## Limits
- Window and door openings are not cut out of walls
- Curved (NURBS) surfaces are approximated with straight edges
- Needs internet access to load the 3D library and fonts
