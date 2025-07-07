# Hotel Transylvania – C Booking Simulation

A console-based hotel room booking system in C. Simulates guest registration, room selection, availability tracking, and payment handling.

---

## Core Logic

- Fixed 20-room array, grouped into 4 themed types  
- Room availability tracked via `booked[]` array  
- User input via `scanf()`; data stored in structs  
- Payment dues calculated and stored per visitor  
- Summary output with names and unpaid balances

---

## Room Config

| Room Type              | Index Range | Cost  |
|------------------------|-------------|-------|
| Frankenstein's Tower   | 0–4         | $250  |
| The Mummy's Pyramid    | 5–9         | $300  |
| The Werewolf's Cave    | 10–14       | $200  |
| The Vampire's Casket   | 15–19       | $500  |

---

## Tools

- Language: C  
- Compiler: GCC / standard C compiler  
- Headers: `stdio.h`, `stdlib.h`
