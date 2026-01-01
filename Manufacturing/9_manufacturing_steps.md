## Manufacturing steps

in one-step manufacturing, we only need to worry on the MO itself 

in two-step manufacturing, we need to pick the components and transfer them to the production location before processing the MO

in three-step manufacturing, this requires transferring the finished product into the storage location 

one-step manufacturing is ideal for small scale manufacturing operations companies the don't need to worry about an excessive amount of components or products might not need to worry too much about tracking those type of transfers

if trackicking this operation is absolute critical, two or three step manufacturing is suggested.

to enable two or three step, go to Inventory app -> Configuration -> Settings -> Enable `Multi-Step Routes`

GO to Configuration -> Warehouse form -> select the two or three step Manufacture. For now pick three step manufacturing

create an MO then Confirm it.

check the chatter to see that the `MO Readiness` is not `Ready` instead it is in `Waiting Another Operation`

This means that it is waiting for the process of transferring the components to the production location

to do this, click the `Transfers` smart button then validate the stock.picking

go back to MO by clicking the `Manufacturing` smart button

`MO Readiness` is now `Ready`

produce the MO

once the product is finished, process the transfer by clicking again the `Transfer` smart button then select the 2nd stock.picking then validate it


