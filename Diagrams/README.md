# Intuit Invoice System UML Overview
## Structural Diagrams
  - Class Diagram
  ![image-link](./images/class_diagram.png)
## Behavioral Diagrams
  - Use Case Diagram
    
  This use case diagram represents the interactions between the users (Customer and Business Owner), and the Invoice Management System, as facilitated through an interface. The diagram captures the core functionalities provided by the system to enable effective and efficient management of invoices and related activities.

1. Business Owner: The business owner is responsible for the creation and management of invoices. They can perform several critical actions such as:
    - Create Invoice: Draft a new invoice to be sent to customers.
    - View Customer Payment History: Review past payments made by a customer to keep track of financial engagements.
    - Deposit Payments: Record the deposit of payments received from customers.
    - Generate Reports: Produce various reports for business analysis and record-keeping.
    - Manage Customer Account Details: Maintain and update customer account information.
    - Receive Bank Details: Obtain bank information for transaction purposes.

2. Customer: The customer is the recipient of the invoice who interacts with the system to complete payment or communicate discrepancies.
    - Validate Details: Confirm the accuracy of personal details before proceeding with payments.
    - Make Payment: Submit payment for an invoice received.
    - Decline Invoice: This new feature enables the customer to reject an invoice if the details appear incorrect, prompting a review or correction from the business owner.

3. System Interface: Represented as QB, the interface serves as the medium through which both actors interact with the system functionalities.
    - Send Invoice: The system sends the invoice to the customer and, as a new improvement, notifies the business owner of successful transmission.
    - Send Reminder Payment: Generates reminders for overdue payments, enhancing the payment collection process.
    - Update the Payment Status: Reflects the current status of the payment after customer actions.
    - Update Invoice: Allows for modifications and updates to be made to the invoice details.

Incorporating the listed improvements, the use case diagram now better reflects the comprehensive flow of actions and interactions within the Invoice Management System. The addition of an acknowledgment to the business owner regarding the successful delivery of the invoice ensures clarity in communication, while the option for the customer to decline the invoice adds a layer of verification and trust to the transaction process. These enhancements aim to streamline operations, reduce errors, and improve the overall satisfaction of both the business owner and the customers.
  - Activity Diagram
  - Sequence Diagram
  - Communication Diagram

