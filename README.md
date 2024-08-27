# myShop






import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("""
                Prices:
                Bubblegum: $2
                Toffee: $0.2
                Ice cream: $5
                Milk chocolate: $4
                Doughnut: $2.5
                Pancake: $3.2""");

        double income;
        System.out.println("""
                Earned amount:
                Bubblegum: $202
                Toffee: $118
                Ice cream: $2250
                Milk chocolate: $1680
                Doughnut: $1075
                Pancake: $80
                """);
        
        income = 7777.0;
        System.out.println("Income: $" + income);
        System.out.println("Staff expenses:");
        int staffExp = scanner.nextInt();
        System.out.println("Other expenses");
        int otherExp = scanner.nextInt();

        int netIncome = (int) (income - (staffExp + otherExp));
        System.out.println("$" + netIncome);
    }
}
