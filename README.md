# Practice 1: JSON Travel Itinerary

## Assignment Requirements

Create a JSON object representing a travel itinerary that includes:

- Trip Name
- Traveler Information
  - Name
  - Contact Information
    - Email
    - Phone
- Destinations
  - Location
  - Arrival Date
  - Departure Date
  - Activities
    - Title
    - Time

Additional Requirements:

- At least 2 destinations
- At least 2 activities per destination
- Proper JSON formatting
- Use nested objects and arrays

---

## Planning Notes

I chose a European travel itinerary.

Destinations:
1. Paris
2. Rome

Reasoning:
- Both destinations are common international travel locations.
- They provide opportunities for multiple activities.
- They demonstrate the use of nested JSON structures.

---

## JSON Structure Design

Trip
├── Traveler
│   └── Contact Information
└── Destinations
    ├── Paris
    │   └── Activities
    └── Rome
        └── Activities

---

## Requirement Checklist

✓ Trip Name included

✓ Traveler object included

✓ Traveler name included

✓ Contact object included

✓ Email included

✓ Phone included

✓ At least 2 destinations

✓ Arrival and departure dates included

✓ At least 2 activities for Paris

✓ At least 2 activities for Rome

✓ Proper JSON formatting

✓ Nested objects used

✓ Arrays used

---

## Files

- itinerary.json

This file contains the completed JSON travel itinerary.
