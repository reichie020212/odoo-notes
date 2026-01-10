## Engineer to Order (ETO)

ETO and MTO is almost the same, the key difference is the design.

With MTO, the design is already locked in. it's a special product that we don't keep in stock. 
So once a customer places an order, all we have to do it follow the blueprint and build it spec.

With ETO, there is no blueprint yet, the design is build and engineered from scratch, customer is fully involve with the design process.

Fosters trust, collaboration, and strong partnerships

ETO projects are more collaborative and more detailed.

in an ETO workflow, nothing gets made until the order is placed and the design is finalized.

ONly once we fully understand the customer's requirement, then we can move forward with engineering, production, and delivery.

Enable `Analytic Accounting` by going to Accounting -> Configuration -> Settings -> Find Analytic Accounting.
This feature is crucial because it lets us keep all project related costs like components and labor costs all organized in one place.

Go to Employees -> Employees form -> add amount to `Hourly Cost` field.

<img width="1889" height="676" alt="image" src="https://github.com/user-attachments/assets/917685ef-600e-46a2-9598-e01fc9a5dfcb" />

To track work hours, go to Projects -> Configuration -> Settings -> Enable `Timesheets` 

To set the invoice policy to delivered, go to Sales Settings -> Invoicing -> Invoice what is delivered

<img width="1907" height="767" alt="image" src="https://github.com/user-attachments/assets/70b51694-eb16-495c-8d5d-1c71dbbb0138" />

To create a project template that we can reuse everytime, Go to Projects -> Create a project -> Create stages and tasks inside project.

Create a product named `ETO Design Service`. This product's type must be Service. Check screenshot for other preferred value per fields.
This product is what we'll use to charge customers for designing their custom orders. set Sales Price unit to `per Hours`

<img width="1914" height="832" alt="image" src="https://github.com/user-attachments/assets/d10bbdc6-98dc-4e85-99df-af970cc6a9c5" />

if `Project` is selected on `Create on Order` field, a new project is automatically created every time that this product is ordered 

its recommended to link it to a specific `Project Template` so every order kicks off with a fresh ETO project with the structure and stages that were ready to use

Place an order for custom ETO project in Sales app.

Upon confirming the quotation and becoming an SO, Analytic account will be automatically created. You can see this by showing the column `Analytic Distribution` in Order Lines Tab.

Also, upon confirming the quotation, new smart buttons will show that is based on the projects created.

<img width="1906" height="711" alt="image" src="https://github.com/user-attachments/assets/78937554-38ab-4259-a615-b80bc75a7654" />

Add more tasks, assignees, and other related fields if necessary.

Add timesheets per tasks then move the task's state to done.

Create or update work center based on your project by going to in Manufacture -> Configuration -> Work Centers.

Make sure cost per hour field in work center have an amount. This will be used to calculate the total cost of manufacturing

Create a new BOM for the project. Add the SO number to the `Reference` field. Go to `Miscellaneous` tab then select the Project automatically created by the SO in the `Project` field.
Add product to the components. make sure that each product have a set `Cost`.
Add Operations to the `Operations` tab.

Create an MO and use BOM then confirm MO.
Click `Produce All` once done manufacturing the product.

Go back to Sales Order. Time to charge the customer for the product that we just manufactured.
Add the product manufactured to the `Order lines` tab. then add a unit price to the product. then save.

A new `Delivery` smart button will appear. click that to redirect to the stock.picking then validate it. once validated, it means the product has been delivered to the customer

We need to invoice the customer now so go back to the SO, then click `Create Invoice` header button.

In the invoice form view, you may notice that the quantity of the product service is automatically updated, this is based on the total hours worked on to produce the product.

TO review the project details, go to Projects app -> click the 3-dotted menu button of the project card -> select Dashboard.
Here, you can see all of the costs associated with the project from the revenues, costs, and overall profit

<img width="1902" height="887" alt="image" src="https://github.com/user-attachments/assets/84f8ca8f-4456-45f8-8b96-210e7deaddbd" />



