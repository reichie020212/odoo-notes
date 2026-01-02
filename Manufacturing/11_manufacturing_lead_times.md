## Manufacturing Lead Times

Lead Time - the number of calendar days it takes to complete a process from start to finish
- Customer Lead Time - days pass between when a product is ordered and when it ships out of the warehouse
- Customer Lead Time == Delivery Lead Time
- Manufacturing Lead Time - days it take to actually build the product

set the customer lead time of a product in Product Form -> Inventory Tab -> Customer Lead Time field

to set the manufacture lead time, Go to BoM form of the product -> Miscellaneous tab -> Manuf. Lead Time field

There's also a field called `Days to prepare Manufacturing Order`. This field represents the number of days needed to gather components or make subassemblies before production can start.

You can set `Days to prepare Manufacturing Order` manually or you can click `Compute` button beside it to automatically compute.

`Compute` button is based on the longest `Delivery Lead Time` in the `Purchase` tab of all of the products in the BoM.

Create an SO of a 0 quantity product and you will see that the Forecast is in color `Red`

<img width="1592" height="576" alt="image" src="https://github.com/user-attachments/assets/95b4afb9-3061-46f8-a812-2255ce61b63e" />

click the `View Forecast`. Then click the `Manufacturing Forecast` button.

<img width="1600" height="585" alt="image" src="https://github.com/user-attachments/assets/d760a007-d905-4c61-be4a-193bdcc9811b" />

Here you can see the next availability date of the product based on the Lead Times set.

<img width="1608" height="607" alt="image" src="https://github.com/user-attachments/assets/9ab2595e-a0a1-4a1a-8376-abe57ac52de4" />
<img width="1609" height="590" alt="image" src="https://github.com/user-attachments/assets/ce48796b-4148-4d96-9d38-95962cea86f1" />


