## Scrap Orders

set one-step manufacture in Warehouse form

if you want to scrap a product and automatically create a Purchase Order if the product is scrapped, set the Route of the product to `Buy` and there must be atleast one vendor in the `Purchase` tab.

To scrap a component in MO, open a confirmed MO then click the `Scrap` header button. a pop-up window will show.

<img width="1920" height="736" alt="image" src="https://github.com/user-attachments/assets/821de69d-1edd-48f4-a113-9c1c11a95404" />

Select the Product to scrap and set the quantity

Set the `Replenish Quantities` to true to get a new unit once the product is scrapped

Click the `Scrap Products` button.

once done scrapping, MO Status will change back to Waiting, `Purchase` and `Scraps` smart buttons will appear.

Go to PO to confirm, validate, and receive the component

Go back to MO the continue producing the product

Once the MO is done, you can scrap the produced product by clicking again the `Scrap` header button.

In the product dropdown field, you will notice that the only product that can be selected is the produced product

if the `Replenish Quantites` is set to true, a new MO will automatically created.

in two-step or three-step, if you scrap a component, instead of automatically creating a PO or MO, It will create a new stock.picking
