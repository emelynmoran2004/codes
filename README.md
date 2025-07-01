 BudgetCalcular {
    double SALARY = 3000.0;
double SAVING_PERCENT = 0.20;
double RENT_PERCENT = 0.30;
double GROCERIES_PERCENT = 0.15;
double ENTERTAINMENT_PERCENT = 0.10;
double savedAmount = SALARY * SAVING_PERCENT;
double rentAmount = SALARY * RENT_PERCENT;
double groceriesAmount = SALARY * GROCERIES_PERCENT;
double entertainmentAmount = SALARY * ENTERTAINMENT_PERCENT;

double totalExpenses = rentAmount + groceriesAmount + entertainmentAmount;
double remainingBalance = SALARY - totalExpenses;

System.out.println("Budget Summary");
System.out.println("Monthly salary: $" + SALARY);
System.out.println("Amount Saved: $" + savedAmount);
System.out.println("Rent: $" + rentAmount);
System.out.println("Groceries: $" + groceriesAmount);
System.out.println("Entertainment: $" + entertainmentAmount);
System.out.println("Remaining Balance: $" + remainingBalance);