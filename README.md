Download Link: https://assignmentchef.com/product/solved-solvedchapter-8-polymorphism
<br>
Exercise 1: Explain the difference between the terms late binding and polymorphism. 2 3 4 Exercise 5: Consider the following code, which is identical to the code discussed earlier in the opening of the subsection, “Downcasting and Upcasting,” except that we added the type cast shown in color: Sale saleVariable; DiscountSale discountVariable = new DiscountSale(“paint”, 15, 10); saleVariable = (Sale)discountVariable; System.out.println(saleVariable.toString()); We saw that without the type cast, the definition of the toString method used is the one given in the definition of the class DiscountSale. With this added type cast, will the definition of the toString method used still be the one given in DiscountSale or will it be the one given in the definition of Sale? 6 7 8 9 10 11 12 13 14 Exercise 15: The abstract class Employee given in Display 8.7 has a constructor (in fact, it has more than one, although only one is shown in Display 8.7). But using a constructor to create an instance of an abstract class, as in the following, is illegal: Employee joe = new Employee(); //Illegal So why bother to have any constructors in an abstract class? Aren’t they useless?