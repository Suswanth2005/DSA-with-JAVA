import java.util.*;
class Encapsulation
{
  private int a = 100;
  private int b = 20;

//to access private variable we use methods like "getter" and "setter"
  public int getterA ()
  {								//getter
	return this.a;
  }
  public int getterB()
  {
      return this.b;
  }
  public void setterA(int a) //setter
  {
      if(a<100){
          
          this.a=a;
          System.out.println("Value changed to: "+a);
      }
      else{
          System.out.println("value was not changed");
      }
  }

}
public class Main
{
  public static void main (String[]args)
  {
	Encapsulation e = new Encapsulation ();
	// System.out.println(e.a); //It's prints error because "a" has private access(we can't access private variable outside of a class)
	  System.out.println (e.getterA ());
	  System.out.println(e.getterB());
	  Scanner sc = new Scanner(System.in);
	  int a = sc.nextInt();
	  e.setterA(a);

  }

}
