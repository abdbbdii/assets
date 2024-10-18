# Automated Menu Ordering System

## Abstract
The Automated Food Ordering System solves issues like long wait times, order mistakes, and reliance on waitstaff by allowing customers to select tables, browse menus, and place orders directly from a table screen. Customer can pay for their food. A manager oversees order fulfillment and overall restaurant operations, while an admin manages the menu, promotional deals, accounts, and branches.

## Introduction
Many restaurants struggle with long wait times, order errors due to human intervention, and high labor costs, which can negatively impact customer satisfaction and overall efficiency. The reliance on waitstaff for taking orders can lead to delays and mistakes, affecting the dining experience.

The Automated Food Ordering System addresses these challenges by providing several advantages. It eliminates the need for waitstaff, allowing customers to sit at a table and start browsing the menu using a screen at their table, where they can place orders directly. Customers can customize their orders, view the status of their orders, and pay for their meals through the system. This automated process reduces wait times, minimizes order errors, and enhances the overall dining experience.

The platform includes various functionalities, such as a comprehensive menu display that allows customers to view food items, read descriptions, and check prices. The system enables customers to customize their orders based on preferences, such as portion sizes or ingredient modifications.

The manager oversees order fulfillment and overall restaurant operations, ensuring smooth kitchen functionality and addressing any service issues. Meanwhile, the admin manages the menu, promotional deals, and discounts, with the ability to update or modify items as necessary to provide customers with the latest offerings. Both the manager and admin must sign up and log in, ensuring secure access and control over their respective areas.

## Problem Statement
Traditional restaurant ordering systems can cause inefficiencies, delays, and errors. Customers experience long waits, incorrect orders, and limited status updates, while manual processing increases mistakes and slows service.

## Objectives
- **Enhanced Customer Experience:**
Allow customers to browse menus, place orders, and pay directly from their table.
- **Streamlined Order Processing:**
Automatically send orders to the counter, reducing wait times and minimizing errors.
- **Order Customization & Tracking:**
Enable customers to customize orders and receive real-time order status updates.
- **Customer Feedback:**
Let customers rate their meals and provide feedback.
- **Waitstaff Assistance:**
Allow customers to call a waiter for assistance when needed.
- **Manager Oversight:**
Provide managers with the ability to oversee and track customer orders at the counter.
- **Admin Control:**
Allow admins to manage food products, deals, accounts, and branches.
- **User-Friendly Interface:**
Offer light and dark mode options for customer comfort.

## Tools and Technologies
The Automated Food Ordering System will be developed using the following tools and technologies:

