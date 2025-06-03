import java.util.Scanner;




public class lond1 {

static void student(String name , double grade){

    System.out.println("Name is "+name);
    System.out.println("Grade is "+grade);

    if(grade>=50||grade<=100){
            System.out.println("Student "+name+" Congratulations you passed the exam ");
    }else if(grade<50||grade >=0){
            System.out.println(" Failed ");
    }
}

public static void main(String[] args) {

   Scanner in = new Scanner (System.in);

      System.out.println(" Enter number of the student : ");
      int s=0,f=0,NumberOfTheStudent=in.nextInt();

      
      double grade , avg=0 ;
      String name ;

   for(int i=0  ;i<NumberOfTheStudent;i++ ){
      System.out.print("Student name : ");
      name=in.next();
      System.out.print("Student grade : ");
      grade=in.nextDouble();

    if(grade>100||grade<0){
      System.out.println("Invalid grade! Please enter number between 0 and 100");
      i--;
      continue;
       }

   student(name,grade);

      avg+=grade ;

   if(grade>=50){
       s++;
    }else
       f++;
              }
      System.out.println("Number of successful Student : "+s);
      System.out.println("Number of those who failed : "+f+"\n");
    char c ;
      System.out.println("If you want a avrage of the grades press y Or to exit press any key.");
      c =in.next().charAt(0);
      
   switch(Character.toLowerCase(c)){
       case 'y' :
      System.out.println("avrage of grades is = "+(avg/NumberOfTheStudent)+".");
           System.out.println("Good Bye");
       break;
       default :
           System.out.println("Good Bye");
      }
     
    }

}
