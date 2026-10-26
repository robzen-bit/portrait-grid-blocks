# Portrait Grid Blocks

Prototype for placing website blocks inside the Portrait (masonry) gallery grid. Supports ADO story 86637 (Gallery Builder).

- Use an orange plus between photos to add a block under that photo.
- Each new block asks whether to shuffle nearby photos for the best fit. The clicked photo stays fixed and its bottom edge is the line the block sits under; the other columns are refilled with the closest-matching photos so they end level.
- Switch Small/Large and Desktop/Laptop/Tablet/Phone in the top bar. Reset clears everything.

Everything is in `index.html` (no build step). All tuning numbers are in the `CONFIG` object at the top of the script. Saved state lives in the browser's localStorage.
