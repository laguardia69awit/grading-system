import java.util.Scanner;

public class CodesCracker
{
   public static void main(String[] args)
   {
      float[] marks = new float[8];
      float sum=0;
      Scanner scan = new Scanner(System.in);
      
      System.out.print("Enter Total Number of Subjects: ");
      int tot = scan.nextInt();
      System.out.print("Enter Marks Obtained in " +tot+ " Subjects: ");
      for(int i=0; i<tot; i++)
      {
         marks[i] = scan.nextFloat();
         sum += marks[i];
      }
	  
      float avg = sum/tot;
      String grade = "";
      
      if(avg>=94 && avg<=100)
         grade = "A";
      else if(avg>=90 && avg<94)
         grade = "A-";
      else if(avg>=87 && avg<90)
         grade = "B+";
      else if(avg>=83 && avg<87)
         grade = "B";
      else if(avg>=80 && avg<83)
         grade = "B-";
      else if(avg>=77 && avg<80)
         grade = "C+";
      else if(avg>=73 && avg<77)
         grade = "C";
      else if(avg>=70 && avg<73)
         grade = "C-";
      else if(avg>=67 && avg<70)
         grade = "D+";
      else if(avg>=63 && avg<67)
         grade = "D";
      else if(avg>=60 && avg<63)
         grade = "D-";
      else if(avg>=0 && avg<60)
         grade = "F";
      else
         grade = "Invalid Input!";
		 
      if(grade.equals("Invalid Input!"))
         System.out.println("\nInvalid Input!");
      else
         System.out.println("\nGrade = " +grade);
   }
}
