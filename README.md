import java.io.*;

class Main {


static int areaRectangle(int a, int b)
{
int area = a * b;
return area;
}

static int perimeterRectangle(int a, int b)
{
int perimeter = 2*(a + b);
return perimeter;
}


public static void main (String[] args) {

int a = 5;
int b = 7;
System.out.println("Area = "+ areaRectangle(a, b));
System.out.println("Perimeter = "+ perimeterRectangle(a, b));

}
}
