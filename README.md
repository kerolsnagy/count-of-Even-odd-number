# count-of-Even-odd-number
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        Scanner k =new Scanner(System.in);
        int num;
        int countEven=0,countOdd=0;
        int i=0;
        while (i<10)
        {
            System.out.println("Enter intger number..");
            num= k.nextInt();
            if (num%2==0)
                countEven++;
            else
                countOdd++;
            i++;
        }
        System.out.println("the number of Even number =" + countEven);
        System.out.println("the number of Odd number =" + countOdd);

    }
}

