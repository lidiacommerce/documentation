# Order Management

#### 1️⃣ Order Creation and Listing

Orders created by customers are first generated in the [**Marketplace Console**](../../../lidia-console/user-guide/). After payment is approved, the order is assigned to the relevant seller and reflected in the **Merchant Console → Orders** page.

On this screen, the seller can view all paid orders in a list format with the following information:\
order ID, reference number, delivery code, customer information, total amount, order date, delivery status.

Newly received orders appear on this screen with the New status.

#### 2️⃣ Order Approval or Rejection

Approval or rejection of a newly received order is performed through the order detail screen.

* **When an order is approved, the products included in the order can be cancelled individually.**
* **When an order is rejected, all products in the order are rejected together**.

During the rejection process, one of the following rejection reasons can be selected -insufficient stock, incorrect product, other- and an additional explanation can be entered if desired. These actions can be performed from both the Marketplace Console and the Merchant Console.

#### 3️⃣ Order Preparation and Delivery Transition

Approved orders move to the **Ready** status and become eligible for shipment.

If the seller offers products using one of the system’s integrated shipping providers, a delivery code is automatically generated for the order by the system. From this point forward, the delivery flow progresses through the following statuses:\
To Be Shipped → To Be Delivered.

#### 4️⃣ Invoice Upload Requirement

From the moment the delivery process begins, the seller is responsible for uploading an invoice for each processed delivery.

If there is a missing or unuploaded invoice, an Missing Invoice label is displayed under the order status on the Orders page, and the following alert message appears:\
“You have X pending invoice upload requests!”



* #### **Order Detail Page**&#x20;

The order detail page is structured similarly to the order screen in the Marketplace Console and consists of three main sections.

* **Summary Section**\
  The summary section allows quick access to the core order information. This area includes:\
  customer first name, last name, email address, phone number, order number, order date and time, unit prices of ordered products, shipping fee, tax amount, total order amount, seller’s net payout, order status.\
  \
  On the right side of the screen, the customer information panel displays:\
  customer name, delivery details, contact number, delivery address, individual billing address.

***

* **Order Financial Breakdown**\
  Located below the summary section, the Order Financial Breakdown presents the financial structure of the order and consists of two main parts: the Revenue Table and the Cost Table.\
  \
  **Revenue Table:**\
  **product amount** (total sales value of products),\
  **shipping fee** (shipping cost charged to the customer),\
  **total revenue** (sum of product and shipping amounts).\
  \
  **Cost Table – Internal Costs:**
* **platform cost** (platform service fee)
*  **payment provider cost** (payment processing fee)
*  **shipping cost** (delivery cost)
*  **seller share** (amount remaining to the seller after costs)
*  **withholding tax** (statutory tax deduction)
*  **return amount** (cost related to returned items)
* **cancellation amount** (cost related to cancelled orders)
* **marketplace coupon cost**
* **seller coupon cost**
* **marketplace campaign cost**
* **seller campaign cost**
* **loyalty point cost**<br>

**Cost Table – External Costs:**

* **external coupon cost**
* **external loyalty point cost**
* **total cost** (sum of all internal and external costs)

***

* **Deliveries Section**\
  The Deliveries section displays detailed delivery content related to the order. This area includes:\
  product name, mini product image, seller item code, barcode number, delivery quantity, product unit price, discount amount (if any), total delivery amount.\
  \
  Once the delivery process begins, the following steps are displayed:\
  delivery code created (with date and time), to be shipped, to be delivered.

Below these steps, the following action buttons are available:

* **View Delivery:** Redirects the user to the relevant delivery on the Order Management → [Delivery Management](delivery-management.md) page, allowing the entire delivery process to be managed from a single screen.
* **View Transport Document:** Displays the official transport document provided by the shipping company.
* **View Transport Document as Sticker:** Displays the transport document in a label format suitable for attaching to the package.

***



* [x] Using the Upload Invoice button, the seller enters the invoice number, invoice party (buyer/platform), invoice date, invoice type (individual/corporate) and uploads the invoice file in PDF format. Uploaded invoices are listed and managed under Invoice Center → Invoices.
* [x] All orders listed on the Orders page can be exported in Excel format using the Export Data button. This export can be used for reporting, accounting, and archiving purposes.

