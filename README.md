class Vehicle
{
int speed =50;
}
class Bike extends Vehicle
{
int speed=100;
void display()
{
System.out.println(speed);
System.out.println(super.speed);
}
public static void main(string args[])
{
Bike b=new Bike();
b.display();
}
}
