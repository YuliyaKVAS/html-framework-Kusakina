# html-framework-Kusakina
There are classes container, row and column classes (col-md-i, col-sm-i, col-lg-i, i=1...12)
 that create a grid.
The grid is capable to respond to changes in screen expansion.
There are several media queries (for 768px,992px, 1200px ) that allow to set certain width of the 
'div' with class  "container" depending on the screen expansion and also the width of each 
column (col-sm-1....col-lg-12) is defined in percentage.

Also classes  for adding float to elements (such as pull-left(element floats to the left of its container)
and pull-right(to the right of its container)) are created. In the clearfix class there is a clear: both 
property that prevents floating elements on either the left and the right side.

And also the are several classes for work with flex technology.
flex class is using display: flex prooerty to determine flexible 'div'.
flex-row and flex-column are using flex-direction property to build items in a row or in a column inside 
the 'div' element.
space-between class using justify-content: space-between property, so items are evenly distributed in 'div'.
x-start and x-end classes are also using justify-content property with flex-start and flex-end values
to make items are packed toward the start and the end of 'div'. Class y-center is using priperty
align-items: center, so items can be centered in the cross-axes.
