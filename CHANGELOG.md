## 0.0.11

- Avoid unnecessary node rebuilds

## 0.0.10

- Added DragHandlers for edges to resize a node in only one dimension @schaetz
- Added "resizeMode" attribute to Nodes to configure the amount of drag handlers @schaetz
- Made movement and resizing of nodes smoother by replacing GestureDetector by Listener widget @schaetz
- Implemented snapping to grid on resize @schaetz
- Implemented snapping to grid on movement within the Node class without the need for a formatter, also snapping at the right or bottom edges (depending on proximity) @schaetz
- Added "snapMovementToGrid" and "snapResizeToGrid" attributes to Controller to make snapping configurable individually for both actions @schaetz
- Added "Settings" menu item with "Snap To Grid" option @schaetz

## 0.0.9

- Adding [value] to [InfiniteCanvasNode] with generic type

## 0.0.8

- Adding optional grid snapping (Thanks @InstrinsicAutomations 🎉)

## 0.0.7

- Adding ability to merge menus
- Adding [DirectedGraph] builder

## 0.0.6

- Removing meta key for delete
- Adding [drawVisibleOnly] to allow for drawing only visible nodes and edges
- Adding [canAddEdges] for when holding control you can link nodes

## 0.0.5

- Adding clip option for node

## 0.0.4

- Adding menu options
- Adding resize controls

## 0.0.3

- Adding click to drag when space is pressed
- Adding background builder

## 0.0.2

* Fixing widget rebuilds
* Adding draggable example

## 0.0.1

* Adding example and library
* Adding demo
