# Manager
import java.util.Scanner;

public class Manager {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        System.out.print("Enter Name: ");
        input.nextLine();

        Office office = new Office(5, 8);
        Employees employee = new Employees(true);
        Equipment equipment = new Equipment(10);

        System.out.println("\nOn Shift: " + employee.onShift);
        System.out.println("Working Total: " + employee.workingTotal());

        System.out.println("Employees Present: " + office.totalEmployee());
        System.out.println("Total Time: " + office.totalTime());

        System.out.println("Total Computers: " + equipment.totalComputers());
        System.out.println("Computer Fixed: " + equipment.computerFixed());

        input.close();
    }
}
