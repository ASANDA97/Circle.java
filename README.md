# Circle.java
package myCircle;

	// Constructors
	public class Circle(int x, int y )

	{
		private double radius;
	   // Need to construct an instance of MyPoint for the variable center
	   center = new Point(x, y);
	   this.radius = radius;


	public Circle(point center, double radius) {
	   // An instance of MyPoint already constructed by caller; simply assign.
	   this.center = center;

	}
	public Circle() {
	   center = new Point(x, y) ; // construct MyPoint instance
	   this.radius = radius;
	}

	// Returns the x-coordinate of the center of this MyCircle
	public int getCenterX() {
	   return Center.getX();   // cannot use center.x and x is private in MyPoint
	}

	// Returns the distance of the center for this MyCircle and another MyCircle
	public double distance(MyCircle another) {
	   return center.distance(another.center); // use distance() of MyPoint
	}

	public double getRadius() {
		return radius;
	}
	public void setRadius(double radius) {
		this.radius = radius;
	}
	public double getArea() {
		return result=PI.this.radius*this.radius;
		return results;
	}
	public double getDiameter() {
		return 2*this.radius;
	}
	public double getCircumference() {
		return 2*PI.this.radius;
	}


	public static void main(String[] args) {
		// TO DO Auto-generated method

   Circle myCircle  = new Circle();
   Scanner sc = new scanner (System.in);
   double radius = sc.nextDouble();
   Circle myCircle2 = new Circle ();
   System.out.println("The area of the circle is",myCircle2.getArea());
   System.out.println("The diameter of the Circle is", myCircle2.getDiameter());
   System.out.println("The Circumference of the circle is",myCircle2.getCircumference());

	   }
