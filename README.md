# Seascape Yacht Charter Dashboard

A comprehensive yacht charter management system with booking management, pricing configuration, and document generation.

## Features

- **Yacht Management**: Manage yacht fleet with specifications and availability
- **Booking System**: Create, edit, and track charter bookings
- **Pricing Configuration**: Seasonal pricing setup per yacht with high/low season rates
- **Document Generation**: Auto-create contracts, invoices, and receipts
- **Settings Management**: Configure yacht pricing and system settings

## Enhanced Charter Cost Reset

The booking management system includes enhanced reset functionality that allows operators to:

- Reset charter costs to pricing configuration values
- Refresh pricing from latest configuration data
- Visual indicators for overridden vs. configured pricing
- Smart button states based on override status

## Tech Stack

- React 18+ with Vite
- Tailwind CSS for styling
- Supabase for backend and database
- Document generation with auto-population
- Real-time data synchronization

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up Supabase configuration
4. Run development server: `npm run dev`

## Project Structure

```
src/
├── components/
│   ├── booking/          # Booking management components
│   ├── calendar/         # Calendar and timeline views
│   ├── settings/         # Pricing and system configuration
│   └── admin/           # Admin configuration tools
├── services/
│   └── supabase/        # Database and API services
└── utils/               # Helper functions and utilities
```