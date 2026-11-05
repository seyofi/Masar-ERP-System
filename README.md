# Masar ERP System

Arabic-first construction ERP platform for contractors in Saudi Arabia.

## Product scope
The MVP focuses on General Contractors and connects:
- Projects, contracts, and BOQ
- Budgets and cost control
- Procurement and purchase orders
- Goods receipts
- Owner and subcontractor claims
- Approvals, audit, and reporting

## Architecture
- Modular monolith
- Next.js + TypeScript frontend
- NestJS + TypeScript backend
- PostgreSQL database
- Prisma ORM
- Arabic/English with RTL/LTR support

## Project principles
- Tenant isolation is a security boundary.
- Approved BOQ revisions are immutable.
- Budget, commitments, actual costs, and forecasts remain separate.
- Financial records require traceability and auditability.
- No compliance claim without implementation and verification.

## Current status
Foundation stage. No application modules have been implemented yet.
