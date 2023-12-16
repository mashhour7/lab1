// Lab 1 // CS11211

// Import statement to include the Scanner class import java.util.Scanner;

/**

There is an issue with the class name.

For this exercise, you are not allowed to change the file name!

However, the filename should MATCH the class name! */ public class app {

/*

main()

Program execution begins with this method.

Unfortunately, the main method declaration has some issues. Fix them! */ public static void main(String[] args) { Scanner scnr = new Scanner(System.in);

// A variable called base int base; // Declare another variable called head to store the second digit int head;

/* Write your code here */

// The following prompts and reads the first digit from the user System.out.println("Enter the base digit: "); base = scnr.nextInt();

// Write the code to read the second digit similar to above but // store the digit into head System.out.println("Enter the second digit: "); head = scnr.nextInt();

// Print an arrow on the screen using the above digits // Ex: If the input is: // 0 1 // the output is: // 1 // 11 // 00000111 // 000001111 // 00000111 // 11 // 1

/* Write your code here for printing the arrow */

System.out.println(" 1\n 11\n00000111\n000001111\n00000111\n 11\n 1");

/***** Do NOT MODIFY BELOW! *******/ scnr.close();     }

}
