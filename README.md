# Floor Plan Designer (2D + 3D)

Plan your home layout on screen: draw the plot, add rooms, walls, doors and windows, and see exact sizes in feet and inches. Then switch to **3D View** to look around your plan, walk through it room by room, and share it. No installation needed.

## Getting started

1. Pick or create a project from the dropdown at the top left.
2. Set your plot size: click the plot, then double-click it and type the width and height (for example `30' 0"` or `30`).
3. Add rooms, walls, doors and windows from the left sidebar.
4. Everything saves automatically in your browser.
5. When you are ready, click **3D View** at the top to see your plan in 3D.

**Typing sizes:** `10' 6"`, `10 6` and `10.5` all work. A plain number means feet.

## Main features

- **Rooms:** draw a room by dragging on the plot. Move it, resize it from its edges or corners, and choose its type (Bedroom, Kitchen, etc.) from the side panel.
- **Walls:** draw straight walls. Default thickness is 9 inches. Walls snap neatly to edges and corners.
- **Doors and windows:** click on a wall to place them. Click a door's curved line to change which way it opens.
- **Furniture and extras:** bed, sofa, toilet, sink, car, two-wheeler, fridge, chair, table, dressing table, almari, column, stairs, electrical point, text note, north arrow, and a Custom shape of any size.
- **Exact sizes everywhere:** double-click any item to see and edit all its details, including area and usable area.
- **Warnings:** red items show overlaps or anything sticking outside the plot. Click a warning to jump to it.
- **Tape measure:** drag between two points to check any distance.
- **Guide lines:** add vertical or horizontal guides and snap things to them.
- **Arrange tools:** Shift-click several items, then align or space them evenly. Mirror the whole plan left-right or top-bottom.
- **Calculator:** a feet-and-inches calculator on the right (add, subtract, multiply, divide, rounding to 1/16 inch and more).
- **Change all colours:** recolour every wall, door, window or room at once.
- **3D View:** see your plan as a 3D house, walk through it, and export it (see the 3D section below).

## Controlling what you see

- **Layers:** show or hide rooms, walls, doors, windows, furniture, text and guides.
- **Dimensions / Sq ft text / Grid:** switch on or off, or use "Hide all dimensions".
- **Text size:** make labels and dimension text bigger or smaller with the + and - buttons.
- Hidden layers are also hidden in your exports (PDF, image, SVG).

## Preview mode

Click **Preview** for a clean, full-screen view of your 2D plan with no panels. Hover over any room or wall to highlight it. Press **Esc** or "Exit preview" to go back to editing.

---

## 3D View

Click **3D View** (next to Preview) to see your plan as a 3D house. Your 2D plan is not changed. To change the layout, close the 3D view, edit in 2D, and open 3D again.

Your walls, doors, windows, rooms and furniture all appear in 3D. Doors and windows are cut into the walls, and windows have glass.

### Looking around

- **Rotate:** drag with your mouse or finger.
- **Zoom:** scroll, pinch, or use the **🔍＋** and **🔍－** buttons (the + and - keys also work).
- **Move the view:** right-click and drag, or drag with two fingers.
- **Quick views:** use the view list at the top to jump to Isometric, Top, or any of the four sides.
- **Ceiling:** show or hide the ceiling. It is only visible from inside the house.
- **Cutaway walls:** shows low walls so you can see into every room from above.
- **Labels:** show or hide the room names.
- Press **Esc** or click **Close** to go back to the 2D plan.

### Walk through your plan

Click **🚶 Walk** to stand inside your plan and look around as if you were there.

- **Move:** use **W A S D** or the arrow keys. On a phone, use the arrow buttons at the bottom left.
- **Look around:** drag with your mouse or finger.
- **Map:** a small plan appears in the top right corner. The red arrow shows where you are and which way you are facing. Tap or click anywhere on the map to jump there.
- **Go to a room:** choose a room from the **Go to room…** list, or double-click (double-tap on a phone) any room. You will start just inside the door, looking into the room.
- **Zoom:** the **🔍＋** and **🔍－** buttons make the view closer or wider.
- Press **Esc** to leave walking and return to the outside view.

### Change how you stand

While walking, a panel with a little person appears in the bottom right corner. Pick how you want to see the rooms:

| Pose | What it is like |
|---|---|
| **Stand** | Normal adult eye height |
| **Sit** | Seated on a chair or sofa |
| **Crouch** | Low, as if looking at something near the floor |
| **Lie down** | Floor level, looking up at the ceiling |
| **Raised** | Higher up, as if standing on a stool or ladder |
| **Child** | A small child's eye level |

