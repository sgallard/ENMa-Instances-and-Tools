# Input files used in "Entry Point Preserving Newspaper Magnification".

Each input is defined in 2 separate files:
- pX.json: Defines the articles, i.e the content of each article. 
    -  Starts with the name of the input, which is just to identify it but is not used in the code
    - font used for all the text
    - percentage of margin for displaying purposes.
    - Then, for each article, identified by the codename (in this examples, rectY), the heading font size and text, together with the body font size and text is defined. Also, the RGB code of the bounding box color.

- pX.txt: Defines the layout, i.e the coordinates and dimensions of each article:
    - Defines first the width and height of the page 
    - (the next 2 values are not used in this version of the algorithm)
    - for each article, identifies by the codename, the x and y coordinates of the **bottom left corner of each article**, together with width and height.


Additionally, images of the represented inputs are present in img/ folder. Finally, img_magn2/ contains the same but with an In-place-magnification of 2x
