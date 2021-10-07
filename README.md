# Here is What i am learning  on 
    My  name is Sindorov Elyor who is from Uzbekistan.I would like to be a Frontend programmer and I am very hard prepared for this. In addition, I am very curious, enthusiastic and fast-paced with people.My goal in life is to become a future mature pragrammist and reach my heights in this field
    Programming languages
    CSS
    Java
    C++
    HTML
    Code Excample
    class Rectangle {
    private double height;
    private double width;
    static int numberOfRectangle;

    Rectangle() {
		++numberOfRectangle;

    }

    Rectangle(double h, double w) {
		++numberOfRectangle;
        height = h;
        width = w;
    }

    Rectangle(Rectangle r) {
		++numberOfRectangle;

    }

    double getHeight() {
        return this.height;
    }

    void setHeight(double height) {
        this.height = height;
    }

    double getWidth() {
        return this.width;
    }

    void setWidth(double width) {
        this.width = width;
    }

    double getArea() {
        return this.height * this.width;
    }
	

    static int getNumberOfRectangle() {
	
		return numberOfRectangle;
    }

    boolean equalTo(Rectangle obj) {
        if (this.height == obj.height && this.width == obj.width)
            return true;
        else return false;
    }

}

interface GeometricComparable {
    boolean equalTo(Rectangle obj);
}

public class InterfaceDemo
{
    public static void main(String[] args)
    {
        Rectangle rec1 = new Rectangle ();
        System.out.println ( "Rectangle object number "+Rectangle.getNumberOfRectangle());

        Rectangle rec2 = new Rectangle (10.4, 20.2);
        System.out.println ( "Rectangle object number "+Rectangle.getNumberOfRectangle());

        Rectangle rec3 = new Rectangle (rec1);
        System.out.println ( "Rectangle object number "+Rectangle.getNumberOfRectangle());

        System.out.println ( "Rectangle object rec1 and rec2 are equal " + rec1.equalTo(rec2));
        System.out.println ( "Rectangle object rec1 and rec3 are equal " + rec1.equalTo(rec3));


    }
}

Contact number +998949132002
               +998915028179
Gmail.sindorovelyor123@gmail.com               


