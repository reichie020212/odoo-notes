## Import an opening balance

The transition to new software requires
- General Ledger
- Open Receivables and Payables
- Bank balance
- Inventory count

Best practices on importing
- its important to transition using the data from the end of fiscal year or the end of the tax period
- the general ledger must be balance
- the total of accounts receivable on general ledger must equal to sum of your open or unpaid customer invoices minus any unpaid customer credit note
- the total of accounts payable on the general ledger must equal to sum of open or unpaid vendor bills minus any vendor credit notes

Open spreadyseet from your old system

change all receivables accounts to `suspense account`

change all payables accounts to `suspense account`

change bank accounts to `Outstanding Receipts`

All changes must be in a separate tab named `balance odoo`

create a separate tab named `Receivables` for customer invoices. below are the columns and sample value
- Number -> INV/2024/00001
- Partner -> Cars Race Inc.
- Invoice/Bill Date -> 2024/3/6
- Due Date -> 2024/4/5
- Reference -> SO00813
- Invoice lines / Unit Price -> 1,000
- Invoice lines / Label -> Open Invoice
- Invoice lines / Account -> 499000

Create a separate tab named `Payables` for vendor bills. This have the save columns in receivables tab but with different values as shown below
- Number -> Bill/2024/00001
- Reference -> PO00244
- Invoice lines / Label -> Open Bills

Create a new Journal in Configuration -> Journals with below values per field
- Name: Opening Balance
- Type: Misc
- Short Code: OPB

Go to Accounting -> Journal Entries to start importing. click the gear icon then import records

Upload Opening Balance xlsx

select Balance Odoo tabs/sheets, then test it, then import

Check Journal Entries list view to see the new Journal Entry record in draft state. Post them.

Go to Customer -> Invoices to import the receivables sheet

Select all created invoices, then click Actions -> Post entries

Do this also on Vendor Bills for payables sheet

Check general ledger

Copy the debit amount in Outstanding Payments

Go to Dashboard and create a new transaction in bank card

Label must be `Opening balance` and amount is the outstanding payment

Reconcile it by validating

go back to general ledger to see if outstanding payment is balanced
