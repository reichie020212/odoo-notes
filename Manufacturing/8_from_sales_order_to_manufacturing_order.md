## From Sales Order to Manufacturing Order

Process 1: MTO Route

Go to Inventory -> Configuration -> Routes

Filter the list view to `Archived`

`Unarchived` the `Replenish on Order (MTO)`

Go to Products form.

`Can be sold` field must be check.

`Replenish on Order (MTO)` and `Manufacture` routes must also be checked in the `Inventory` tab

Create a BoM for the product

Create an SO and add the product in the order lines then confirm it

once confirmed, an MO will automatically created and you can access it via the `Manufacturing` smart button. click it.

manufacture the product or click `Product All` to product the product

Go back to the SO and go to its stock.picking by clicking the `Delivery` smart button then `Validate` the stock.picking.

NOTE: the `MTO` route always creates an MO for a product when it is included in a SO. This is the case even when there's enough stock on hand to fulfill the SO

Process 2: Reordering rule

Go to product form -> Inventory tab -> untick `MTO` then tick the `Manufacture`

Go to its reordering rule by clicking the `Reordering Rules` smart button

Create a new Reordering rule and configure the following fields
- Route - Manufacture
- Min Quantity - 0
- Max Quantity - 0
- To Order - 1

This is called the `001` reordering rule 

create a new quotation and add the product to order lines then confirm it to became an SO

This time, no `Manufacturing` smart button is visible but an MO is already created automatically since in this case, the MO is not linked to the SO anymore

This also means that the product created by the MO will not be reserved for this SO and can be used for any SOs if necessary 

Go to the Manufacturing Order menu and open the most recent MO

manufacture the product or click the `Product All` smart button.

Go to the stock.picking of the SO to see if the product is available.

if available and already shipped, click `Validate`
