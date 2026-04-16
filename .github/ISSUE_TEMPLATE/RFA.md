## Title 

View Real-Time Facility Availability

## User Story

**As an** admin

**I want** to see real-time court availability

**So that** I can prevent double bookings

## Story Points

8

## Tasks

- [ ] Implement availability logic
- [ ] Sync bookings with schedule
- [ ] Test concurrency handling

## Acceptance Criteria

- [ ] Availability updates instantly
- [ ] Double booking is prevented

## Given / When / Then

**Given** a booking exists,

**when** another booking is attempted at the same time,

**then** the system blocks it.

## Validation and Evidence

**Validation method**
Booking conflict testing

**Related repository evidence**
docs/availability.md

---


