# Nour's Order Desk - Project Plan

## 1. The Client Problem
Nour runs a handmade candle business. Her orders are scattered across notebooks and WhatsApp, making it difficult to track what customers requested, the total cost, and what needs to be prepared.

## 2. Required Features
- **List Orders:** View customer, product, quantity, total, and status.
- **View Order:** Open full details in a side panel or modal.
- **Add Order:** Submit via form; show the saved server response.
- **Update Order:** Edit information and change status (Pending, Preparing, Delivered).
- **Delete Order:** Confirm before deleting.
- **Summary Counts:** Display total, pending, and delivered counts based on real data.

## 3. API Endpoints
- `GET /api/orders` - Return all orders
- `GET /api/orders/[id]` - Return a single order
- `POST /api/orders` - Create a new order
- `PATCH /api/orders/[id]` - Update an existing order
- `DELETE /api/orders/[id]` - Remove an order

## 4. Implementation Steps
1. Define TypeScript types and interfaces.
2. Create a shared in-memory data store (`globalThis`).
3. Build validation and calculation logic.
4. Implement Route Handlers (GET, POST, PATCH, DELETE).
5. Build the frontend dashboard UI.
6. Connect the UI to the API using `fetch`.
7. Test error handling and edge cases (Postman).
8. Document findings in `REVIEW.md`.