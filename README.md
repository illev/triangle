# triangle
Given: class Point, skeleton of class Triangle.

Implement Triangle methods:

constructor, having three points as parameters.
These points refers to vertices of the triangle.
Ensure the created triangle exists and it is not degenerative.\\
double area()
Return the area of the triangle.
Point centroid()
Return the centroid of the triangle.

Triangle
Given a class Point,
a skeleton of a class Triangle,
implement Triangle methods:

constructor, which has three points as parameters.
Make sure that these points refer to vertices of the triangle.
Ensure that the created triangle exists and it is not degenerative.\

double area()
Return the area of the triangle.

Point centroid()
Return the centroid of the triangle.

Hints:

Triangle existence reference
Triangle area reference
Centroid reference

Please note that you may benefit from introducing more classes.

Examples

You may use Main class to try your code.
There are some examples below.
Sample code:
...
new Triangle(new Point(0,0), new Point(1, 0), new Point(2, 0));
Result: Exception because such a triangle would be degenerative.

Sample code:
...
double area = new Triangle(new Point(0,0), new Point(3, 0), new Point(0, 4)).area();
System.out.println(area);
Output:
6

Sample code:
...
Point centroid = new Triangle(new Point(0,0), new Point(3, 0), new Point(0, 3)).centroid();

System.out.println(centroid.getX());
System.out.println(centroid.getY());
Output:
1
1
