GRASP & Polymorphism
GRASP (General Responsibility Assignment Software Patterns) is a set of design principles that help developers assign responsibilities efficiently in object-oriented systems. Polymorphism, one of these principles, allows different classes to be treated as the same type, enabling flexibility and scalability in software design.

Polymorphism in Action: A Smart Payment System
Imagine an online shopping platform where customers can pay using different methods—Credit Card, PayPal, or Bitcoin. Instead of handling each payment type separately, we use Polymorphism to define a common interface called Payment. Then, different classes (CreditCardPayment, PayPalPayment) implement this interface, each processing the payment in its own way.

This means our system can easily add new payment methods in the future without modifying existing code, making it scalable, flexible, and future-proof—a perfect example of Polymorphism in software design! 🚀

📌 What This Project is About
This project demonstrates the GRASP principle of Polymorphism by implementing a Smart Payment System. Instead of writing separate code for each payment method, we use a common interface (Payment) and let different payment types (CreditCardPayment, PayPalPayment, and BitcoinPayment) define their own behavior. This makes our system flexible, scalable, and easy to maintain.

🔧 How to Use It
Clone or Copy the Code: Copy the Java code and run it in any Java IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code with Java support).
Choose a Payment Method: Create an instance of CreditCardPayment, PayPalPayment, or BitcoinPayment.
Process Payment: Call the processPayment() method and pass the selected payment method along with the amount.
See the Output: The system will execute the appropriate payment method dynamically based on Polymorphism.
