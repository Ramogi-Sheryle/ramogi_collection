# Ramogi Collection

A mobile-friendly sales and inventory management prototype for Ramogi Collection.

## Prototype features

- Point of sale with product search and cart
- Inventory management and low-stock indicators
- Stock deductions after completed sales
- M-Pesa, cash, and card/POS payment recording (payment selection only; no live M-Pesa API connection)
- Printable receipts and recent sales
- Barcode scanning where the browser supports the Barcode Detection API
- CSV sales export and JSON backup/restore

## Current storage limitation

The original standalone prototype stores records in the browser on the current device using local storage. It does not yet provide user accounts, shared cloud data, or automatic syncing between devices.

## Next development milestone

Add secure authentication and a cloud database so products, stock, and sales can be accessed safely across devices. M-Pesa STK Push integration should be added only after the business payment account and Daraja credentials are configured.
