/* "WAP to print all the charecters of English alphabet as given below using For loop".
          "{A,b,C,d,E,f,G,h,I,j,K,l,M,n,O,p,Q,r,S,t,U,v,W,x,Y,z}"
*/



import java.io.*;
import java.util.*;

public class Main {
    public static void main(String[] args) {

/* We are using ASCII values of Alphabets in this programe that is 'A'=65, 'Z'=90, 'a'=97, 'z'=122 */
            
            for (int i=0;i<=25;i++) {          
               if (i%2 == 0) {                  // A to Z = 65 to 89
                  char ch= (char) ('A'+1*i);
                System.out.print(ch+" ");
               }
               else {                           // b to z = 98 to 122 
                  char ch1 = (char) ('a'+1*i);
                       System.out.print(ch1+" ");
                    }
            }
   }
} 
