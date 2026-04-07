# Student-Management-System
package project;
import java.util.*;

public class Project {

	public static void main(String[] args) {
		Student s1 =new Student("Kiran",192312353,"ECE");
		Student s2 = new Student("Srikar",192312346,"ECE");
		Student s3 = new Student("shashank",1923123552,"ECE");
		//System.out.println(s1);
		//System.out.println(s2);
		//System.out.println(s3);
		
ArrayList<Student>list=new ArrayList<>();
list.add(s1);
list.add(s2);
list.add(s3);
System.out.println(list);
	}

}
class Student{
	String name;
	int Roll ;
	String depart;
	Student(String name,int Roll ,String depart){
		this.name=name;
		this.Roll  =Roll ;
		this.depart= depart;
	}
public  String toString() {
	        return "Student Name: " + name + ", Roll : " + Roll + ", Depart: " + depart + "";			
	        

}}
