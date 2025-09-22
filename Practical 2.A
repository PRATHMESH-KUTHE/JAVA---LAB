class Employee {
    String name;
    int employeeId;

    Employee(String name, int employeeId) {
        this.name = name;
        this.employeeId = employeeId;
    }

    void DisplayDetails() {
        System.out.println("Name: " + name);
        System.out.println("Employee ID: " + employeeId);
    }
}

class FullTimeEmployee extends Employee {
    double salary;

    FullTimeEmployee(String name, int employeeId, double salary) {
        super(name, employeeId);
        this.salary = salary;
    }

    @Override
    void DisplayDetails() {
        super.DisplayDetails();
        System.out.println("Salary: $" + salary);
    }
}

class PartTimeEmployee extends Employee {
    double hourlyRate;
    int hoursWorked;

    PartTimeEmployee(String name, int employeeId, double hourlyRate, int hoursWorked) {
        super(name, employeeId);
        this.hourlyRate = hourlyRate;
        this.hoursWorked = hoursWorked;
    }

    @Override
    void DisplayDetails() {
        super.DisplayDetails();
        System.out.println("Hourly Rate: $" + hourlyRate);
        System.out.println("Hours Worked: " + hoursWorked);
    }
}

public class EmployeeManagement {
    public static void main(String[] args) {
        FullTimeEmployee fte = new FullTimeEmployee("Hari", 101, 75000);
        PartTimeEmployee pte = new PartTimeEmployee("Om", 102, 20, 120);

        System.out.println("Full Time Employee Details:");
        fte.DisplayDetails();

        System.out.println("\nPart Time Employee Details:");
        pte.DisplayDetails();
    }
}
