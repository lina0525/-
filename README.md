# -
金字塔
package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
                int i, j, k, n;
                Scanner input = new Scanner(System.in);
                System.out.print(" ");
                n = input.nextInt();
                for (i = 1; i <= n; i++) {
                    for (j = 1; j <= n - i; j++)
                        System.out.print(" ");
                    for (k = 1; k <= 2 * i - 1; k++)
                        System.out.printf("*");
                    System.out.printf("\n");
                }
            }
        }
