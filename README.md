# grid
Grid ref with grid projects

### Grid reference

display : grid | inline-grid

grid-column-gap
grid-row-gap
grid-gap

grid-column-start
grid-column-end
grid-row-start
grid-row-end

grid-template-columns
grid-template-rows

##### align grid items horizontally
justify-content: space-around|space-evenly|space-between|center|start|end

##### align items vertically
align-content: space-around|space-evenly|space-between|center|start|end


#### chid items
grid-column
grid-row



grid-area : grid-row-start grid-column-start grid-row-end grid-column-end
grid-template-areas

##### If four <grid-line> values are specified, grid-row-start is set to the first value, grid-column-start is set to the second value, grid-row-end is set to the third value, and grid-column-end is set to the fourth value.

##### When grid-column-end is omitted, if grid-column-start is a <custom-ident>, grid-column-end is set to that <custom-ident>; otherwise, it is set to auto.

##### When grid-row-end is omitted, if grid-row-start is a <custom-ident>, grid-row-end is set to that <custom-ident>; otherwise, it is set to auto.

##### When grid-column-start is omitted, if grid-row-start is a <custom-ident>, all four longhands are set to that value. Otherwise, it is set to auto.

##### The grid-area property can also be set to a <custom-ident> which acts as a name for the area, which can then be placed using grid-template-areas.