### Core Development Tools
- **[WinUI3](https://learn.microsoft.com/en-us/windows/apps/winui/winui3/):** For building modern Windows apps.
- **[XAML](https://learn.microsoft.com/en-us/visualstudio/xaml-tools/xaml-overview):** For designing user interfaces.
- **[C#](https://docs.microsoft.com/en-us/dotnet/csharp/):** For backend development.

### Database and Storage
- **[PostgreSQL](https://www.postgresql.org/):** For database storage.
- **[Supabase](https://supabase.io/):** For database hosting and management.
- **[Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/):** For database queries and management.

### Version Control and Collaboration
- **[GitHub](https://github.com/):** For version control and collaboration.
- **[Hackmd](https://hackmd.io/):** For collaborative writing and sharing.
- **[Whatsapp](https://www.whatsapp.com/):** For communication and updates.

### Design and Prototyping
- **[Figma](https://www.figma.com/):** For wireframing and prototyping.
- **[Exalidraw](https://excalidraw.com/):** For creating diagrams and illustrations.

### Development Environments
- **[Visual Studio](https://visualstudio.microsoft.com/):** For software development.
- **[Visual Studio Code](https://code.visualstudio.com/):** For code editing and documentation.

### Documentation
- **[Microsoft Office Suite](https://www.microsoft.com/en-us/microsoft-365/microsoft-office):** For documentation.

### Hardware Tools
- **Tablet or Touch Screen:** For customers to browse menus and place orders.
- **Computer or Laptop:** For managers and admins to oversee operations and manage the system.
- **Internet Connection:** To enable communication between devices and the central system.

## Vision

Our vision is to create a seamless and efficient dining experience for customers and restaurant staff by automating the ordering process, reducing wait times, and enhancing customer satisfaction.

## Scope and Features

The scope of Automated Food Ordering System includes the following features:

### Customer Features

- **Table Selection:** Customers can select a table and start browsing the menu from a screen installed at their table.
- **Menu Browsing:** The system provides a detailed menu display with descriptions and prices, allowing customers to view available items.
- **Order Placement:** Customers can place orders directly through the table screen, eliminating the need for waitstaff.
- **Customization:** Customers can customize their orders, such as modifying ingredients or selecting portion sizes.
- **Order Tracking:** Customers will be able to view real-time updates on their order status.
- **Payment Integration:** Customers can pay for their orders directly from the system using integrated payment options.
- **Feedback Mechanism:** After their meal, customers can rate their experience and provide feedback through the system.
- **Waitstaff Assistance:** If needed, customers can request assistance from waitstaff using the system.

### Manager Features

- **Order Management:** The system provides managers with an interface to oversee and track all customer orders.
- **Operational Monitoring:** Managers can monitor restaurant operations, ensuring smooth kitchen functionality and addressing any order or service-related issues.
- **Fulfillment Supervision:** Managers ensure that orders are fulfilled efficiently and on time.

### Admin Features

- **Menu Management:** Admins can update, modify, or remove menu items, including adding new offerings or deals.
- **Promotional Deals:** Admins can manage promotional deals, discounts, and special offers.
- **Account Management:** Admins oversee user accounts, including managers, waitstaff, and other restaurant employees.
- **Branch Management:** The system allows admins to manage multiple branches from a centralized interface.

### User Interface (UI) Features

- **Light/Dark Mode:** The system offers light and dark mode options for enhanced user comfort.
- **Easy Navigation:** The interface will be designed for simple navigation, ensuring a smooth user experience for both customers and restaurant staff.

## Requirements

### Functional Requirements

#### Actors

There are three actors:
- Admin
- Custumer
- Manager

#### Admin Functional Requirement
- The system shall allow the admin to add, edit, and delete menu items, including descriptions and prices.
- The system shall enable the admin to create, modify, or remove promotional deals and discounts.
- The system shall allow the admin to manage user accounts (customers and managers), including adding, editing, or deleting accounts.
- The system shall enable the admin to manage multiple restaurant branches.
- The system shall allow the admin to assign roles and permissions to managers.

#### Customer Functional Requirement
- The system shall allow customers to view the menu with detailed item descriptions, prices, and availability.
- The system shall enable customers to place and customize their orders directly from a table screen.
- The system shall allow customers to receive real-time updates on the status of their orders.
- The system shall enable customers to pay for their orders through integrated payment options.
- The system shall allow customers to rate their meals and provide feedback.
- The system shall enable customers to call for waiter assistance through the interface.

#### Manager Functional Requirement
- The system shall allow managers to track and oversee all customer orders, ensuring timely fulfillment.
- The system shall allow managers to view the history of customer orders for reporting and analysis purposes.
- The system shall allow managers to monitor and update the availability of menu items and inventory levels.
- The system shall enable managers to recieve notifications for call requests from customers.

### Non-Functional Requirements

#### Usability
- The system shall have an intuitive and user-friendly interface for customers, managers, and admins.
- The system shall provide easy navigation and clear instructions for all users.
- The system shall offer light and dark mode options for user comfort.
- The system shall provide a responsive design for various screen sizes and devices.

#### Reliability
- The system shall be reliable and available during restaurant operating hours.
- The system shall have backup and recovery mechanisms in place to prevent data loss.

#### Performance
- The system shall be responsive and provide real-time updates on order status.
- The system shall process orders quickly and efficiently to minimize wait times.
- The system shall handle multiple user requests simultaneously without performance degradation.

#### Security
- The system shall ensure data privacy and security for all user information.
- The system shall implement user authentication and authorization mechanisms to prevent unauthorized access.
- The system shall encrypt sensitive data to protect user privacy.
- The system shall have secure payment integration for customer transactions.
- The system shall provide role-based access control to restrict user permissions based on roles.

#### Scalability
- The system shall be scalable to accommodate multiple restaurant branches and users.

#### Maintainability
- The system shall be modular and well-structured for easy maintenance and updates.
- The system shall have clear documentation and guidelines for future development and enhancements.
- The system shall have version control and collaboration tools for team development.

---
## TODO Requirements: Non-Functional, Business, Physical, Development, etc.
---

## Wireframes

### Navigation

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Navigation.png)

| Component | Admin | Manager | Customer |
| --- | --- | --- | --- |
| T1 | As an admin, I shall navigate to the previous page | As a manager, I shall navigate to the previous page | As a customer, I shall navigate to the previous page |
| T2 | As an admin, I shall open and close the navigation pane | As a manager, I shall open and close the navigation pane | As a customer, I shall open and close the navigation pane |
| T3 | As an admin, I shall minimize the window | As a manager, I shall minimize the window | As a customer, I shall minimize the window |
| T4 | As an admin, I shall maximize the window | As a manager, I shall maximize the window | As a customer, I shall maximize the window |
| T5 | As an admin, I shall close the window | As a manager, I shall close the window | As a customer, I shall close the window |
| T6 | As an admin, I shall view the contents of a page | As a manager, I shall view the contents of a page | As a customer, I shall view the contents of a page |
| T7 | As an admin, I shall navigate to different pages | As a manager, I shall navigate to different pages | As a customer, I shall navigate to different pages |
| T8 | As an admin, I shall navigate to settings | As a manager, I shall navigate to settings | As a customer, I shall navigate to settings |

### Settings Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Settings.png)

| Component | Admin | Manager | Customer |
| --- | --- |
| T1 | As an admin, I shall use radio buttons to select the theme (Light, Dark, Default). | As a manager, I shall use radio buttons to select the theme (Light, Dark, Default). | As a customer, I shall use radio buttons to select the theme (Light, Dark, Default). |
| T2 | As an admin, I shall have a button to sign out of the application. | As a manager, I shall have a button to sign out of the application. | As a customer, I shall have a button to sign out of the application. |
| T3 | As an admin, I shall have a link to the privacy policy. | As a manager, I shall have a link to the privacy policy. | As a customer, I shall have a link to the privacy policy. |

### Sign In Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Signin.png)

| Component | Admin | Manager |
| --- | --- | --- |
| T1 | As an admin, I shall change the role to manager or customer | As a manager, I shall change the role to admin or customer |
| T2 | As an admin, I shall enter the username | As a manager, I shall enter the username or table ID |
| T3 | As an admin, I shall enter the password | As a manager, I shall enter the password |
| T4 | As an admin, I shall check the "Keep me signed in" box | As a manager, I shall check the "Keep me signed in" box |
| T5 | As an admin, I shall go to learn more | As a manager, I shall go to learn more |
| T6 | As an admin, I shall sign in | As a manager, I shall sign in |

### Home Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-Home.png)

| Component | Customer |
| --- | --- |
| T1 | As a customer, I shall see a Call for Help button. |
| T2 | As a customer, I shall browse a Carousel of Deals by swiping to left or right |
| T3 | As a customer, I shall scroll through Top Trending Items. |
| T4 | As a customer, I shall scroll through Top Rated Items.
| T5 | As a customer, I shall tap to check out a deal. |
| T6 | As a customer, I shall tap to view more details of a deal. |
| T7 | As a customer, I shall tap to add an item to the cart. |
| T8 | As a customer, I shall tap to discover more via links to different pages. |

### Category Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-Category.png)

| Component | Customer |
| --- | --- |
| T1 | As a customer, I shall scroll through the list of items in the subcategory. |

### Cart Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-Cart.png)

| Component | Customer |
| --- | --- |
| T1 | As a customer, I shall see a list of items in my cart that are not yet ordered. |
| T2 | As a customer, I shall view a list of items that are already ordered. |
| T3 | As a customer, I shall access my order history with a list of past orders. |
| T4 | As a customer, I shall have a bin icon to remove an item that has not been ordered yet. |
| T5 | As a customer, I shall have a button to complete my pending order, displaying the total price. |
| T6 | As a customer, I shall have a button to write a review for an ordered item. |

### Add to Cart Dialog

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-AddToCartDialog.png)

| Component | Customer |
| --- | --- |
| T1 | As a customer, I shall select the item size (Small, Medium, Large). |
| T2 | As a customer, I shall adjust the quantity of the item using plus and minus buttons. |
| T3 | As a customer, I shall select toppings using radio buttons (No, Yes). |
| T4 | As a customer, I shall tap to select a card of topping. |
| T5 | As a customer, I shall choose toppings from multiple selectable cards. |
| T6 | As a customer, I shall have a button to add the item to my cart. |
| T7 | As a customer, I shall have a button to cancel and close the dialog. |

### Call for Help Dialog

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-CallForHelpDialog.png)

| Component | Customer |
| --- | --- |
| T1 | As a customer, I shall use cancel button to close the dialog. |

### Sign out Dialog

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-SignoutDialog.png)

| Component | Customer |
| --- | --- | --- |
| T1 | As a customer, I shall call the manager to enter the password. |
| T2 | As a customer, I shall enter the manager's password. |

### Deal Details Dialog

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-DealDetailsDialog.png)

| Component | Customer |
| --- | --- |
| T1 | As a customer, I shall tap to cancel the dialog. |

### Rate Item Dialog

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Customer-RateItemDialog.png)

| Component | Customer |
| --- | --- |
| T1 | As a customer, I shall tap to rate the item. |
| T2 | As a customer, I shall tap to close the dialog. |
| T3 | As a customer, I shall tap to submit the rating. |

### Orders Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Manager-Orders.png)

| Component | Manager |
| --- | --- |
| T1 | As a manager, I shall use this button to select all items. |
| T2 | As a manager, I shall use this button to deselect all items. |
| T3 | As a manager, I shall use this button close the selected items. |
| T4 | As a manager, I shall order the items by any of the columns. |
| T5 | As a manager, I shall search for specific items by any of the columns. |
| T6 | As a manager, I shall use this button clear the search results. |
| T7 | As a manager, I shall use this button to search for items. |
| T8 | As a manager, I shall change the status of the item to "Ready", "Completed", or "In Progress". |
| T9 | As a manager, I shall see a grid view of all items. |
| T10 | As a manager, I shall select an item |

### History Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Manager-History.png)

| Component | Manager |
| --- | --- |
| T1 | As a manager, I shall pick a date to view the history of orders. |
| T2 | As a manager, I shall use this button to clear the selected date. |

### Menu Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Manager-Menu.png)

| Component | Manager |
| --- | --- |
| T1 | As a manager, I shall use this button to mark an item as in-stock |
| T2 | As a manager, I shall use this button to mark an item as out-of-stock |

### Accounts Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Admin-Accounts.png)

| Component | Admin |
| --- | --- |
| T1 | As an admin, I shall use this button to add a new account. |
| T2 | As an admin, I shall use this button to remove an existing account. |
| T3 | As an admin, I shall use this button to update an existing account. |
| T4 | As an admin, I shall use this button to write a custom query. |

### Branches Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Admin-Branches.png)

| Component | Admin |
| --- | --- |
| T1 | As an admin, I shall use this button to add a new branch. |
| T2 | As an admin, I shall use this button to remove an existing branch. |
| T3 | As an admin, I shall use this button to update an existing branch. |

### Tables Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Admin-Tables.png)

| Component | Admin |
| --- | --- |
| T1 | As an admin, I shall use this button to add a new table. |
| T2 | As an admin, I shall use this button to remove an existing table. |
| T3 | As an admin, I shall use this button to update an existing table. |

### Products Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Admin-Products.png)

| Component | Admin |
| --- | --- |
| T1 | As an admin, I shall use this button to add a new product. |
| T2 | As an admin, I shall use this button to remove an existing product. |
| T3 | As an admin, I shall use this button to update an existing product. |

### Deals Page

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Admin-Deals.png)

| Component | Admin |
| --- | --- |
| T1 | As an admin, I shall use this button to add a new deal. |
| T2 | As an admin, I shall use this button to remove an existing deal. |
| T3 | As an admin, I shall use this button to update an existing deal. |
| T4 | As an admin, I shall use this button to edit the deal items. |

### Deal Items Dialog

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Admin-DealItemsDialog.png)

| Component | Admin |
| --- | --- |
| T1 | As an admin, I shall use this button to add a new item to the deal. |
| T2 | As an admin, I shall use this button to remove an existing item from the deal. |
| T3 | As an admin, I shall use this button to close the dialog. |

### Write custom query Dialog

![alt text](https://raw.githubusercontent.com/abdbbdii/assets/refs/heads/main/wireframes/Admin-WriteCustomQueryDialog.png)

| Component | Admin |
| --- | --- |
| T1 | As an admin, I shall write a custom query. |
| T2 | As an admin, I shall use this button to execute the query. |
| T3 | As an admin, I shall use this button to close the dialog. |

## Use Cases

### Use Case 1: Sign In

#### Primary Actors
- Admin
- Manager

#### Goal
To allow the admin, manager, or customer to sign in to the system.

#### Precondition
The user has a valid account and is on the sign-in page.

#### Postcondition
The user is authenticated and granted access to the system based on their role.

#### Trigger
The user enters their credentials and clicks the sign-in button.

#### Basic Flow
1. The system displays the sign-in page with option to select the role (admin, manager, or customer).
2. The user selects the role (admin, manager, or customer).
3. The user enters their username and password.
4. If the user selects the customer role, the system asks for the table ID.
5. The user clicks the sign-in button.
7. If the user is an admin, the system validates the credentials and grants access to the admin interface.
8. If the user is a manager, the system validates the credentials and grants access to the manager interface.
9. If the user is a customer, the system validates the credentials and grants access to the customer interface.

#### Alternative Flow
- If the user clicks "Learn more" link, the system displays additional information about the sign-in process.

#### Exception Flow
- If the user enters invalid credentials, the system displays an error message and prompts the user to try again.

### Use Case 2: Sign Out

#### Primary Actors
- Admin
- Manager
- Customer

#### Goal
To allow the admin, manager, or customer to sign out of the system.

#### Precondition
The user is logged in to the system and is on the settings page.

#### Postcondition
The user is logged out of the system and redirected to the sign-in page.

#### Trigger
The user clicks the sign-out button.

#### Basic Flow
1. The system displays the settings page with the sign-out button.
2. The user clicks the sign-out button.
3. If the user is a customer, the system asks for manager's password to confirm sign out.
4. The user enters the manager's password.
5. The system logs out the user and redirects to the sign-in page.

#### Alternative Flow
- If the user is an admin or manager, the system logs out the user and redirects to the sign-in page.

#### Exception Flow
- If the user cancels the sign-out process, the system remains on the settings page.
- If the user enters an incorrect password, the system displays an error message and prompts the user to try again.

### Use Case 3: Browse Menu

#### Primary Actor
Customer

#### Goal
To allow the customer to browse the restaurant's menu.

#### Precondition
The customer is seated at the table with the system in customer mode.

#### Postcondition
The customer can view the menu items and select items to view details.

#### Trigger
The customer selects one of the main menu categories.

#### Basic Flow
1. The system displays the main menu categories.
2. The customer selects a category to view subcategories.
3. The customer can scroll through the list and view details of each item.
4. The customer can select an item to view its description, price, and rating.

#### Alternative Flow
- If the customer needs assistance, they can call for help using the system.

#### Exception Flow
- If an item is out of stock, the system displays a notification to inform the customer.
- Customers can call for help if they have any issues with the menu.

### Use Case 4: Browse Deals and Promotions

#### Primary Actor
Customer

#### Goal
To allow the customer to view available deals and promotions.

#### Precondition
The customer is seated at the table with the system in customer mode.

#### Postcondition
The customer can view details of available deals and promotions.

#### Trigger
The customer clicks on the "Home" button from the navigation pane.

#### Basic Flow
1. The system displays the home page with a carousel of deals and promotions.
2. The customer can scroll through the carousel to view different deals.
3. The customer can click on a deal to view more details and check out.
4. The customer can view top trending and top-rated items on the home page.
5. The customer can click on "Discover More" to navigate to specific category pages.
6. The customer can add items to the cart directly from the home page.

#### Alternative Flow
- The customer can call for help if they have any issues with the deals or promotions.

#### Exception Flow
None

### Use Case 5: Add Item to Cart

#### Primary Actor
Customer

#### Goal
To allow the customer to add an item to the cart.

#### Precondition
The customer has selected an item from the menu.

#### Postcondition
The item is added to the cart.

#### Trigger
The customer selects the "+" button to open the add to cart dialog.

#### Basic Flow
1. The system displays the add to cart dialog with item details.
2. The customer selects the size and quantity of the item.
3. The customer can choose toppings if available.
4. The customer confirms the order by clicking the "Add to Cart" button.

#### Alternative Flow
- The customer can cancel the order by clicking the "Cancel" button.

#### Exception Flow
- If the customer tries to add an item that is out of stock, the system displays an error message.
- Customers can call for help if they have any issues with their order.

### Use Case 6: Place Order

#### Primary Actor
Customer

#### Goal
To allow the customer to place an order.

#### Precondition
The customer has items in the cart.

#### Postcondition
The order is sent to the manager's interface for processing.

#### Trigger
The customer clicks the "Pay price" button to complete the order.

#### Basic Flow
1. The system displays the cart with all selected items.
2. The customer reviews the order and clicks the "Pay price" button.
3. The system processes the payment and sends the order to the manager.
4. The customer receives a confirmation by placing the order in "Orders" section.
5. The customer can write a review for the ordered items.
6. The customer can view the estimated time for the order to be ready.

#### Alternative Flow
- The customer can remove items from the cart before placing the order.

#### Exception Flow
- If there are no items in the cart, the system displays a message indicating no items to order.
- If the payment fails, the system displays an error message and prompts the customer to try again.
- Customers can call for help if they have any issues with their order.

### Use Case 7: View Order Status

#### Primary Actor
Customer

#### Goal
To allow the customer to view the status of their order.

#### Precondition
The customer has placed an order.

#### Postcondition
The customer can track the progress of their order.

#### Trigger
The customer clicks on the "Orders" section.

#### Basic Flow
1. The system displays the list of current and past orders.
2. The system shows the status of each order (e.g., estimated time, ready, completed).

#### Alternative Flow
None

#### Exception Flow
- If there are no current orders, the system displays a message indicating no orders in progress.
- Customers can call for help if they have any issues with their order.

### Use Case 8: Call for Help

#### Primary Actor
Customer

#### Goal
To allow the customer to call for help from the waitstaff.

#### Precondition
The customer needs assistance.

#### Postcondition
The waitstaff is notified of the customer's request for help.

#### Trigger
The customer clicks on the "Call for Help" button.

#### Basic Flow

1. The system displays the call for help dialog.
2. The customer waits for the waitstaff to respond.

#### Alternative Flow
None

#### Exception Flow
- If the waitstaff does not respond promptly, the customer can try calling again.
- If the issue is urgent, the customer can call the restaurant directly.
- If the customer's issue is resolved, they can cancel the call for help.

### Use Case 9: Provide Feedback

#### Primary Actor
Customer

#### Goal
To allow the customer to provide feedback on their dining experience.

#### Precondition
The manager has changed the order status to "Completed."

#### Postcondition
The feedback is submitted for review.

#### Trigger
The customer clicks on the "Write a Review" button.

#### Basic Flow
1. The system displays the review dialog with option to rate the meal.
2. The customer selects a star rating.

#### Alternative Flow
None

#### Exception Flow
- The customer can cancel the review process if they change their mind.

### Use Case 10: Manage Orders

#### Primary Actor
Manager

#### Goal
To allow the manager to oversee and manage customer orders.

#### Precondition
The manager is logged in to the system.

#### Postcondition
The manager can track order status such as in-progress, ready, completed or, close the order.

#### Trigger
The manager clicks on the "Orders" section from the navigation pane.

#### Basic Flow
1. The system displays the list of current orders.
2. The manager can view the status of each order.
3. The manager can change the status of an order (e.g., from in-progress to ready).
4. The manager can close an order once it is completed.
5. The manager can sort orders by status, time, or table number.
6. The manager can search for specific orders by table number or order number.

#### Alternative Flow
None

#### Exception Flow
None

### Use Case 11: Order History

#### Primary Actor
Manager

#### Goal
To allow the manager to view the history of customer orders.

#### Precondition
The manager is logged in to the system.

#### Postcondition
The manager can access past orders for reporting and analysis.

#### Trigger
The manager clicks on the "History" section from the navigation pane.

#### Basic Flow
1. The system displays the list of past orders.
2. The manager can view details of each order, including items, total price, and customer feedback.
3. The manager can sort orders by date or table number.
4. The manager can search for specific orders by table number, order number, or date.

#### Alternative Flow
None

#### Exception Flow
- If there are no past orders, the system displays a message indicating no history available.

### Use Case 12: Manage Availability of Menu Items

#### Primary Actor
Manager

#### Goal
To allow the manager to monitor and update the availability of menu items.

#### Precondition
The manager is logged in to the system.

#### Postcondition
The manager can update the availability of menu items by marking them as in-stock or out-of-stock.

#### Trigger
The manager clicks on the "Menu" section from the navigation pane.

#### Basic Flow
1. The system displays the list of menu items.
2. The manager can view the availability status of each item.
3. The manager can change the availability status of an item by marking it as in-stock or out-of-stock.
4. The manager can sort items by category.
5. The manager can search for specific items by name or category.

#### Alternative Flow
None

#### Exception Flow
None

### Use Case 13: Manage Menu

#### Primary Actor
Admin

#### Goal
To allow the admin to manage the restaurant's menu.

#### Precondition
The admin is logged in to the system.

#### Postcondition
The admin can add, edit, or delete menu items.

#### Trigger
The admin clicks on the "Products" section from the navigation pane.

#### Basic Flow
1. The system displays the list of menu items.
2. The admin can add a new item to the menu.
3. The admin can edit the details of an existing item.
4. The admin can delete an item from the menu.
5. The admin can sort items by category or price.
6. The admin can search for specific items by name or category.

#### Alternative Flow
None

#### Exception Flow
- If the admin tries to update or delete an item that is associated with an active order, the system displays a warning message.
- If the admin tries to delete an item that is part of a promotional deal, the system displays a warning message.
- If the admin tries to add an item that already exists in the menu, the system displays an error message.

### Use Case 14: Manage Promotional Deals

#### Primary Actor
Admin

#### Goal
To allow the admin to manage promotional deals and discounts.

#### Precondition
The admin is logged in to the system.

#### Postcondition
The admin can create, edit, or delete promotional deals.

#### Trigger
The admin clicks on the "Deals" section from the navigation pane.

#### Basic Flow
1. The system displays the list of current deals and promotions.
2. The admin can create a new deal by specifying the details.
3. The admin can edit the details of an existing deal.
4. The admin can delete a deal from the list.
5. The admin can sort deals by category or discount percentage.
6. The admin can search for specific deals by name or category.

#### Alternative Flow
None

#### Exception Flow
- If the admin tries to delete a deal that is associated with an active order, the system displays a warning message.
- If the admin tries to create a deal with the same name as an existing deal, the system displays an error message.

### Use Case 15: Manage User Accounts

#### Primary Actor
Admin

#### Goal
To allow the admin to manage user accounts.

#### Precondition
The admin is logged in to the system.

#### Postcondition
The admin can add, edit, or delete user accounts.

#### Trigger
The admin clicks on the "Accounts" section from the navigation pane.

#### Basic Flow
1. The system displays the list of user accounts (admins, managers).
2. The admin can add a new user account by specifying the details such as name, role, and password.
3. If the admin is adding a manager, the system asks for the branch assignment.
4. The admin can edit the details of an existing user account.
5. The admin can delete a user account from the list.
6. The admin can sort accounts by role or name.
7. The admin can search for specific accounts by name or role.

#### Alternative Flow
None

#### Exception Flow
- If the admin tries to delete an account that is associated with an branch, the system displays a warning message.
- If the admin tries to create an account with the same username as an existing account, the system displays an error message.

### Use Case 16: Manage Branches

#### Primary Actor
Admin

#### Goal
To allow the admin to manage multiple restaurant branches.

#### Precondition
The admin is logged in to the system.

#### Postcondition
The admin can add, edit, or delete branch information.

#### Trigger
The admin clicks on the "Branches" section from the navigation pane.

#### Basic Flow
1. The system displays the list of branches.
1. The admin can add a new branch by specifying the details such as branch name, address, and contact information.
1. The admin can edit the details of an existing branch.
1. The admin can delete a branch from the list.
1. The admin can sort branches by name or location.
1. The admin can search for specific branches by name or location.

#### Alternative Flow
None

#### Exception Flow
- If the admin tries to delete a branch that is associated with active orders or user accounts, the system displays a warning message.
- If the admin tries to add a branch with the same name or address as an existing branch, the system displays an error message.The admin is logged in to the system.

### Use Case 17: Manage Table Assignments

#### Primary Actor
Admin

#### Goal
To allow the admin to manage table assignments.

#### Precondition
The admin is logged in to the system.

#### Postcondition
The admin can assign tables to specific branches.

#### Trigger
The admin clicks on the "Tables" section from the navigation pane.

#### Basic Flow
1. The system displays the list of tables and their current assignments.
2. The admin can assign a table to a specific branch.
3. The admin can reassign a table to a different branch.
4. The admin can remove a table assignment.
5. The admin can sort tables by branch or table number.
6. The admin can search for specific tables by number or branch.

#### Alternative Flow
None

#### Exception Flow
- If the admin tries to assign a table that is already assigned, the system displays a warning message.
- If the admin tries to remove a table assignment that is associated with active orders, the system displays a warning message.
- If the admin tries to assign a table to a branch that does not exist, the system displays an error message.

### Use Case 18: Change Theme

#### Primary Actors
- Admin
- Manager
- Customer

#### Goal
To allow users to change the theme of the application.

#### Precondition
The user is logged in to the system.

#### Postcondition
The user's theme preference is updated.

#### Trigger
The user clicks on the "Settings" section from the navigation pane.

#### Basic Flow
1. The system displays the settings page with the theme options.
2. The user can select the desired theme (e.g., light, dark, default).

#### Alternative Flow
- Managers and admins can change the theme for the entire system.

#### Exception Flow
None

### Use Case 19: View Privacy Policy

#### Primary Actors
- Admin
- Manager
- Customer

#### Goal
To allow users to view the privacy policy of the application.

#### Precondition
The user is logged in to the system.

#### Postcondition
The user can access the privacy policy.

#### Trigger
The user clicks on the "Settings" section from the navigation pane.

#### Basic Flow
1. The system displays the settings page with a link to the privacy policy.
2. The user clicks on the privacy policy link to view the policy.
3. The system displays the privacy policy in a default browser.

#### Alternative Flow
None

#### Exception Flow
None

## TODO User Stories
## TODO Story Boards
## TODO Proposed Methodology/System
## TODO Related Work
## TODO Team Members Individual Tasks
## TODO Timeline/Gantt chart
## TODO Data Gathering Approach
## TODO References