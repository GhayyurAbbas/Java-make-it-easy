# Java-make-it-easy
Now here you people are gonna see some new and easy ways of driving java
Without running your hands on keyboard like headless chickens
import java.util.Scanner
class student{
   private int age;
   private String name;
   public student(){}
   public studrnt(int age, String name){
          this.name=name;
          this.age=age;
   }
   public student(student NewStudent)
   {
      this(NewStudent.age, NewStudent. name);
   }
   public void display(int age, String name)
   {
      if(age==0&&name=="")
      {
         System.out.println(age);
         System.out.println(name);
      }
      else{ System.out.println(this.age); System.out.println(this.name);}
   }
   
