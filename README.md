# Building Billing System

## Goal
Track monthly water usage and generate accurate bills per apartment based on consumption and fixed charges.

## Core Features
- Monthly meter readings per apartment
- Automatic usage calculation (current - previous)
- Proportional bill calculation based on total building consumption
- Fixed monthly charges per apartment
- Monthly bill generation
- Payment tracking (future phase)

## System Concept
Each month:
- Meter readings are entered
- Usage is calculated per apartment
- Total building consumption is calculated
- Cost per unit is derived from total bill
- Each apartment is charged based on usage + fixed fee

## Roles
- Admin: manages data, inputs readings, generates bills
- User (Apartment Owner): views own usage, bills, and history

## Stack
- Supabase (Database, Auth, Backend)
- Next.js (Frontend - planned)
- GitHub (Version control)