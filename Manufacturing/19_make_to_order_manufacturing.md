## Make-to-Order Manufacturing (MTO)

Unarchive the MTO Route by going to Inventory -> Configuration -> Routes -> Filter to Archived -> Unarchived MTO

Go to the Product Form and enable the `Replenish on Order (MTO)` route and `Manufacture` in the Inventory tab since `Replenish on Order (MTO)` needs to be paired by either `Buy`, `Manufacture`, or `Resupply`

Create a Quotation then add the product in the order line then confirm

Odoo automatically triggers the Make-to-order replenishment rule, which creates the MO

click `Manufacturing` smart button to redirect to the MO

Produce the product in the MO

Go back to the SO

You can see in the graph icon in the order lines that the there are reserved quantities now

Go to stock.picking by clicking `Deliver` smart button

click the `Validate` to complete the delivery
