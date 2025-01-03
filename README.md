import java.util.Scanner;

class Circle {
    double radius;
    String color;

    Circle() {
        radius = 1.0;
        color = "blue";
    }

    Circle(double radius) {
        this.radius = radius;
        color = "blue";
    }

    Circle(double radius, String color) {
        this.radius = radius;
        this.color = color;
    }

    double getArea() {
        return Math.PI * radius * radius;
    }

    double getRadius() {
        return radius;
    }

    String getColor() {
        return color;
    }
}

class Cylinder extends Circle {
    double height;

    Cylinder() {
        super();
        height = 2.0;
    }

    Cylinder(double height) {
        super();
        this.height = height;
    }

    Cylinder(double height, double radius) {
        super(radius);
        this.height = height;
    }

    Cylinder(double height, double radius, String color) {
        super(radius, color);
        this.height = height;
    }

    double getArea()

<!---
sonu750305/sonu750305 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
