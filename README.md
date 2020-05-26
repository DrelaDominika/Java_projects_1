# Java_projects_1
My first repository which focuses on learning the basics of Java.

## Table of contents
* [General info](#general-info)
* [Setup](#setup)
* [Code Examples](#code-examples)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
This repository consists of my first few projects in Java which were created in IntelliJ - IDE. 

## Setup
You can download the tool mentioned here: https://www.jetbrains.com/idea/download/#section=windows

The Java Development Kit: https://www.oracle.com/java/technologies/javase-jdk11-downloads.html will alse be required.

## Code Examples
Code which allowes you to calculate the factorial of a given number:

```package com.company;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        System.out.println("Ile liczb chcesz podac?");
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();

        double[] arr = new double[n];
        double total = 0;

        for(int i=0; i<arr.length; i++){
            System.out.print("Wpisz liczbe no. "+(i+1)+": ");
            arr[i] = scanner.nextDouble();
        }
        scanner.close();
        for(int i=0; i<arr.length; i++){
            total = total + arr[i];
        }

        double average = total / arr.length;

        System.out.format("Srednia tych liczb wynosi: %.3f", average);
        
    }
}
```


## Status
All projects are finished.

## Inspiration
Prejects are based on the book "Thinking in Java" written by Bruce Eckel.

## Contact
Created by [@DrelaDominika] - feel free to contact me!
