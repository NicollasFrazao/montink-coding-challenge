# Montink Mini ERP Challenge

Hiring challenge for a mini ERP of orders, products, coupons and stock.

## Context

Hiring challenge of Montink (2025).

This repository holds only the challenge statement, kept in Portuguese in [`CHALLENGE.md`](CHALLENGE.md). The solution is not included.

## Requested scope (from the statement)

- MySQL database with four tables: orders, products, coupons and stock.
- A screen to create and update products (name, price, variations, stock), with stock kept per product and, as a bonus, per variation.
- A "Buy" button that manages a session cart, controlling stock and order totals, with shipping rules based on the subtotal.
- Address lookup by postal code (CEP) using https://viacep.com.br/.
- Bonus: coupons with expiry date and minimum subtotal, an e-mail sent when the order is placed, and a webhook that receives an order ID and status (cancel removes the order; any other status updates it).
- Back end in plain PHP or CodeIgniter 3 (preferred), or Laravel; Bootstrap suggested for the screens.

## Notes

- Git history: four commits on 2025-07-25, all touching only `README.md`.
- The statement asks for the SQL that creates the database to be delivered with the code; it is not present.
