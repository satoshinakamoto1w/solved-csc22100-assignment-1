Download Link: https://assignmentchef.com/product/solved-csc22100-assignment-1
<br>
5/5 - (1 vote)

1- Create a hierarchy of Java classes as follows:

MyLine is_a MyShape; MyRectangle is_a MyShape; MyOval is_a MyShape.

Class MyShape:

Class MyShapeis the hierarchy’s superclass and extends the Java class Object. An implementation of the class defines a reference point (x, y) and the color of the shape. The class includes appropriate class constructors and methods, including methods that perform the following operations:

<ol>

 <li>getX, getY – return the x- and y-coordinates of the reference point of the MyShape object;</li>

 <li>area, perimeter – return the area and perimeter of the object.. MyShape</li>

</ol>

c.d. draw– draws a MyShape object.

These methods must

be overridden in each subclass in the hierarchy

methods return zero.

toString

–

returns the object’s description as a String. This method must be

overridden in each subclass in the hierarchy;

This method must be overridden in each subclass

object, it paints the drawing canvas in the color

For the

. Class MyLine:

MyShape

Class MyLine extends class MyShape. The MyLine object is a straight line segment defined by the endpoints (x1, y1) and (x2, y2). The MyLine object may be of any color. The class includes appropriate class constructors and methods that perform the following operations:

<ol>

 <li>length — returns the length of the MyLine object;</li>

 <li>xAngle — returns the angle (in degrees) of the MyLine object with the x-axis;</li>

</ol>

object, the

in the hierarchy. For the

specified

c. toString — returns a string representation of the MyLine object, including the line’s endpoints, length, and angle with the x-axis;

d. draw — draws a MyLine object.

Class MyRectangle:

Class MyRectangle extends class MyShape. The MyRectangle object is a rectangle of height h and width w, and a top left corner point p(x, y), and may be filled with a color. The class includes appropriate class constructors and methods, including methods that perform the following operations:

<ol start="5">

 <li>getX, getY, getWidth, getHeight — return the width, height of the MyRectangle object</li>

 <li>toString— returns a string representation of the MyRectangle object: top left corner point, width, height, perimeter, and area;</li>

 <li>draw— draws a MyRectangle object of height h and width w, anchored at p(x, y).</li>

</ol>

Class MyOval:

Class MyOval extends class MyShape. The MyOval object is defined by an ellipse within a rectangle of height h and width w, and a top left corner point p(x, y). The MyOval object may be filled with a color. The class includes appropriate class constructors and methods, including methods that perform the following operations:

<ol start="2">

 <li>getX, getY, getA, getB — return the x- and y-coordinates of the center point and abscissa of the MyOval object;</li>

 <li>toString— returns a string representation of the MyOval object: axes lengths, perimeter, and area;</li>

 <li>draw— draws a MyOval object.</li>

 <li>2-  Use JavaFX graphics and the class hierarchy to draw a geometric configuration comprised of a sequence of alternating concentric ovals and their inscribed rectangles as illustrated below, subject to the following additional requirements:

  <ol>

   <li>The code is applicable to canvases of variable height and width;</li>

   <li>The dimensions of the shapes are proportional to the smallest dimension of thecanvas;</li>

   <li>The ovals and rectangles are filled with different colors of your choice, specifiedthrough a MyColor enum reference type.</li>

  </ol></li>

 <li>3-  Explicitly specify all the classes imported and used in your Java code.</li>

</ol>