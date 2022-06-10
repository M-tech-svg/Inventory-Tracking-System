Inventory Tracking System:

 - Inventory tracking system is used to manage inventory and handling supplies from order given to selling shop.
 - It has 2 users :
    
	- Retailer (That request for supplies)
	- Supplier (Supplies items from quantity)
	
 - The items are supplied from suppliers, retailer request for quantity with requested price.
 - The supplier when receives request from retailer it checks the quantity available.
 - The retailer checks the quantity sent comparing with items they requested.
 - After confirming the availability supplier sends the items
 - If it is confirmed, the retailer adds item to inventory.
 - If it does not matches the items, the request is denied.  
 - It is web based system designed using PHP and built in SOAP server.
 - The database is based on PHP MyAdmin 5.2.0
 - The tables that are :
  - orders
  - retailer
  - supplier
  - supplier_inventory
  - users
 - It creates order request for supplier and updates the stock from trigger in the database where reuqest sent is received 
   and changes the inventory items.
 
 