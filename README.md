# 6.-WAP-of-Java-String-Comparison-2-String
import java.util.*;
class level1{
    Scanner sn=new Scanner(System.in);
   
    void ok(){
        String p=sn.nextLine();
       String k=sn.nextLine();
       if(p.equalsIgnoreCase(k))
       {
           System.out.println("given string are same irrespective of case");
       }
       else{
           System.out.println("string are not equal");
       }
        
    }
    
}
public class Main
{
	public static void main(String[] args) {
		System.out.println("Enter the word");
	level1 obj=new level1();
		obj.ok();
	}
}
