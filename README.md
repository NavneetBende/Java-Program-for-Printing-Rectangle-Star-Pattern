Printing Rectangle Star Pattern
In this problem we’re going to code a Java Program for printing rectangle star pattern.

The process of this program is  take number input from user and store it in variable named as row and col then run the i for loop start from i=1 to i<= row . then take another inner loop start from j=1 to j<=col and then take a star printing statement after that take a line change statement

Print Rectangle Star Pattern
Algorithm:
Take the number of rows and columns as input from the user ( length and breadth of the rectangle) and store it in two different variables. (‘row’ and ‘col’ in this case)
Run a loop ‘row’ number of times to iterate through all the rows. From i=1 to i<=row . The loop should be structured as for (int i = 1; i <= row; i++)
 Run a nested loop ‘col’ times to iterate though each column of a row. From j=1 to j<col. The loop should be structured as for(j=1 ; j<=col ; j++).
Inside the nested loop print star to print a star in each column of  a row. System.out.println(“*”);
In the main loop print a new line to move to the next line. System.out.println();
Code in Java:
import java.util.Scanner;
public class Pattern1 {
    public static void main(String[] args) {
    	Scanner sc = new Scanner(System.in);
		System.out.println("Enter row and col");
		int row = sc.nextInt();
		int col = sc.nextInt();
		
		for (int i = 1; i <= row; i++) {
			for (int j = 1; j <= col; j++) 
				System.out.print("*");
			System.out.println();
		}
	}

}
