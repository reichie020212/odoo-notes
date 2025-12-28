## Reservation Methods

Reservation Methods - decide which orders get available stock first

Removal Strategies - Determine which stock units are used to fulfill an order (e.g, FIFO, by location)

Three types of Reservation Methods:
- At Confirmation
- Manually
- Before Scheduled Date

`At Confirmation` - This method reserves products automatically when a SO is confired as long as stock is available

To change reservation method, go to Configuration -> Operation Type, Open form, set Reservation method field

Go to SO, confirm it, then hover or check the forecast icon in the order lines

You can also check this on the stock picking after clicking the `Delivery` smart button, then check the quantity column if its the same with `demand` column or check the `product availability` field

on `Manual Reservation`, you have to manually check the availability by going to stock picking and click the `check availability` button

on `Before Scheduled Date`, Odoo waits for a set amount of days before scheduled delivery date to start automatically reserving product

If before Scheduled  date is selected, two new fields will appear to set the amonunt of days to reserve

stock pickings that is not yet reserved is marked as `waiting`

you can `star` a stock picking in form and list view
