package com.company;
import java.lang.String;
import java.util.Scanner;
import java.util.concurrent.SynchronousQueue;

public class Main {

    public static void main(String[] args) {
        System.out.println("5 4 3 2 1");
        Scanner number = new Scanner(System.in);
        int first, result, first1;
        System.out.print("Enter first num:");
        first = number.nextInt();
        first1 = first - 1;
        int i = 0;
        do{
            i++;
            first = first + i;

        }
        while ( i < first1);
        System.out.print(first);
    }
}
