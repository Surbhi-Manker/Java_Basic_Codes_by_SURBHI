# Java_Basic_Codes_by_SURBHI

package com.google;

import java.util.Scanner;

public class Main {

    static int sum(int a, int b)
    {
    return(a*b);
    }
    public static void main(String[] args) {
        // write your code here
//        System.out.println("Hello Surbhi");
//
//        System.out.println("Hi, This is Surbhi Manker and here, I'm writing my first JAVA Program");
//
//
//        String name = "Hardik";
//        System.out.println(name);
//
//        int a = 23, b = 23;
//        int c = a * b;
//        boolean d = a < b;
//
//        System.out.println(d);
//Taking user input in java

//        Scanner scan = new Scanner(System.in);
//        System.out.println("Enter Day");
//        int day = scan.nextInt();
//        System.out.println(day);

//        if (age> 20) {
////            System.out.println("You are an adult");
////        } else if (age > 5){
////            System.out.println("You are not a kid");
////        }
////        else{
////            System.out.println("You are a kid");
////        }
////        switch (age){
////            case 12:
////                System.out.println("You are 12 years old");
////                break;
////            case 56:
////                System.out.println("You are 56 years old");
////                break;
////            case 23:
////                System.out.println("You are 23 years old");
////                break;
////            default:
////                System.out.println("You are not belongs to any of these cases");
//
////        }
//
//switch (day){
//    case 1:
//        System.out.println("Today is SUNDAY");
//        break;
//    case 2:
//        System.out.println("Today is MONDAY");
//        break;
//    case 3:
//        System.out.println("Today is TUESDAY");
//        break;
//    case 4:
//        System.out.println("Today is WEDNESDAY");
//        break;
//    case 5:
//        System.out.println("Today is THURSDAY");
//        break;
//    case 6:
//        System.out.println("Today is FRIDAY");
//        break;
//    case 7:
//        System.out.println("Today is SATURDAY");
//        break;
//    default:
//        System.out.println("NOT DEFINED");
//
//        package com.google;
//
//import java.util.Scanner;
//
//        public class Main {
//            public static void main(String[] args) {
//                // write your code here
//        Scanner scan = new Scanner(System.in);
//        System.out.println("Enter Day");
//        int day = scan.nextInt();
//        System.out.println(day);
//        if (age> 20) {
//            System.out.println("You are an adult");
//        } else if (age > 5){
//            System.out.println("You are not a kid");
//        }
//        else{
//            System.out.println("You are a kid");
//        }
//        switch (age){
//            case 12:
//                System.out.println("You are 12 years old");
//                break;
//            case 56:
//                System.out.println("You are 56 years old");
//                break;
//            case 23:
//                System.out.println("You are 23 years old");
//                break;
//            default:
//                System.out.println("You are not belongs to any of these cases");
//        }
//        switch (day){
//            case 1:
//                System.out.println("Today is SUNDAY");
//                break;
//            case 2:
//                System.out.println("Today is MONDAY");
//                break;
//            case 3:
//                System.out.println("Today is TUESDAY");
//                break;
//            case 4:
//                System.out.println("Today is WEDNESDAY");
//                break;
//            case 5:
//                System.out.println("Today is THURSDAY");
//                break;
//            case 6:
//                System.out.println("Today is FRIDAY");
//                break;
//            case 7:
//                System.out.println("Today is SATURDAY");
//                break;
//            default:
//                System.out.println("NOT DEFINED");
//        }

//        int j = 0;{
//            System.out.println(j);
//            j+=1;
//        } while(j>=10);
//                for (int k=1;  k>=1; k++);
//                {
//                    System.out.println(k);
//                }
//            }
//        }
//        Loops - For, while, do while loop, for each loop
//        int i = 0;
//        while(i <= 10){
//            System.out.println(i);
//            i += 1;
//        }
//        int J = 0;
//        do {
//            System.out.println(J);
//            J += 1;
//        } while(J >10);
//        for (int i = 0; i <= 10; i++) {
//            if (i >=3) {
//                break;
//            } else {
//                System.out.println(i);
//            }
//        }

//        for(int i = 0; i <= 10; i++) {
//            if (i==5) {
//                continue;
//            }
//                    System.out.println(i);
//        }


//Arrays = collection of multiple values - Single Dimensional Arrays
//       no need of seperate variables
//       [variables = box/container]

//        int[] marks = {10, 20, 30, 40, 50};
//        System.out.println(marks[0]);
//        marks[4] = 45; //change or update values
//        System.out.println(marks[4]);
////to print all marks values [length means = 4 there are four number of marks 01234 = 4 ]
//
//// Classical way to iterate an array
//        for (int i = 0; i < marks.length; i++) {
//            System.out.println(marks[i]);
//        }
//        System.out.println("This is for each loop (Modern way to iterate");
////For each loop
//        for (int value : marks) {
//            System.out.println(value);
//    }
////Double/Triple/Multi-dimensional Arrays
//
////Types of array - according to datatype -  int array/string array/float array/
//        int [][]matrix = {{5,7,9},{2,4,6}};
//        {
//            System.out.println(matrix[0][1]);
//        }
//        String [] lifelong = {"Surbhi","Love","Trustworthy","Rohit","Marriage","Surbhi","Trust","Rohit"};
//        for(String value:lifelong) {
//            System.out.println(value);
//        }
////        TRY - CATCH
//        String[] lifelong = {"Surbhi", "Love", "Trustworthy", "Rohit", "Marriage", "Surbhi", "Trust", "Rohit"};
//        try {
//            System.out.println(lifelong[2]);
//        } catch (Exception e) {
//            System.out.println(e);
//        }
//        {
//            System.out.println("Surohit");
//        }
//Method = block of run, which run only when we call
//Method Call - to sum, mean, mode etc
//create a static method named = sum - which is not
//static is a keyword which belongs to main class
//not belongs to main class object
//will create automatically two int which have mentioned in the static method & their operation
//        System.out.println(sum(1,1));
//        System.out.println(sum (1,1));
//Calculator Project

        Scanner scan = new Scanner(System.in);
        float num1, num2;

        System.out.println("Enter first number");
        num1 = scan.nextFloat();

        System.out.println("Enter second number");
        num2 = scan.nextFloat();

        System.out.print("You have entered ");
        System.out.print(num1);
        System.out.print(" and ");
        System.out.println(num2);

        String prompt = "Enter 0 for Addition, 1 for Subtraction, 2 for Multiplication, 3 for Division";
        System.out.println(prompt);

        int input = scan.nextInt();
        switch (input) {
            case 0:
                System.out.println("Adding these numbers");
                System.out.print("The result is : ");
                System.out.println(num1+num2);
                break;
            case 1:
                System.out.println("Subtracting these numbers");
                System.out.print("The result is : ");
                System.out.println(num1-num2);
                break;
            case 2:
                System.out.println("Multiplying these numbers");
                System.out.print("The result is : ");
                System.out.println(num1*num2);
                break;
            case 3:
                System.out.println("Dividing these numbers");
                System.out.print("The result is : ");
                System.out.println(num1/num2);
                break;
            default:
                System.out.println("Invalid Numbers");
        }
    }
}
