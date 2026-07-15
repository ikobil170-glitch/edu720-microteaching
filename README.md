# edu720-microteaching
# EDU720 Microteaching Booking Page

A live booking page for the EDU720 Microteaching Workshop with automatic slot management and data collection via Supabase.

## Features

✅ **Live Slot Management** - Slots close automatically when full (10 students per slot)  
✅ **Real-time Data Collection** - Bookings saved to Supabase database  
✅ **Color-coded Schedule** - Different times and days visually organized  
✅ **Email Validation** - Built-in form validation  
✅ **Responsive Design** - Works on desktop and mobile  

## Quick Start

### 1. Setup

- Clone this repository
- Open `index.html` in your browser
- The page will load automatically and connect to Supabase

### 2. Configuration

The Supabase connection details are already configured in `index.html`:

```javascript
const SUPABASE_URL = 'https://qwtwdiauteyghrrxsflp.supabase.co';
const SUPABASE_KEY = '...';
