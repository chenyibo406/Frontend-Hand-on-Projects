1. create a container div
2. inside the container div, create four elements with item classname
   of 'item', each one of them with classone as relative of one, two
   three, four, and with number of '1', '2', '3', '4'
3. set container, width, height, background-color, border-radius,margin with pixel. Could you figure it out why some of the properties of css need to set pixel and some of them need to set percentage, rem, vh and vw? there are one of the article show the
   different size unit of css properties setting:

https://www.geeksforgeeks.org/css-units-em-rem-px-vh-vw/;

https://elementor.com/help/whats-the-difference-between-px-em-rem-vw-and-vh/;

https://essential-addons.com/elementor/css-design-guide-difference/;

4. set container css, display: flex and see what happen, and write the explanation
   below the syntax; set flex-direction: row or column or column-reverse or row-reverse

5. add another 8 div element with classname 'item' and relative number as well as text content.

6. set item css attributes,  
   width: 150px;
   height: 80px;
   background-color: #15f831;
   border-radius: 8px;
   display: flex;
   justify-content: center;
   align-items: center;
   font-size: 2em;
   font-family: Arial, Helvetica, sans-serif;
   box-shadow: 1px 2px 5px black;

7. set container attributes  
    display: flex;
   flex-direction: column;
   flex-direction: row;
   flex-direction: column-reverse;
   flex-direction: row-reverse;
   flex-wrap: nowrap;
   flex-wrap: wrap;
   flex-flow: row wrap;
   justify-content: flex-start;
   justify-content: flex-end;
   justify-content: center;
   justify-content: space-between;
   justify-content: space-evenly;
   align-items: center;
   align-content: flex-start;
   align-content: flex-end;
   align-content: center;
   align-content: space-around;
   align-content: space-between;
   align-content: space-evenly;
   (if neccessary, add comment to each syntax)

8. order
   set one, two, three, four css order attribute to, 1,2,3,4 number
   and change the number to different and see what would happen.
   write comment down, when neccessary.

9. flex grow
   set one, two, three, four css "flex-grow" attribute and set the
   number to
   0,0,0,0;
   1,0,0,0;
   1,1,1,1;
   0,1,1,1;
   1,1,1,2;

10. flex shrink
    set one, two, three, four css "flex-shrink" attribute and set the
    number to
    0,0,0,0;
    1,0,0,0;
    1,1,1,1;
    0,1,1,1;
    1,1,1,2;

11. flex-basic
    add flex-basic: 200px to the .item class in CSS file and see what happen
    could you write down the reason with comment below?
    set max-width: 50px first and then write min-width: 500px to see
    what happen. Could you write down the explanation with comment?

why do we need flex-basic instead of max-width and min-width?
what is the benefit with flex-basic?

set flex-basic with 500px and .one, .two, .three, .four, flex-shrink:1

12. comment all the .one, .two, .three, .four in CSS
    comment flex-basis:500px
    use flex properties
    flex: [grow] [shrink] [basis] in items

13. align-self
    set .one{algn-self: flex-end}
