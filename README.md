## Objectives:

In this lab, you will learn how to do the following:

- Ask the user to input data into your program
- Use the `Scanner` to input a string from the console using `in.nextLine()`
- Store a value entered from the user into a variable
- Output a string to the screen

## Program: Hello World... Revised:
Write a program that asks the user to enter their name and their favorite dessert. 
Then have the program print the following to the screen:
```
Please enter your name:
Hello <name>!
Please enter your favorite dessert:
I hope you like coding JavaScript as much as you like to eat <dessert>.
```
Now write five more creative questions to ask the user and print out sentences using the users input to make fun statements like shown in the example run.

## Key program requirements:

For this program (and virtually all future programs) you will need to get input from the user.  We will use the Scanner class found in the java.util package.  You don't need to worry about what that means right now.  Simply add the following lines of code to your Lab2a program.

Before your class declaration, add the following code:
```
import java.util.Scanner;
```
The first line of code in your main class should be:
```
Scanner in = new Scanner(System.in);
```
To use the Scanner class to get input from the user and store it in a variable called name, your code should look something like this:
```
String name = in.nextLine();
```
When put together correctly, the first few lines of your code should look like this:
```
import java.util.Scanner;

public class Main {
     public static void main(String[] args) {
     // Using Scanner for getting Input from user
     Scanner in = new Scanner(System.in);
     //Ask the user's name
     System.out.println("Please enter your name: ");
     String name = in.nextLine();
     System.out.println("Hello " + name + "!");
     System.out.println();
     // Write more below
     } //end of main() method
} // end of Main class
```
## Example Run:

Please enter your name:
Jeff
Hello Jeff!

What is your favorite dessert?
Cake
I hope you like coding Java as much as you like to eat Cake.

What is your favorite color?
Green
So, you like the color Green. My favorite color is 0000ff.

Where were you born?
California
I was born in Silicon Valley. If I had been born in California, perhaps we would have been friends.

What is your favorite kind of pet?
Dog
I'm sure a Dog is safer than my pet. I have a pet mouse.... but it always BYTES! HaHaHa!

What is your favorite insect?
Butterflies
Wow! You like Butterflies!?! I like spiders. They make great WEB sites but sometimes they BUG me!

Who was your favorite speaker at the last General Conference?
President Nelson
I agree. President Nelson was great! I'm just glad they didn't make Java against the Word of Wisdom!!!

## Hints:
**!!To get full credit you need your code to have the exact spacing and punctuations!!**