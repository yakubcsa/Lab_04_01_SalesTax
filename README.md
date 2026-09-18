//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
void main() {
    //pretend that we got this from the user as an input
    double purchasePrice = 25.25;
    final double SALES_TAX_RATE = .05;
    double saleTax = 0;
    double total = 0;

    saleTax = purchasePrice * SALES_TAX_RATE;
    total = saleTax + purchasePrice;

    //java 1.8 system.out.println

    IO.println("The sales tax on " + purchasePrice + " is " + saleTax);
    IO.println("The total cost is " + total);

    }
