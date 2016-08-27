# SayHello2Methods

The following code:
public class Methods {
public static void main(String[] args) {
displayMessage();
displayMessage();
}
public static void displayMessage() {
System.out.println("Hello World!");
}
}
produces the following output:
Hello World!
Hello World!

Study the above code and write a program to produce the following output:

Mantra for semester two:
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.
Programming is easy, I am going to nail Java in semester two.

You should use a loop and a method in your code. Note that, in practice, you rarely
write a method with just a single statement. The goal of this exercise, however, is simply
to introduce you to the concepts of writing and calling your own methods.

What is the output of the following Java program? Write the code below and examine
the output.
public class HierarchicalMethods
{
public static void method1()
{
System.out.println("I am method 1.");
}
public static void method2()
{
method1();
System.out.println("I am method 2.");
}
public static void method3()
{
method2();
System.out.println("I am method 3.");
method1();
}
public static void main(String[] args)
{
method1();
method3();
method2();
method3();
}
}

Write methods to draw each of the following shapes:
drawHair  ||||
drawEyes  * *
drawNose  <>
drawMouth <-->
Write methods, drawFace1 and drawFace2 to draw the following faces:

||||
* *
<>
<-->

* *
<>
<-->
||||

Add a method drawEyebrows that is called from drawEyes:
drawEyebrows " "
Write a program that implements the following structure chart:
main
drawFace3
drawHair drawEyes drawNose drawMouth drawHair
drawEyebrows
The output of your program should look as follows:

||||
" "
* *
<>
<-->
||||

You are tasked with writing a program to print the following figures:
*****
*****
 * *
  *
 * *
*****
*****
 * *
  *
 * *
*****
*****
  *
  *
  *
*****
*****
 * *
  *
 * *
Complete the following structure chart and implement the program. The three vertical
asterixes are only used once in this question but you may assume they would be reused.
main
drawFigure1 drawFigure2 drawFigure3
Your program should have a total of seven methods (including main) and follow the
hierarchical arrangement of the above structure chart (e.g. drawFigure2 should call two
methods, one of which calls a further two methods).

Using methods to eliminate code redundancy, write a program to draw the following
shuttle:
   /\
  /  \
 /    \
/      \
#------#
-      -
-      -
-      -
#------#
-      -
-      -
-      -
#------#
-      -
-      -
-      -
#------#
  //\\
 //  \\
//    \\

You should write a method called shuttle that is to be called from main. Begin by
drawing a structure chart for your program.
Note that your code should not contain any duplicate print statements, e.g. the string
#------# should only appear once in your program.
