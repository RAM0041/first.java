# first.java
answers for the assignment in first.java

Q1: Write a program to print whether a number is even or odd, also take input from the user.
ans:

package random;

import java.util.Scanner;

public class practice {
    public static void main(String[] args) {
        System.out.println("Enter a number: ");
        Scanner in = new Scanner(System.in);
        int number = in.nextInt();
        if (number%2 == 0){
            System.out.println("even number!");
        }
        else{
            System.out.println("odd number!");
        }
    }
}
