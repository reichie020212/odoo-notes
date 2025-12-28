enable `landed costs` in configuration settings

go to configuration -> product categories then make sure that the costing method is `average cost`

create a product that represent the landed cost products

product category should have average cost `costing method`

product type should be `service`

cost should be zero

in purchase tab, check `is a landed cost?` field

to use landed cost, do the following
- create a PO
- validate and receive pickings
- note the name of the pickings
- create a bill for the PO
- on the bill, click `add a line` to add the landed cost then set the price
- confirm the bill. Once it is confirmed, `Create Landed Costs` button will show, click that button to create and redirect to landed cost
- select in the transfers field the pickings
- select a split method per landed cost
- validate the landed cost

Check valuation of a product by going to Reporting -> Valuation
