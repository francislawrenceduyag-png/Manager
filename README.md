import java.util.Scanner
public class Manager{
public static void main(Strings [] args) {
Scanner Scanner = new Scanner(System.in);

System.out.println("Enter Employee Name!");
String name = input.nextLine();


System.out.println("Is The Employee Present? {"true/false"} ");
BooleanonShilf = input.nextBoolean();

System.out.println("Are You Late (Yes/No) ");
String isLate = input.nextLine();
boolean isLate = shilfInput.equalIgnoreCase("Yes");

System.out.println("How Many Employees Are Present Today!");
int employeePresent = input.nextInt();

Office office = new Office(100, 10);
Employees employee = new Employee(name, onShilf);
Equipment equipment= new Equipment(10);

System.out.println("\n----EMPLOYEE DETAILS----);
System.out.println("Name: " + employee.employeename);
System.out.println("On Shilf " + employee.onShilf);
System.out.println("Late " + employee.isLate);
SYstem.out.println(" Working Total Hours: " + employee.employeeworkingTotal());public class Equipment {
   
    
class Office{
    int employeePresnet;
    int shilfTime;

    office(int employeePresent, int shilfTime) {
        this.employeePresent = employeePresent;
        this shilfTime = shilfTime;
    }
double totalEmployee()  {
return employeePresent;
}
double totalTime() {
    return employeePresent * shilfTime;
}
}
    public Resources resources;
    public int computerFixed;
   
    public Equipment() {
        resources = new Resources();
        computerFixed = 0;
    }
   
    public Equipment(int initialFixed) {
        resources = new Resources();
        computerFixed = initialFixed;
    }
   
    public Equipment(Resources res, int initialFixed) {
        resources = res;
        computerFixed = initialFixed;
    }
   
    public double totalComputers() {
        return 50.0; 
    }
   
    public boolean computerFixed() {
        return computerFixed > 0;
    }
}


//Section below copy paste sa main.
//Equipment eq = new Equipment(22);

// Or with both values
//Resources myResources = new Resources();
//Equipment eq2 = new Equipment(myResources, 22);

//System.out.println(eq.computerFixed);
//System.out.println(eq.computerFixed());





}
}

