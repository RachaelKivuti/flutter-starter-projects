# Widget Tree

➤ The fundamentals of widgets

➤ To use a full widget tree

➤ To use a shallow widget tree


#### The Three ways to create a shallow widget tree by refactoring:
       -with a constant 
 
       -with a method 
 
       -with a widget class.

### Widgets used

➤ Scaffold—Implements the Material Design visual layout, allowing the use of Flutter’s
Material Components widgets

➤ AppBar—Implements the toolbar at the top of the screen

➤ CircleAvatar—Usually used to show a rounded user profile photo, but you can use it
for any image

➤ Divider—Draws a horizontal line with padding above and below

### Widgets can be used with both Material Design and Cupertino(for iOS):


➤ SingleChildScrollview—This adds vertical or horizontal scrolling ability to a single
child widget.

➤ Padding—This adds left, top, right, and bottom padding.

➤ Column—This displays a vertical list of child widgets.

➤ Row—This displays a horizontal list of child widgets.

➤ Container—This widget can be used as an empty placeholder (invisible) or can specify
height, width, color, transform (rotate, move, skew), and many more properties.

➤ Expanded—This expands and fills the available space for the child widget that belongs to a
Column or Row widget.

➤ Text—The Text widget is a great way to display labels on the screen. It can be configured
to be a single line or multiple lines. An optional style argument can be applied to change
the color, font, size, and many other properties.

➤ Stack—Stack lets you stack widgets on top of each other and use
a Positioned (optional) widget to align each child of the Stack for the layout needed. 

➤ Positioned—The Positioned widget works with the Stack widget to control child positioning and size. A Positioned widget allows you to set the height and width. You can
also specify the position location distance from the top, bottom, left, and right sides of the
Stack widget.

### CrossAxisAlignment and MainAxisSize


In Flutter's layout system, widgets (like Row, Column, and Flex) have two axes: 
       -the main axis  
       -the cross axis 
The main axis is determined by the direction in which the widgets are laid out (horizontal for Row, vertical for Column), while the cross axis is perpendicular to the main axis.

-CrossAxisAlignment.start: Aligns children to the start of the cross axis.

-CrossAxisAlignment.end: Aligns children to the end of the cross axis.

-CrossAxisAlignment.center: Aligns children at the center of the cross axis.

-CrossAxisAlignment.stretch: Stretches children to fill the cross axis.

-CrossAxisAlignment.baseline: Aligns children along their baseline if they have one, 

-MainAxisSize.min: Specifies that the layout widget should occupy the minimum amount of space along its main axis. 
In other words, the widget should be as small as possible while still accommodating its children.

-MainAxisSize.max: Specifies that the layout widget should occupy the maximum amount of space along its main axis. 
In other words, the widget should expand to fill all available space along its main axis.


### Book used to learn flutter framework, dart language: 
Beginning Flutter by Marco L. Napoli

