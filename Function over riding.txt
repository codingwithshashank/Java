class Vivo
{
    void setCamera()
     {
      System.out.println("Vivo camera is set.");
     }
}

class Iq extends Vivo
{
    void setCamera()
     {
     System.out.println("IQ camera is set.");
     }
}

public class Mobile
{
      public static void main(String[] args)
       {
       Iq c=new Iq(); 
       c.setCamera();
       }
}