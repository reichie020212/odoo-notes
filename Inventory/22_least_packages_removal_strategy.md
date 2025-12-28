## Least Packages Removal Strategy

Scenario: there's two chocolate packages thent the first package contains 10 pcs while the 2nd package contains 30 pcs

In `FIFO`, if someone ordered 15 pcs, it will open first package to get 10 pcs then open 2nd package to get 5 pcs.

In `Least Packages`, it will just open the 2nd package to get 15 pcs.

Enable `packages`, `storage location`, `multi-step routes`

To check the product's packages, go to operations -> physical inventory, then check the column `package`

go to location to set the removal strategy to `least packages`

in the SO stock picking hamburder menu, check if the removal strategy takes place.

Set a destination package
