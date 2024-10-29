package org.example;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        var scanner = new Scanner(System.in);

        System.out.println("What is BTC price today?");
        var rate = scanner.nextDouble();

        while (true) {
            System.out.println("How mush $ do you have?");
            var dollars = scanner.nextDouble();

            if (dollars == 0)
                break;

            var result = dollars / rate;
            System.out.println("Result = " + result);
        }
    }
}
