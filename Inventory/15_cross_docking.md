## Cross-docking

Cross-docking is instead of storing product to stock from the input truck, it will directly go to output truck then go to customer

Enable `Storage Locations` and `Multi-step routes`

Go to Warehouse menu, make sure the shipments is using either two or three steps

Go to `Routes` menu to create a cross-dock route

In rules, Add the following
- Table Column Names: Action, Source location, Destination Location
- Column Values: Pull from, WH/Input, WH/Output
- Column Values: Pull from, WH/Output, Partners/Customer

In the products form, go to inventory tab to check the cross-dock route

make sure that the product have atleast one vendor on the purchase tab

Create an SO and confirm order, this will automatically create a PO

confirm and receive the PO

go back to SO then go to its stock picking list

validate the first stock picking

validate the other stock picking once they are done

There is a cross-dock in Operations type
