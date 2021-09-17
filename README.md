/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package simplepattern3;

import java.util.Scanner;
/**
 *
 * @author cmd
 */
public class Simplepattern3 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int i,j;
        for(i=1;i<=5;i++)
        {
            {
                for(j=1;j<=i;j++)
                {
                    System.out.print("*");
                    
                }
                System.out.println();
            }
        }
        // TODO code application logic here
    }
    
}
