## Manufacturing in One Step

When using a one step manufacturing to produce a product, odoo creates a manufacturing order but does not create a transfer order for the movements of components to the production location, nor does it create one to move finished products to the location where they are stored

Product counts still updates based on the amounts used or produced, but there's no need to worry about validating transfers.

To enable one-step manufacturing, Go to Inventory -> Warehouse -> Select a warehouse -> select one-step manufacture

To enable work orders, Go to Manufacturing App -> Configuration -> Settings -> Check `Work Orders` and `Work Order Dependencies`

To process MO in Manufacturing App, Go to Manufacturing App -> Operations -> Manufacturing Orders, select an MO

To process MO in Shop Floor App 

<img width="1590" height="416" alt="image" src="https://github.com/user-attachments/assets/356b4f0e-cbec-422f-9c3d-69a9e4d6ee9b" />

