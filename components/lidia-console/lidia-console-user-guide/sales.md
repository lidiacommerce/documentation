# Sales

The Sales section is the central area where all orders that have taken place on the marketplace are tracked and analyzed end to end. Through this section, it is possible to view in detail which customer made a purchase, from which store, on which date, and for what amount. Order statuses, included products, payment information, and delivery processes can be monitored from this area, enabling both real-time and historical tracking of sales operations.

## **Orders**

The Orders page is located under the Sales module and is the area where all orders created on the platform are listed in detail, filtered, and tracked on an individual order basis. This page enables monitoring each step of the order lifecycle and allows intervention when necessary.

When you enter the Orders page, the summary panel located at the top of the screen displays key metrics that allow you to quickly review the overall situation. In this area, the Number of Orders, Number of Ordered Products, Number of Canceled / Returned Orders, Number of Approved Orders, and Number of Delivered / Completed Orders are shown respectively. The purpose of this summary panel is to enable you to evaluate the general status of order operations at a glance and to facilitate daily operational control.

Below the summary panel, the main table lists all orders in the system. This list consists of the columns Order ID, Reference No, Customer Name (including the customer’s email and phone number information), Total Amount, Tags, Order Date, and Order Status. Thanks to the filtering tools provided on the listing screen, you can analyze your orders in detail and manage your operational workload effectively. With the filtering options, orders can be narrowed down by the selected date range, minimum–maximum order amount, order status, and organizational breakdowns. Order status–based filtering options include pending delivery, new order, order in process, prepared order, invoiced orders, delivered orders, completed orders, expired orders, canceled orders, returned orders, and undeliverable orders. In addition, orders can also be filtered by sellers, dealers, user type (guest or registered user), predefined tags in the system, and orders with invoice requests only.

You can export selected orders or all orders in the list to Excel format using the Export Data button located at the top right of the page and document your order data. This feature provides operational convenience for use cases such as reporting, archiving, and data sharing with different teams.

### **Order Detail**

When you navigate to the detail of any order listed, the order’s date and time information along with the order tags assigned to the order are displayed at the top of the page under the Order Detail heading with the #XXXX ID number. An order may have more than one tag. Order tags are used to differentiate orders from one another, facilitate order tracking, and standardize operational classification. From this screen, you can add new tags to the order or remove existing ones.

**1) Summary Template**

The first template displayed on the order detail screen is the Summary section. This area presents the most critical order information in a single view. Within the summary template, the customer’s full name, email or phone number (displayed based on the method selected by the customer during registration), order date and time, order amount (TRY), order number (copyable), order reference number (copyable), and order status are shown. This template serves as a reference point to verify the core identity details of the order and to quickly initiate operational processes.

**2) Customer Information Template**

Located on the right side of the summary template, the Customer Information template displays detailed information about the customer who placed the order. This area includes the customer’s full name, Guest User / Registered User status, and email/phone details. In the row below, delivery information is shown, including the Contact Number and Delivery Address. Using the Update Delivery Address button, the delivery address can be changed; any update made here applies only to the relevant order.

Following the customer template, the Individual Invoice Address and then the Platform Information section are displayed. The Platform Information section enables monitoring of the customer’s overall behavior on the platform and presents metrics such as Membership Date, Last Order Date, Total Order Amount, Total Order Count, and Total Cancellation/Return Request Count. This area supports operational decision-making by allowing a quick evaluation of the customer’s history.

**3) Notes Section**

Below the customer information template, the Notes section is located. By adding notes to orders, you can record important details related to the order, ensure information continuity within the team, and prevent the loss of critical information. Notes are visible only to users who have access to this page, and multiple notes can be added for the same order. This area is generally used for internal operational notes, exceptional case records, or customer communication notes.

**4) Order Activity Template**

Located below the Notes section, the Order Activity template lists all steps that occur from the moment the customer adds the product to the cart until the order is completed, together with date and time information, in chronological order. This section is critical for verifying the steps experienced during the order process and for performing root cause analysis in case of potential issues.

