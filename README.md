# Vehicle Dealership Management Platform

Full-stack dealership web application for publishing and managing vehicle inventory through a public catalog and administrative workflows.

## Overview

This project was built as a commercial vehicle-sales platform rather than a static landing page. The application combines a customer-facing catalog with persistent data and management capabilities for dealership operations.

## Core capabilities

- Public vehicle inventory catalog
- Administrative vehicle management
- Category management
- Database-backed dynamic content
- Lead-generation flows
- WhatsApp-oriented customer contact
- Responsive web interface
- Production-ready Next.js application structure

## Technology

- Next.js 16
- React 19
- TypeScript
- Supabase
- Tailwind CSS
- ESLint

## Architecture

```text
Public Web Interface
        ↓
Next.js Application
        ↓
Business / Data Layer
        ↓
Supabase
   ├── Vehicles
   ├── Categories
   └── Operational Data
```

## Engineering focus

The project demonstrates full-stack CRUD-oriented application development, relational/persistent data usage, administrative workflows and integration of a public commercial interface with backend data.

## Local development

```bash
npm install
npm run dev
```

Production build:

```bash
npm run build
npm start
```

## Status

Client-oriented full-stack project. The original commercial deployment may no longer be active; this repository documents the engineering implementation.

## Author

David Fernando Flautero Peña — Full-Stack Software Developer
