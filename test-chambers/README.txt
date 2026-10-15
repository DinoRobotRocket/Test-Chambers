Test Chambers - portal gun puzzle

Open index.html in Chrome. It loads chambers/chamber01.js, chamber02.js, ... one at a time as you reach them.

To add a chamber: create chambers/chamber13.js (copy any existing file), then change CHAMBERS=12 to 13 near the top of index.html.
ops are [char,x0,y0,x1,y1] on a 30x17 grid: # solid, W portal-able white wall, ~ acid, S start, E exit.
mirror([...]) flips a layout left-to-right.

Button puzzles: chamber files may also have cubes:[[x,y]], buttons:[[x,y,id]], doors:[[x0,y0,x1,y1,id]]. A door opens while every button with its id is pressed. Update CHAMBERS in index.html when you add files.
