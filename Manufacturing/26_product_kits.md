## Product Kits

Product kit is a single, sellable item composed of multiple, unassembled sub-products, managed through a BoM

An example is a product named `Computer Essentials Kit` and it has below components or products
- Computer Case
- Cooling Fan
- Power Supply

It means that whenever a customer buys `Computer Essentials Kit`, they will receive the components or products

To create a Kit, Go to Manufacturing -> Products -> Bill of Materials -> Create one -> BoM Type field should be `Kit` -> Add components.

Create an SO and add in the order lines table the product kit then confirm.

Once confirmed, you will notice in the order line that only the product kit is showing but if you go to the delivery page by clicking the `Delivery` smart button, we can see here all of the products of the product kit

<img width="2338" height="1050" alt="image" src="https://github.com/user-attachments/assets/1f6a681d-2144-4fb9-bcab-fe2d36247053" />

Product Kit can also be used as a component in another BoM.
