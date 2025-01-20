# Multiplication-table
Multiplication Table

import java.util.Scanner;

public class MultiplicationTable {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a number: ");
        int num = sc.nextInt();
        System.out.println("Multiplication Table of " + num + ":");
        for (int i = 1; i <= 10; i++) {
            System.out.println(num + " x " + i + " = " + (num * i));
        }
    }
}

Output

Enter a number: 3  
Multiplication Table of 3:  
3 x 1 = 3  
3 x 2 = 6  
...  
3 x 10 = 30
