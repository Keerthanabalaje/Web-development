# CSS
     Cascading Style Sheets  
## Background colour
- In the header select the tag[h1,p,etc,.] and property with value [color]
***
## Font- Family
### Typography
1. Serif
2. san serif
3. Monospace
4. Hnadwriting / cursive
5. Display / Fantasy
### Variations
1. Weight - thickness
2. Style - italic, normal
3. Strech - to expand
### Selector
1. id - #
2. class- .
***
## Font size Property
1. Pixels
2. Percentges
3. EMs
4. REMs
## Font weight
1. Normal
2. Bold
3. Others
## Font style
1. Normal
2. Italic
3. Oblique
***
## Text 
### Text Transformation
1. Lowercase
2. Uppercase
3. Capitalize
### Text decorations
1. None
2. Underline 
3. Overline
4. Line Through
5. Blank
### Text indent
1. to leave gap before starting a words or paragraph [Starting position]
### Text shadow 
1. Left shadow
2. Right shadow
3. Top shadow
4. Bottom shadow
5. shadow blurring
6. Combine of everything [2px 2px 2px green]
***
## Gap
### Line height (Leading)
- line-height => Gap between lines
- Will not have any units
### Spacing(kerning)
1. Letter-spacing  => Gap between lines
2. Word-spacing  => Gap between lines
3. Expert kerning => Use to adjust gap btw letters using Letter-spacing
***
## Alignment
### Text align
1. Right
2. Center
3. Left
4. Justify [for paragraph - to look good]
### vertical align 
- Is to decide the positon of 'Inline elements'
1. Baseline
2. Sub
3. Super
4. Top
5. Text Top
6. Middle
7. Bottom
8. Text Bottom
***
## Pseudo 
### Pseudo Elements 
- by using selector and targeting the first letter or firstline with their properties
- double single quotes [ :: ]
### Pseudo classes
- types for links, buton, etc,.
    - Hover
    - active
    - visited
    - focus
***
## Width 
1. width
2. max-width 
3. min-width
## Height
1. Height
2. min-heigth
3. max-heigth (for images)
## Overflow 
1. overflow - auto
2. Overflow -x 
3. overfow - y
***
## Border
1. Width
2. Style
3. Colour
### Border radius

***
## Padding
- Shortcut => top right bottom left
***
## Margin
***
## Display
1. Inline => height change is not possible
2. Block
3. Inline-block => for using height
4. None => it will not display a particular li list
### Visibility 
5. It will leave the gap for the list, gives option to diplay the content in that list [by giving => visibility : 'hidden']
***
## Box
### Shadow
### Border radius
## Background
1. Background-image  : url('../');
2. if the size is small, the image will be repeated fully in this situation we can use => Background-image : no-repeat
3. To reapeat in horizontal = Background repeat: repeat -x
4. To repeat in vertical = repeat -y
### Position background
1. Background position - left top, left centre and left bottom followed this by right and centre 
2. By using the above, while scrooling the image will also scrolled with elements, to avoid this => background-attachment : fixed or scroll
### Background shorthand
1. Background : color path repeat position attachments.
2. We can use numericals for costum position top left (0px 0px) we can use (0px 100px) - to slightly move down can use percentage also
***
## List style
- For unordered list
  1. list-style-type: None
  2. " " " = disc
  3. circle 
  4. square
- For ordered list
  1. list-style-type : decimal-leading-zero(0.1,0.2,0.3)
  2. " " " : lower-alpha(a,b,c)
  3. Upper-alpha (A,B,C)
  4. Lower-roman (i,ii)
  5. Upper-roman (I,II)
### custom list
  1. list-style-image : url('') no-repeat position
### Position 
  - List-style-position: inside (it will make the bullet points to go inside) 
### shorthand list-style
lis-style: position type/image(url('../..'))
***
## Table styling
- width : %
- border : px(size) color
- padding :
- Text-color
- Text-transform
- text-align
### Border 
- Spacing => border-spacing : px 
- Collapse => border-collopse :collapse /separate(will give gap)
### Empty cell property
- empty-cell : hide/show
***
## Position
### Relative 
 - position: relative & left : px
 - z- index: 3
### Absolute
 - Position: Absolute
### Fixed 
 - position: fixed  (the selector element is fixed)
***
## Float Property
 - select image and give float: left
 - clear - left/right
 - class = clear
 - <br class ='clear'>
***
## Stylesheet
- External <link rel ="stylesheet" href = ".css(file)">
- Inline <style>
***
## Flex box
         https://www.youtube.com/watch?v=Z4yBSzpAkk0&t=351s
- Alternative value for
     1. Display:block; Inline; Inline; Inline-block;
- Flex direction 
     1. Flex / Flex- direction: row and row_reverse;
     2. Flex-direction: Colmn and colmn-reverse;
- Flex Wrap: 
     - Over flow flex elments can be wrapped, based on user.
     1. Flex-wrap: no wrap , 
     2. Flex-wrap: wrap,
     3. Flex-wrap: wrap- reverse
Flew- grow
     - flex-grow: 1
     - flex-shrink: 2
- Jstify content (main axis)
     1. justify-content: flex-start;
     2. justify-content: flex-end;
     3. justify-content: centre;
     4. justify-content: space-around;
     5. justify-content: space-between
- align content (cross axis)
     1. align-content: strech (default)
     2. align-content: flex-start
     3. align-content: flex-end
     4. align-content: centre
     5. align-content: space-around
- align self
     - diffrent properties can be used for any flex items at a time
     - .class {
       align-self:strech
     }   
- Item order
     - we can change the order using order
     - .class {
       order: 1
     }
-
***

# HINTS
1. display: flex - to allign something in centre
2. cursor: pointer - to arise hand while pointing





