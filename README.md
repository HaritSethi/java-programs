# java-programs

java program 1

import java.util.*;
class a1{
  public static void main(String[] args){
    Scanner s1 = new Scanner(System.in);
    System.out.println("Enter an integer");
    int a;
    a = s1.nextInt();
    System.out.println("The entered integer is " + a);
  }
}

______________________________________________________________________
java program 2

public class a3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int a=45, b=32;
System.out.println("product is : "+ (a*b));
	}

}

___________________________________________________________________

java program 3


public class a4 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("final number is " + ((60+82)*5-4));
	}

}

_______________________________________________________________

java program 4

import java.util.*;
class a6{
  public static void main(String[] args){
    Scanner s1 = new Scanner(System.in);
    System.out.println("Enter your first name");
    String f = s1.next();
    System.out.println("Enter your last name");
    String l = s1.next();
    System.out.println("Your name is " + f+(" ") + l);
  }
}

________________________________________________________________

java program 5


public class a7 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a=123;
		float b=321456;
		char c='h';
		System.out.println(a + "\n" + b + "\n" + c);
	}

}

______________________________________________________________

java program 6


public class a9 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
double a=8.2;
int b =6;
double c;
c=a*b;
System.out.println("value of c :" + c);
	}

}


____________________________________________________

java program 7


public class a10 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
char a='z';
int b=0;
System.out.println(a+b);
	}

}


________________________________________________

java program 8


public class a11 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		double a;
		a=100.235;
		System.out.println("value of a :" + (int)a);

	}

}


_________________________________________________________

java program 9


public class a12 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
char a='d';
int b=3;
System.out.println("result is: " + (a+b));
	}

}


________________________________________________

java program 10


public class a15 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int len=7, bred=5;
int ar, per;
ar=len*bred;
per=len+bred;
System.out.println("area of rectangle is :"+ ar);
System.out.println("perimeter of rectangle is :"+ per);
	}

}

________________________________________________________

java program 11


public class a17 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int num=2345;
num+=8;
num/=3;
num%=5;
num*=5;
System.out.println("result is :"+ num);
	}

}

__________________________________________________

java program 12


public class a23 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int a=6, b=8;
int c=a;
a=b;
b=c;
System.out.println("values of a and b are " + a + " & "+ b);

	}

}

_______________________________________________________

java program 13


public class a24 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int a=6, b=8;
a=a+b;
b=a-b;
a=a-b;System.out.println("a is :" +a+ "b is :" +b);
	}

}


______________________________________________

java program 14

import java.util.*;
public class a25 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
double f, c;
System.out.println("enter the temp");
Scanner s=new Scanner(System.in);
f=s.nextDouble();
c=(f-32)/(1.8);
System.out.println("temp in celsius is :"+ c);
	}

}


___________________________________________

java program 15



public class a26 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int t=90, b=45, g, a, ab=20, ag;
g=t-b;
a=t/2;
ag=a-ab;
System.out.println("total numbers of girls with grade a are :" +ag);
	}

}

________________________________________________


java-program-16

import java.util.*;
public class a27 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int a, b, sum, prod, prod2;
System.out.println("enter first integer :");
Scanner s1= new Scanner(System.in);
a=s1.nextInt();

System.out.println("enter second integer :");
Scanner s2=new Scanner(System.in);
b=s2.nextInt();

sum=a+b;
prod=a*b;
System.out.println("sum is :"+sum + " product is"+prod );
System.out.println(sum*prod);
	}
}


________________________________________________

java program 17

import java.util.*;
public class a28 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
float l, b;
int area;
System.out.println("enter the length");
Scanner s1=new Scanner(System.in);
l=s1.nextFloat();
System.out.println("enter the breadth");
Scanner s2=new Scanner(System.in);
b=s2.nextFloat();

area = (int)(l*b);
System.out.println("area of the rectangle is " + area);

	}

}


___________________________________________________

java program 18

import java.util.*;
public class a29 {
	public static void main(String[] args){
	
		System.out.println("enter your name :");
		Scanner s1=new Scanner(System.in);
		String name=s1.nextLine();
		
		System.out.println("enter your roll number :");
		Scanner s2=new Scanner(System.in);
		int rollno=s2.nextInt();
		
		System.out.println("enter your field of interest :");
		Scanner s3=new Scanner(System.in);
		String field=s3.nextLine();
		
		System.out.println("Hey, my name is "+ name + " and my roll number is "+ rollno +". My field of interest is "+ field +".");
	}

}

___________________________________________________________

java program 19

