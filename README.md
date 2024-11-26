This mini-project is a simple Inventory Management System built in C++. It manages a linked list of inventory items, where each item has attributes such as item_name, item_id, quantity, and price_per_item.

Features:
1.	Add New Inventory Item:
	Allows the user to add new items to the inventory, ensuring each item has a unique item_id.
2.	Sell Inventory Item:
	Users can "sell" an item by entering the item's ID and quantity, which then updates the inventory. If an item's quantity reaches zero, it is automatically removed from the list.
3.	Purchase Inventory Item from Supplier:
	Users can restock an item by specifying the item ID and quantity. The system updates the inventory accordingly, verifying if the item exists.
4.	Check Stock:
	Displays a list of all available inventory items, showing each item’s ID, name, and current quantity.
5.	Exit:
 Allows the user to exit the program gracefully.

Implementation:

This project uses a linked list data structure to dynamically manage inventory items. Each item in the inventory is a node in the list, represented by a struct inventry_item. The program also includes basic error handling and a menu-driven interface.

Functions:

•	delitem(): Deletes an item from inventory if its quantity reaches zero.

•	Menu-driven system within main() function, allowing users to interact with the inventory management system.

Concepts Covered:

•	C++ structs and pointers

•	Linked list implementation

•	Dynamic memory allocation and deallocation

•	Menu-driven console interface

This mini-project serves as a basic demonstration of inventory management and linked list operations in C++.
