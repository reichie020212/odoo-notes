## Manufacturing Order and Work Order Basics.

Manufacturing Order (MO) - specifies which product needs to be produced including the quantity, required materials, and production timeline. it serves as a key document in the manufacturing process ensuring that the right products are made according to the demand and operational capacity

To create an MO, go to Manufacturing app -> Operations -> Manufacturing Orders -> Click New.

set the product that we will manufacture and the quantity

Bill of Material (BoM) will automatically populated if there's a BoM for the specific product

BoM is a blueprint on how the product should be made including the full list of the required components

when BoM is added, Components tab and Work Orders are also auto populated

Confirm the MO

Component Status will only be on green `Available` if all components or materials are available.

if one-step manufacturing is enabled, this means that MOs will be marked as ready as long as we have enough components in stock

if two-step or three-step manufacturing is enabled, we would need to transfer components to the production location before the MO would be ready to start. `Available` status will be in orange that means `waiting for components`

in Work Order table, `Real Duration` column represents the actual time that it takes to complete a work order.

click the green start button on the right side of a work order record, it will change the status to `in progress` and `real duration` will start counting

You can pause or manually finish the work order

by clicking the `Done` button, the status will change to `Finished`

Once all Work Orders are Done, click the `Produce All` button
