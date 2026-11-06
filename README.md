# 👑 Reyaz Online Wedding Hall Booking Management System

A luxurious, high-performance, responsive web application designed for booking and managing grand wedding venues, royal banquets, and convention halls.

---

## 🌟 Key Features

### 🏰 1. Customer Booking Portal (`index.html`)
- **Luxury Aesthetic**: Styled with a regal Royal Gold, Deep Midnight Navy, and Ivory color palette, ambient gold particle canvas, and glassmorphism cards.
- **5 Exclusive Grand Venues**:
  - *The Royal Kohinoor Grand Ballroom* (Capacity: 1,000 - 2,500 guests)
  - *The Crystal Palace Banquets* (Capacity: 500 - 1,400 guests)
  - *Emerald Garden & Royal Pavilion* (Capacity: 600 - 1,800 guests)
  - *Noor Heritage Mahal Banquet* (Capacity: 350 - 900 guests)
  - *Sapphire Intimate Elegance Hall* (Capacity: 150 - 500 guests)
- **Interactive Availability Calendar**: Real-time month-by-month calendar showing available, partially booked, and fully booked dates. Clicking any date pre-fills the booking wizard.
- **Dynamic Live Booking Wizard**:
  - Event slot selection (Morning Gala with 15% discount, Evening Gala, Full Day 24h).
  - Guest counter validation.
  - Live Catering Menu options (Shahi Dastarkhwan Mughlai, Grand Continental & Fusion, Royal Pure Veg Banquet).
  - Signature Décor & Stage Theme customizer.
  - Premium Add-ons (4K Drone Crew, Pyro & Heavy Dry Ice Bridal Entry, Live Shehnai, DJ, Vintage Car).
  - Real-time Price Computation with 18% GST and 25% Advance deposit requirement.
  - Instant Official Printable Voucher / Tax Invoice with reference number.
  - Interactive audio celebration chime (Web Audio API synth).

### ⚙️ 2. Admin Management Dashboard (`admin.html`)
- **Real-Time KPIs**: Confirmed Revenue, Confirmed Bookings count, Pending Approvals, Active Halls, Total Guests Hosted.
- **Reservations Management Table**:
  - Live search by Client Name, Reference ID, Phone, or Hall.
  - Filter by Status: All, Confirmed, Pending, Cancelled.
  - Action buttons: Approve/Confirm, Cancel, View & Print Voucher, Delete.
- **Walk-in & Phone Reservation**: Modal to record off-line bookings directly into the database.
- **Hall Operations Manager**: Toggle switches to put halls under maintenance or open them for booking.
- **Revenue Analytics**: Visual progress bars showing revenue breakdown per venue.
- **Demo Data Reset**: Instant one-click restore to sample bookings and halls.

---

## 🚀 How to Run

1. **Option A (Desktop One-Click Launcher)**:
   - Double-click `Launch_Reyaz_Wedding_System.bat` located right on your Desktop.

2. **Option B (Direct Browser Open)**:
   - Open `Reyaz_Wedding_Hall_Booking_System` on your Desktop.
   - Double-click `index.html` to open the Customer Booking Portal.
   - Double-click `admin.html` to open the Management Dashboard.

3. **Option C (Local Server, Optional)**:
   - Run any HTTP server such as `npx serve` or Python's `python -m http.server 8000` inside the folder.
