import java.util.Scanner;
public class QuestionOne
{
 public static void main(String args[])
 {
 Scanner keyboard = new Scanner(System.in);
 
 int a = 1 + (int) (Math.random() * 99);
 int guess;
 System.out.printLn("Iam thinking of a number from 1 to 100...guess what it is ?");
 guess = keyboard.nextInt();
 while(guess != a){
 if (guess > a)
 {
 System.out.println("lower");
 }
 else if (guess < a)
 { 
 System.out.println("higher");
 }
 else
 {
 System.out.println("Congratulations. you guessed the number X tries");
 }
 }
 }
 }