import java.util.*;
public class a30 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the side of the square");
Scanner s1=new Scanner(System.in);
int a=s1.nextInt();
int area=a*a;
System.out.println("area of the square is :" + area);
	
	}

}


______________________________________________________

java program 20

import java.util.*;
public class a31 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter first string :");
Scanner s1=new Scanner (System.in);
String a=s1.nextLine();

System.out.println("enter second string :");
Scanner s2=new Scanner (System.in);
String b=s2.nextLine();

System.out.println("new string is " +a +" " +b);
	}

}

_____________________________________________

java program 21

import java.util.*;
public class a32 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter marks 1 :");
Scanner s1=new Scanner(System.in);
int marks1=s1.nextInt();

System.out.println("enter marks 2 :");
Scanner s2=new Scanner(System.in);
int marks2=s2.nextInt();

System.out.println("enter marks 3 :");
Scanner s3=new Scanner(System.in);
int marks3=s3.nextInt();

System.out.println("total marks are :" + (marks1+marks2+marks3) + "\n percentage is :" + ((marks1+marks2+marks3)/3) );
	}

}


________________________________________

java program 22

import java.util.*;
public class a33 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the length :");
Scanner s1=new Scanner(System.in);
int len =s1.nextInt();

System.out.println("enter the breadth :");
Scanner s2=new Scanner(System.in);
int bred =s2.nextInt();

if(len==bred){
System.out.println("it is a square");
}
else{
	

	System.out.println("it ia a rectangle");

	}
	}

}

________________________________________________

jva program 23

import java.util.*;
public class a34 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the two integers :");
Scanner s1=new Scanner(System.in);
Scanner s2=new Scanner(System.in);
int a=s1.nextInt();
int b=s2.nextInt();
if(a>b){
	System.out.println("a is greater than b");
	
}
else{
	System.out.println("b is greater than a");
}
	}

}

_________________________________________

java program 24

import java.util.*;
public class a35 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the number of the units purchased :");
Scanner s1=new Scanner(System.in);
int n=s1.nextInt();
if((100*n)>1000){
System.out.println("total price :"+(100*n*9/10));	
}
else{
	System.out.println("total price :"+(100*n));
}
	}

}

__________________________________________

java progrsm 25

import java.util.*;
class a36 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the salary :");
Scanner s1=new Scanner(System.in);
int sal =s1.nextInt();

System.out.println("enter the year of joining :");
Scanner s2=new Scanner(System.in);
int year=s2.nextInt();
if(year<2012){
	System.out.println("net bonus :"+(sal/20));
			}
else{
		System.out.println("no bonus");
	}

	}

}

______________________________________

java program 26

import java.util.*;
public class a37 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the marks :");
Scanner s1=new Scanner(System.in);
int marks=s1.nextInt();
char grad=0;
if(marks<25){
grad ='F';
}
if(marks>=25 && marks<40){
	grad='E';
	
}
if(marks>=40 && marks<50){
	grad='D';
	
}
if(marks>=50 && marks<60){
	grad='C';
	
}
if(marks>=60 && marks<80){
	grad='B';
	
}
if(marks>=80 && marks<=100){
	grad='A';
	
}
System.out.println(grad);

	}

}

____________________________________

java program 27

import java.util.*;
public class a38 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the ages :");
Scanner s1= new Scanner(System.in);
int age1=s1.nextInt();
Scanner s2=new Scanner(System.in);
int age2=s2.nextInt();
Scanner s3=new Scanner(System.in);
int age3=s3.nextInt();

if(age1>age2 && age1>age3){
	System.out.println("Ist person is the oldest");
}
if(age2>age1 && age2>age3){
	System.out.println("IInd person is the oldest");
	
}
if (age3>age1 &&age3>age2){
	System.out.println("IIIrd person is the oldest");
}
	}

}

_____________________________________

java program 28

import java.util.*;
public class a39 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
System.out.println("enter the number :");
Scanner s1=new Scanner(System.in);
int n =s1.nextInt();
if(n>0){
	System.out.println("output is :"+n);
}
else{
	System.out.println("output is :"+(-1*n));
}
	}

}


______________________________________________________

java program 29

import java.util.*;
public class a40 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner s1=new Scanner(System.in);
System.out.println("enter total classes held :");
int h=s1.nextInt();

Scanner s2=new Scanner(System.in);
System.out.println("enter classes attended :");
int a=s2.nextInt();
int per;
per= (a*100)/h;

System.out.println("percentage of classes is :"+ per);
if(per>=75)
	System.out.println("student can sit in exam.");
else
	System.out.println("Student cannot sit in exam.");
	}

}

__________________________________________________________
