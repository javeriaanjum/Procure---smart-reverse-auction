PROCURE FRONTEND FUNCTIONAL DEMO
=================================

Included files:
- customer-dashboard.html
- seller-dashboard.html
- quotation-comparison.html

How to try it:
1. Extract the ZIP into a folder.
2. Open that folder in VS Code.
3. Open index.html if you have your existing homepage in the same folder; otherwise open any of the three pages directly.
4. Use VS Code Live Server (recommended). Open customer-dashboard.html in the browser.
5. Create a requirement and publish it.
6. Open Supplier Portal, select that requirement, fill in supplier name/price/delivery, and submit a quotation.
7. Return to Customer Dashboard and click View / Compare Quotations on the requirement.
8. Choose a supplier to save the selection locally.

Important:
- This is a frontend-only prototype. It shares demo data across pages through browser localStorage on the same browser/origin.
- It is not a real multi-user online system and does not use Java, Spring Boot or MySQL yet.
- Do not mix file:// opening and Live Server URLs; localStorage is origin-specific.
- Keep a backup of your existing HTML files before replacing them.
- Once your backend teammate shares the API endpoints, the localStorage calls can be replaced with fetch() calls to the Java backend.
