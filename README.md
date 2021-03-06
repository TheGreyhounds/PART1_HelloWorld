# PART1_HelloWorld
Just a simple HelloWorld to get you started on your journey with Java.

The HelloWorld has a lot going on under the hood.
For one, you may notice that the code itself is
wrapped in the function "main()", which itself is
wrapped in a class called HelloWorld. It's no
coincidence that the class name is the same name
as the Java source file. In Java, the source file
must have the same name as the public class it
contains, or the file will not compile.

The words "public," "static," and "void" are all
identifiers that signal to the compiler how the code
following them operates. The main() function operates
as the entry point to our program. Every Java program
has a main() function, and every main function is
written in this way.

As for the actual code that runs, we are simply calling
the function "println(String ourMessage)" which is a part
of the static object "out," which in turn is a part of the
module "System" (in Java, periods access an instance variable 
or a method held by the object it was called on). Finally, 
the semi-colon signals to the compiler that our statement 
has ended, which in this case and in most cases is on a single 
line (though you may certainly have a statement take up more 
than one line, so long as it is ended with a semi-colon).

You don't have to understand all of the technicals right now. 
You just need to know that the main() function is required for 
every Java program, and that System.out.println() is the way 
we will be writing output to the console.
