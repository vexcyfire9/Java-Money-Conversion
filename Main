import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner scan = new Scanner(System.in);
        double CAD = 0;
        double USD = 0.7;
        double AUD = 0.9;
        double JPY = 109.18;
        double GBP = 1.81;

        System.out.println("CAD to USD - 1");
        System.out.println("CAD to AUD - 2");
        System.out.println("CAD to JPY - 3");
        System.out.println("CAD to GBP - 4");
        System.out.println("==============");
        System.out.print("> ");

        int choice = scan.nextInt();

        if (choice == 1){
            System.out.print("Enter amount here > ");
            CAD = scan.nextDouble();
            double Convert = CAD * USD;
            String Convert2 = String.format("%.2f",Convert);
            System.out.println("CAD: " + CAD + "$");
            System.out.println("USD: " + Convert2 + "$");
        }
        else if (choice == 2){
            System.out.print("Enter amount here > ");
            CAD = scan.nextDouble();
            double Convert = CAD / AUD;
            String Convert2 = String.format("%.2f",Convert);
            System.out.println("CAD: " + CAD + "$");
            System.out.println("AUD: " + Convert2 + "$");
        }
        else if (choice == 3){
            System.out.print("Enter amount here > ");
            CAD = scan.nextDouble();
            double Convert = CAD * JPY;
            String Convert2 = String.format("%.2f",Convert);
            System.out.println("CAD: " + CAD + "$");
            System.out.println("JPY: " + Convert2 + "¥");
        }
        else if (choice == 4){
            System.out.print("Enter amount here > ");
            CAD = scan.nextDouble();
            double Convert = CAD / GBP;
            String Convert2 = String.format("%.2f",Convert);
            System.out.println("CAD: " + CAD + "$");
            System.out.println("GBP: " + Convert2 + "£");
        }

    }
}
