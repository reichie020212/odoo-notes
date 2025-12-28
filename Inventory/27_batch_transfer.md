## Batch Transfer

Batch picking is when one pickers select products for multiple orders at once, then sorts them at a designated location

Batch Transfer vs Batch Picking:
- Batch transfer:
  - Groups orders together
  - can be used for picking, internal transfers, or deliveries
- Batch picking
  - one of the three picking methods aavilable in odoo
  - physically gathering items for multiple orders at onces
  - behind the scene, it is handled by `Batch Transfer` operations

Enable `Batch, wave, and cluster transfer` in configuration settings

Go to Warehouse form, then set the Outgoing shipments to two or three step

Go to `Delivery Orders` operation type to set the `Automatic batches` field to true

upon setting it, new fields will show, set them based on your preferences

In the `Pick` card inside the Inventory Overview, click the three-dot menu, then click `Prepare Batch`

add transfers stock pickings then confirm the batch

upon confirming, new tabs will appear

check the `From` column to see where the items can be pick

add responsible person

click the gear icon, then `Batch Transfer` to generate a barcode

go to barcode app and explore the feature

once batch transfer picking validated, go to delivery order card to see the list of batches

check and validate each batch

