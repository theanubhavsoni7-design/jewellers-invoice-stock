# Radhey Shyam Vishnu Kumar Jewellers — Invoice & Stock Manager

## Included
- Invoice creation and print / Save as PDF
- HSN field; GSTIN printed as business identification only
- No GST calculations or tax breakdown
- Gold/silver stock by item code, purity, quantity, gross and net weight per piece
- Automatic stock quantity deduction when saving invoices using stock-linked items
- Stock purchase/addition, low-stock indicator, invoice history, cancellation/return stock restoration
- JSON export and restore backup

## Important limitations
- This is a browser-based, offline-friendly prototype. Data is stored in the browser on the device where it is used.
- It does not automatically sync across devices or users. Export backups regularly.
- It deducts item quantity. Weights shown on invoices are calculated from the stored per-piece weight multiplied by quantity; it does not support fractional-piece sales or partial returns automatically.
- No GST is calculated.
- Test the workflow with sample records before relying on it for real shop transactions.

## Run
Open `index.html` in a modern browser. For a persistent website, upload `index.html` to the root of a GitHub repository and enable GitHub Pages for the main branch/root folder. This ZIP includes the file and instructions; it does not itself publish the app.
