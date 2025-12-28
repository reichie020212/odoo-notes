## Working with Perishable Product

The FEFO (First Expire, First out) strategy

Enable `Lots and Serial Numbers` and `Expiration Date` in Inventory config settings

Enable also the `storage locations` and `multi-step route`

In products, product type should be `goods` while track by should be `lots`

enable `expiration date` then set the expiration dates

go to locations form and select `FEFO` Removal Strategy

On the PO stock picking, when you try to ad Lot or S/N in the hamburger menu, a column for expiration date is now added, set expiration date on each of them

Expiration dates can also be set in Lot or S/N form

in Sales, go to SO stock pickings then on the hamburger menu to see the lot used based on expiration
