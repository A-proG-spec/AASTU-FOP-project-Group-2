# Addis Ababa Science and Technology University

# Fundamentals of Programming 2 - Group Project

##  Smart Parking Management System

The **Smart Parking Management System** is a console-based C++ application that automates parking slot management, booking, and billing. It provides separate interfaces for administrators and customers, with real-time database integration using MySQL.

##  Group Members

| No. | Name | ID |
|-----|------|-----|
| 1 | Ahmedin Muhamed | ETS0116/17 |
| 2 | Anteneh Wondwosen | ETS0186/17 |
| 3 | Arjuma Tilahun | ETS0190/17 |
| 4 | Arsema Negash | ETS0197/17 |
| 5 | Betibeb Aregahegn | ETS0300/17 |
| 6 | Arsema Desalegn | ETS0196/17 |

##  Features

### Admin Functions
- Add, modify, and remove parking slots
- Dynamic rate configuration (per slot or by type)
- View all slots with occupancy status
- System statistics monitoring

### Customer Functions
- View available parking slots (VIP customers see premium spots)
- Book parking spots
- Checkout with automatic billing
- View booking history
- Profile management
- Password update

##  Technologies Used

| Technology | Purpose |
|------------|---------|
| C++ | Core programming language |
| MySQL | Database management |
| MariaDB Connector | C++ MySQL integration |
| Git | Version control |

##  Database Schema

The system uses the following tables:
- `User` - User accounts (admin/customer)
- `ParkingSlot` - Parking spot information
- `Booking` - Booking records
- `Vehicle` - User vehicle information
- `Payment` - Transaction records

## Installation & Setup

### Prerequisites

1. **Install MySQL/MariaDB**
   - Default credentials: root/root (update as needed)

2. **Install MinGW or GCC Compiler**
   - Use any C++ compiler with MySQL support
