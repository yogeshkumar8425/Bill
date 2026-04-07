# AWANSHI ENTERPRISES Invoice Software

This is a browser-based billing app for creating both bills and proforma invoices in a standalone starter version.

## Features

- Dashboard with totals and recent documents
- Item Store for saving products with stock, HSN code, and default rate
- Bill and proforma invoice form with separate auto-numbering, GST, discount, notes, and item lines
- Live document preview
- Browser database using `IndexedDB`
- Full backup export and import in JSON format
- Status change, preview, delete, and print support
- Login screen with password reset and OTP demo flow
- Item-wise sell, purchase, and stock summary

## How to Run

1. Open `index.html` in your web browser.
2. Add products in the `Item Store` tab to save stock, HSN code, and rate.
3. Create bills or proforma invoices from the `New Document` tab.
4. Use the `Preview` tab to print or save PDF.
5. Use the `Dashboard` backup panel to export or import your full data.

## Notes

- Data is stored in the browser database on this computer.
- Existing `localStorage` data is migrated into the database on first load.
- Clearing browser site storage will remove saved data.
- This version does not require Node.js or installation.
