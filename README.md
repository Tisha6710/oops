# oops
Student info
package OOPSinJava;
public class StudentClass {
    // creating a new data type
    public static class Student{
        String name;
        int rno;
        double percentage;
    }
    public static void main(String[] args) {
        Student x =new Student();
        x.name="Tisha";
        x.rno=90;
        x.percentage=97.8;
        System.out.println(x.percentage);

        Student s =new Student();
        s.name="Akshit";
        s.percentage=89;
        s.rno=8;
        System.err.println(x.rno);
    }
}
