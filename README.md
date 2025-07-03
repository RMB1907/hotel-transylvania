# Hotel Transylvania – C Booking Simulation

A spooky, fun-themed hotel booking system built in C. The program simulates room booking at "Hotel Transylvania", where guests can choose from themed rooms like Frankenstein’s Tower or The Vampire’s Casket. It handles room selection, booking availability, payment calculation, and generates a summary of due payments.

---

## Features

- Offers 4 types of themed rooms with different pricing and spookiness levels.
- Displays available rooms based on type.
- Prevents double booking using a `booked[]` tracker.
- Collects visitor details: name, stay duration, payment.
- Calculates and tracks due amounts if payment is partial.
- Generates a final summary of all bookings and dues.

---

## Room Types and Costs

| Room Type              | Room Index Range | Cost per Night | Spookiness |
|------------------------|------------------|----------------|------------|
| Frankenstein's Tower   | 0–4              | $250           | *          |
| The Mummy's Pyramid    | 5–9              | $300           | *          |
| The Werewolf's Cave    | 10–14            | $200           | *          |
| The Vampire's Casket   | 15–19            | $500           | ***        |

---

## 🛠️ Technologies Used

- **Language**: C
- **Compiler**: GCC / any standard C compiler
- **I/O**: `stdio.h`, `stdlib.h` for input, output, and exit handling

---

## 🧠 How It Works

- Visitors are prompted to choose a room type.
- The program shows only unbooked rooms within that type's range.
- If a valid room is selected, the system records:
  - Visitor name
  - Number of nights
  - Payment and dues
- At the end of all bookings, a summary of visitor names and dues is displayed.

---



