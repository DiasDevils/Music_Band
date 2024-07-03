# Music Band learning project.
This is a project for learning HTML and CSS.
This is a 'pretend' website for a starting out music band.


# Cheat sheet to troubleshoot bug
PADDING
1.padding: 10px; ONE value sets padding on all four sides.
2.padding: 10px 5px; TWO values, 1st top&bottom, 2nd left&right.
3.padding: 10px 5px 3px; THREE values 1st the top, 2nd left&right, 3rd top&bottom.
4.padding: 10px 5px 3px 1px;= FOUR values, 1st top, 2nd right, 3rd bottom, 4th left.

MARGIN
1.margin: 10px;= ONE value sets margin on all four sides.
2.margin: 10px 5px;=  TWO values, 1st top&bottom, 2nd left&right.
3.margin: 10px 5px 3px;=THREE values, 1st top, 2nd left&right, 3rd for bottom.
4.margin: 10px 5px 3px 1px;= FOUR values, 1st the top, 2nd right, 3rd bottom, 4th left.

POSITION
1.position: static; Default flow, ignores top, right, bottom, left.

2.position: relative; Relative to normal position in the doc flow.Can be offset using top, right, bottom, left.
/* Example */
position: relative;
top: 10px; /*moves 10px down from its normal position*/

3.position: absolute; Relative to initial containing block/ancestor. Can be positioned using top,right,bottom,left.
/* Example */
position: absolute;
top: 20px; /* 20px from the top of the nearest positioned ancestor */
left: 50px; /* 50px from the left of the nearest positioned ancestor */

4.position: fixed; Relative to the viewport (browser window), staying in the same place even when scrolling. Use top, right, bottom, left to position.
/* Example */
position: fixed;
bottom: 10px; /* Always 10px above the bottom of the viewport */
right: 15px; /* Always 15px from the right of the viewport */

5.position: sticky; Switches between relative and fixed positioning based on the user's scroll position.
Sticks in place when scrolling past a defined threshold (using top, right, bottom, left).
Must be within a scrolling parent element to work effectively.
/* Example */
position: sticky;
top: 0; /* Sticks to the top of its parent container when scrolling down */


BOX-SHADOW
box-shadow: 0 1px 2px white;
0 = Horizontal Offset. No shift left or right; shadow aligns directly under the element horizontally.
1px = Vertical Offset. Shadow is shifted 1 pixel down.
2px Blur Radius. Shadow is slightly blurred by 2 pixel.
Color (white): The shadow color is white.


# References

Favicons from https://favicon.io/emoji-favicons/guitar
              https://favicon.io/emoji-favicons/musical-note

Code from https://github.com/Code-Institute-Solutions/love-running-v3

Code from https://github.com/D0nni387/flex-demo/blob/main/assets/css/style.css

Code from chat gpt for resposive photos



Google font from https://fonts.google.com/selection/embed