You can also fine-tune:

- **Eye height:** drag the slider to any height you like (the **R** and **F** keys raise and lower it).
- **Look up/down:** tilt the view up or down.

Your choice stays the same as you move between rooms, so you can compare rooms from the same position.

### Setting heights (windows, appliances and more)

Click any wall, door, window or piece of furniture in the 3D view. A panel opens where you can set:

- **Bottom:** how high above the floor it starts. For example, a window that starts 4 feet up, or a wall cupboard that hangs high.
- **Height:** how tall it is.
- **Top:** where it ends. Top is simply Bottom plus Height, and the three numbers stay in step with each other.
- **Window type:** choose **Normal**, **Roshandan** (small ventilator high on the wall) or **Floor-to-ceiling**, and the numbers are filled in for you. You can still change them afterwards.
- **Wall height:** set the height of all walls at once in the Heights box.

Click **Reset to default** to go back to the standard height for that item. If you never set anything, sensible standard heights are used (for example, doors 7 ft, windows 4 ft with a 3 ft sill, walls 10 ft).

Heights are only used in the 3D view. They are stored in your browser along with your project, but they are not part of the 2D plan or the JSON backup file.

### Save and share your 3D view

| Button | What you get |
|---|---|
| **📷 PNG** | A picture of what you are looking at now |
| **💾 Export 3D** | One file you can send to anyone. It opens in any web browser, on a phone or computer, and has everything: looking around, walking, poses, map, room jumping and heights. It does not include your editing tools. |
| **🧊 GLB** | A 3D model file for other programs such as Blender, 3D viewers, and augmented-reality apps on many phones. It contains the house shape and colours, but not walking, poses, the map or height editing. |

Good to know:

- **Export 3D** is a snapshot of your plan at the moment you export. If you change your plan later, export again.
- Changes made to heights inside an exported file are not saved when it is closed.
- If you do not want the ceiling in your GLB model, switch off **Ceiling** before exporting.

### On a phone

The 3D view works on phones and tablets. The top bar can be swiped sideways to reach all the buttons, and the height panel appears at the bottom of the screen. Turn your phone sideways for a wider view.

### Things to know about the 3D view

- Furniture is shown as simple shapes, not photo-realistic models.
- Doors are always shown closed.
- Text notes and the north arrow are not shown in 3D.
- If the 3D view does not open, check your internet connection and reload the page.

---

## Projects

- Create as many projects as you like from the dropdown ("Create new project").
- Rename a project using the name box next to the dropdown.
- **Delete project** removes the current project (click twice to confirm).
- **Clear all** empties the current plan. Undo brings it back.
- Projects are stored in your browser only. Use the JSON button to keep a backup file.

## Saving and exporting (2D plan)

| Button | What you get |
|---|---|
| **JSON** | Full project file (everything, including hidden items) |
| **CSV** | A table of all rooms and elements with sizes and areas |
| **SVG / PNG** | Picture of your plan |
| **Export PDF** | PDF with title block and scale bar (choose A4 or A3) |
| **Print / PDF** | Print-ready page |
| **Room images (PNG)** | One picture per room |
| **Open / Import** | Load a saved JSON project |

For saving and sharing the 3D view, see the 3D View section above.

## Handy shortcuts

| Key | Action |
|---|---|
| V / R / W / D / O / M | Select / Room / Wall / Door / Window / Tape measure |
| Ctrl+Z / Ctrl+Y | Undo / Redo |
| Ctrl+C / Ctrl+V | Copy / Paste (works between projects) |
| Ctrl+D | Duplicate |
| Delete | Remove selected item |
| Arrow keys | Nudge selected item |
| Shift-click | Select several items |

**In the 3D view:**

| Key | Action |
|---|---|
| W A S D or arrow keys | Walk (when walking) |
| R / F | Raise / lower your eye height (when walking) |
| + / - | Zoom in / out |
| Esc | Stop walking, or close the 3D view |

## Tips

- Zoom with the + and - buttons at the top. Drag empty space or scroll to move around.
- Keep Snap switched on to line things up with walls and edges automatically.
- Use the Tools and Panel buttons at the top to hide the sidebars for more room.
- Draw your walls, doors and windows carefully in 2D first. The 3D view is built from them, so a tidy plan gives a tidy 3D house.
- Set window and appliance heights in the 3D view if the standard heights do not match your design.