The listed core steps are displayed under the following headings:

* Entered the order process
* Payment preference selected
* Invoice address selected
* Payment successfully completed
* Order process completed
* Order status updated
* Order shipped
* Order delivered

The steps displayed vary depending on the current status of the order; for example, for orders with a status of new, the process is typically visible up to the “Order process completed” step, whereas for orders with a status of in delivery process, the steps may be displayed up to the “Order shipped” stage.

**5) Order Account Breakdown Template**

The Order Account Breakdown template, located below the summary template, presents the revenue and cost items of the order in an itemized and accounted manner with detailed sub-breakdowns. This area allows you to analyze the financial impact of the order, platform costs, and seller shares in a single consolidated view.

**Revenue Table**

* Product Price
* Installment Difference
* Shipping Fee
* Total Revenue

**Cost Table**

* **Internal Costs**
  * Platform Cost
  * Payment Provider Cost
  * Shipping Cost
  * Seller Share
  * Withholding Tax Deduction
  * Refund Amount
  * Cancellation Amount
  * Marketplace Coupon Cost
  * Seller Coupon Cost
  * Marketplace Campaign Cost
  * Seller Campaign Cost
  * Loyalty Points Cost
* **External Costs**
  * External Coupon Cost
  * External Loyalty Points Cost

At the end of the template, the **Total Cost** information is displayed, completing the comprehensive financial summary of the order.

**6) Order Content Template**

The Order Content template, located below the Order Account Breakdown template, displays the operational progress and delivery stages of the products included in the order. In this area, seller information, product name, quantity, barcode number, and delivery stages of the ordered product(s) are listed. Delivery stages are displayed with different steps depending on the order status.

If the order status is **new**, the delivery stages are displayed as follows:

* New
* To be prepared
* To be shipped
* To be delivered

If the order status is **processing**, the delivery stages progress as follows:

* Processing
* To be prepared
* To be shipped
* To be delivered

Products that move past the new stage and are taken into processing can be removed from the order at this stage using the Cancel Product button.

When the order status is **prepared**, the delivery stages appear as follows:

* Processing
* Prepared
* To be shipped
* To be delivered

For products that move from the to be prepared stage to the prepared stage, the preparation date and time are displayed. In the next stage, to be shipped, the planned shipment date is shown.

If the order status is **in delivery process**, the stages are listed as follows:

* Processing
* Prepared
* Delivery created
* To be delivered

At this stage, delivery type, carrier provider, and delivery code information are displayed. By clicking the View Delivery Process button, you can open the delivery detail screen and access delivery code, shipment tracking number, recipient, and sender information. Using the View in Detail button at the bottom of the page, you are redirected to the [**Logistics**](logistics.md) **> Deliveries** page located in the Console side menu. In addition, at this stage, you can change the delivery status or cancel the delivery using the Intervene Delivery button. All actions performed are logged with your user information; the intervention type may be updating the delivery status or canceling the delivery, and an intervention reason can also be entered.

When the order status is **completed**, along with the information that the products have been delivered, the following details are displayed:

* Delivery type
* Carrier company that performed the delivery
* Order completion duration
* Seller’s average order completion time

Using the Create Request button located under this information, you can select products and enter a return reason to create a return request. If a return is created using a marketplace-contracted carrier, the system provides a return code. In the request creation area, View Seller Performance and Account Breakdown buttons are also available. The account breakdown button displays a detailed, product-based financial summary of the customer’s purchase; this area can be considered a smaller-scale version of the Order Account Breakdown template explained above.

For an order with a created return request, the return reason, the user who made the update, and the update date are displayed. The View Request Details button redirects you to the [**After Sales**](after-sales.md) **> Returns** page in the Console side menu and displays the return details of the relevant order. Additionally, using the Send Return Code to Customer button, the return code of the related delivery can be sent to the customer’s email address.





