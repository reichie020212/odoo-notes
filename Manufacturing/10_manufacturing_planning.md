## Manufacturing Planning

Work Centers Form view have a field `Working Hours`. Click the `right arrow` icon to see its form view.

In this form, you can see the full breakdown of the working hours

Create a new MO then `Confirm` it then click `Plan` 

Go to `Manufacturing Orders` list view then check all or some of the MOs

upon checking, a `Plan` server action button will show. Click it.

by clicking `Plan`, odoo will assigne work centers to each of the MO that you have planned and create a schedule based on the capacity of each work center and the work order duration.

Check the `Start` column, you will notice that the value is changed.

Go to Planning -> Planning by Production. In this menu, you can see how the operations were scheduled and organized by manufacturing order

You can also see the list view by clicking the list view icon

Go to Planning -> Planning by Workcenter. In this menu, you can see the operation by work center.

can also view the calendar view by clicking the calendar icon

If in case you change the schedule in gantt view and the color of graphs changed to red, it means something is wrong in the scheduling.

To fix this, go to list view, removed the groupings, then check the right most, if you see ⓘ, it is just an information, but if you see ◬, it means there is an issue on the scheduling.
Hover to this icon and you will see the `Replan` button. click it to fix the scheduling problem.

<img width="598" height="193" alt="image" src="https://github.com/user-attachments/assets/cae0aacf-e806-42ea-86df-8a2c717b9ecb" />


