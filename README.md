import java.util.Scanner;
public class Array Example{
    public static void main(string[]args){
        Scanner input = new Scanner(System.in);
        System.out.print("Enter the number of elements:");
        int n= input.nextInt();
        int[] numbers = new int [n];
        System.out.println("Enter"+n+"elements:");
        for(int i=0; i<n;i++){
            numbers[i]=input.nextInt();
            }
        System.out.println("The elements in the array are:");
        for (int i=0;i<n;i++){
            System.out.print(numbers[i]+"");

        }
        input.close();
    }
}
