# 🎬 Pega Ticketing and Booking

A Pega App Studio-based Movie Ticketing and Booking application designed to automate the complete movie ticket booking process.

## 📌 Project Overview

The application manages a movie ticket request from initial request creation to booking confirmation.

The workflow includes:

Request
   ↓
Check Show Availability
   ↓
Calculate Booking Cost
   ↓
Payment
   ↓
Allocate Seats
   ↓
Booking Confirmation
   ↓
Customer Notification

## 🎯 Objectives

- Automate movie ticket booking using Pega
- Check show and seat availability
- Calculate the total booking cost
- Process payment information
- Allocate seats to customers
- Generate booking confirmation
- Notify customers about their booking

## 🛠️ Technology Used

- Pega App Studio
- Pega Platform
- Case Management
- Workflow Automation
- Data Objects
- User Actions
- Notifications
- Business Rules

## 🔄 Case Workflow

### 1. Movie Ticket Request

The customer provides:

- Movie
- Show
- Show Date
- Show Time
- Number of Tickets
- Attendee details
- Accessibility requirements

### 2. Check Show Availability

The system checks:

- Available seats
- Required seats
- Seat availability status

### 3. Calculate Booking Cost

The system calculates:

Total Cost = Ticket Price × Number of Tickets

### 4. Payment

The customer provides:

- Payment Method
- Payment Status
- Transaction ID

The total cost is displayed for payment.

### 5. Allocate Seats

Available seats are assigned to the customer based on the requested number of tickets.

### 6. Booking Confirmation

After successful payment and seat allocation, the booking is confirmed.

### 7. Customer Notification

The customer receives a notification containing booking information.

## 📊 Main Data

The application contains data related to:

- Movie
- Show
- Attendee
- Tickets
- Available Seats
- Allocated Seat Numbers
- Booking Status
- Booking Confirmation
- Payment
- Transaction ID
- Customer Notification

## 👥 Team

Developed as a team project using Pega App Studio.

## 🚀 Future Enhancements

- Online payment gateway integration
- Email and SMS notifications
- Dynamic seat-map selection
- QR-code based ticket generation
- Booking cancellation
- Refund management
- Real-time seat availability
- Admin dashboard and analytics

## 📸 Screenshots

Project screenshots are available in the `screenshots` folder.

## 📄 License

This project is created for educational and academic purposes.
