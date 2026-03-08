# Sprint 1 Plan - MyCare Appointment System

**Sprint Duration :** 9th March - 10th March, 2026

**Sprint Goal :** Build the essential booking flow from start to finish.

## Selected User Stories
### US-A01 : Set Hospitals Operating Hours
Priority : High

Acceptance Criteria :
- Admins can configure clinic hours for each day of the week
- Default hours : Mondaay - Friday 8:00 AM - 5:00 PM, Saturday 8:00 AM - 1:00 PM, Sunday Closed
- Admins can mark specific dates as holidays / closed
- Booking calendar only shows available dates / times
- Changes take effect immediately in patient booking interface

---
### US-P01 : Create Patient Account
Priority : High

Acceptance Criteria :
- Registration form with required fields: Full Name, IC / Passport, Email, Phone, Password
- Field validation
- "Create Account" button
- Success message after registration
- Redirect to login page or auto-login

---
### US-P02 : Book New Appointment
Priority : Critical

Acceptance Criteria :
- Select doctor
- Select date
- Select time
- Available slots shown in green, occupied shown in grey
- Select reason for visit
- Add extra notes (Optional)
- Booking summary shows : Doctor, Date, Time, Reason
- "Confirm Booking" button
- Cannot book same-day within 2 hours

---
### US-P03 : Receive Booking Confirmation
Priority : High

Acceptance Criteria :
- Success icon
- "Appointment Confirmed!" heading
- Confirmation number displayed
- Appointment details card
- Action buttons : "Add to Calendar", "View My Appointments"

---
### US-P04 : View All Appointments
Priority : High

Acceptance Criteria :
- Dashboard with 2 tabs : Upcoming & Past
- Upcoming tab (Default) :
  - Sort by date
  - Each appointment shows summary
  - Countdown
  - Action buttons : "View Details", "Reschedule", "Cancel"
- Past tab : Shows completed appointments
- If empty, show "No Appointments", "Book New Appointment"

---
### US-M01 : View Daily Schedule
Priority : High

Acceptance Criteria :
- Doctor dashboard showing today's date
- Appointment shown in chronological order
- Each appointment shows :
    - Time slot
    - Patient name and age
    - Reason for visit
    - Link to patient medical history
    - Consultation status : Upcoming, Checked-in, In Consultation, Completed
    - Lunch break and blocked time shown
    - Total patient count displayed
    - Tomorrow's schedule preview link
 
## Sprint 1 Summary
Total Screens Created :

User Flow Coverage :
