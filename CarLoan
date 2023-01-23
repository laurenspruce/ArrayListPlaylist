public class CarLoan {
    //This program allows a user to work out monthly repayments on car loans

    public static void main(String[] args) {
        int carLoan = 10000;
        int loanLength = 3;
        int interestRate = 5;
        int downPayment = 2000;

        //Checking if user is taking out invalid car loan
        if (loanLength<= 0 || interestRate<= 0) {
            System.out.println("Error! You must take out a valid car loan.");
        //Checking if down payment is greater or equal to car loan
        }else if(downPayment>=carLoan) {
            System.out.println("The car can be paid in full.");
        }else {
            int remainingBalance = carLoan - downPayment;
            int months = loanLength * 12;
            int monthlyBalance = remainingBalance / months;
            int interest = (monthlyBalance * interestRate) / 100;
            int monthlyPayment = monthlyBalance + interest;
            System.out.println(monthlyPayment);
        }

    }

}
