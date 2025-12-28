## Shipping Policy

set Picking Policy in Config Settings

if `ship all products at once` is selected, all quantity of SO must be available and reserve before it can be validated.

The `validate button will only be highlighted if all quantity is available

stock picking is in waiting state unless all quantity is available

if `ship products as soon as available, with back orders`, `validate` button will be highlighted and sotkc picking will be in ready state even if not all quantity is available

when validate button is click, a pop-up will appear to ask if you want to create a backorder

`create a backorder` that will create a new sotkc picking for the remaining product quantity

open the new stock picking to check availability or validate
