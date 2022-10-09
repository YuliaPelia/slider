# slider
complex version slider
In order to create a slider, you need to specify several properties
1) constainer is the block that stores the slider
2) slide is a block containing img
3) nextArrow/prevArrow is a block containing a forward/backward arrow
4) totalCounter is a block that contains a number that shows the number of slides
5) currentCounter is a block that contains a number that corresponds to the displayed slider
6)wrapper is a wrapper of blocks with img slides
7) field is a block that hides the img

1. I create variables and assign them the appropriate selectors
width - necessary to know how many places the main block (wrapper) connects
2. I create an index that will recognize the current slide
3. I create a condition so that when we scroll through the slides, the numbers change according to the slider count
4. I create a function on which the slider will be built
5. I create an event handler to flip the slider
6. I create dots for navigating through pictures
