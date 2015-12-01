class Budget
{
  private double amount;
  public Budget(double amount)
  {
    this.amount = amount;
  }
  public String toString()
  {
    return "Budget this month: $" + amount;
  }
}
