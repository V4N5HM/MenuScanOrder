# MenuScanOrder

**MenuScanOrder** is a full-stack SaaS web application designed to digitize and streamline the dining experience in cafés, restaurants, and coffee shops. By combining QR code technology, real-time ordering, and an intuitive admin dashboard, MenuScanOrder enables contactless, efficient, and user-friendly order management for both customers and restaurants.

---

## Key Features

- **QR-Based Ordering**  
  Generate table-specific QR codes that link directly to digital menus.

- **Customer Ordering Interface**  
  Clean, responsive, and mobile-friendly digital menu with real-time order tracking.

- **Admin Dashboard**  
  Manage menus, tables, and orders with an intuitive UI.

- **Order Management**  
  Track incoming orders with status updates, customer details, and item breakdowns.

- **Feedback System**  
  Customers can submit ratings and reviews to help restaurants improve service.

- **Secure Login System**  
  Authenticated access with hashed passwords for admins and staff.

---

## Mockups

The repository includes HTML mockups for:
- Login Page
- Menu Creation
- Order Management
- QR Code Generator
- Customer Menu View

> *Note: These mockups are static and do not include backend/database functionality.*

---

## Database Design

The database supports:
- **Two User Roles:** Customers and Sellers
- **Multiple Restaurants:** Each managing their own menus and tables
- **Order History:** Tracks orders with customer, table, item, and status data

*See `database_design.png` or `schema.sql` (if added) for structure.*

---

## Technology Stack

**Frontend:**
- HTML/CSS + Bootstrap
- React.js (selected after comparison with Angular & Vue)

**Backend:**
- Node.js / Express (assumed for backend API, not yet implemented)

**Other Tools:**
- `QRCode.js` for QR generation
- `dbdiagram.io` for ERD
- `mermaid.js` (via mermaid.live) for Gantt chart planning

---

## Development Timeline

| Phase            | Duration        | Description                                          |
|------------------|------------------|------------------------------------------------------|
| Planning         | 1–2 weeks        | Requirement gathering, mockups, tech stack research |
| Design           | 2 weeks          | Wireframes, DB schema, architecture planning         |
| Development      | 8 weeks          | Frontend, backend, APIs, integration, debugging      |
| Testing & Deploy | 4–5 weeks        | QA, deployment, post-launch testing                  |

---

## How to Run (Mockups Only)

1. Clone the repository:
   ```bash
   git clone https://github.com/V4N5HM/Web-Development-Project-1.git
   cd Web-Development-Project-1
