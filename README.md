# Dynamic Ticketing System with Priority Waitlist

A Python-based dynamic ticketing system designed to manage seat bookings, cancellations, priority-based waitlists, and real-time seating capacity expansion using core data structures.

---

## Project Overview

This project simulates a high-demand event ticketing scenario where users can book specific seats, modify or cancel reservations, and join a waitlist when the event is sold out.

The system was designed with a strong focus on **data structures and algorithmic efficiency**, rather than external frameworks. It demonstrates how foundational computer science concepts can be used to build a realistic, stateful system that adapts to changing demand.

The scenario assumes an event initially offering 500 seats, with the ability to dynamically increase capacity when demand exceeds availability.

---

## Key Features

- Seat booking with unique ticket ID generation  
- Seat availability checks and visual seat map display  
- Priority-based waitlist (VIP, special, regular)  
- Automatic seat reassignment upon cancellation  
- Ticket modification (seat and priority updates)  
- Dynamic seating capacity expansion  
- Menu-based interactive interface for testing and demonstration  

---

## Data Structures & Concepts Used

- **Dynamic Arrays (Lists)** — seat grid representation  
- **Hash Tables (Dictionaries)** — fast ticket lookup by ticket ID  
- **Priority Queue** — waitlist management based on customer priority  
- **Object-Oriented Programming** — modular system design  
- **Algorithmic Thinking** — efficient reassignment and state handling  

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/frossardpaula/dynamic-ticketing-system.git
   ```
2. Open the Jupyter notebook:
  ```text
  jupyter notebook CMPT2021_Paula_Frossard_Ticketing_System.ipynb
   ```
3. Run the notebook cells and use the interactive menu to:

- Book seats
- Cancel or modify bookings
- Test waitlist behavior
- Increase seating capacity
- No external libraries are required beyond standard Python.

---

## Repository Contents

- **CMPT2021_Paula_Frossard_Ticketing_System.ipynb**  
  Main implementation of the ticketing system with an interactive menu and test cases.

- **CMPT2021_Paula_Frossard_Ticketing_System_Report.pdf**  
  Detailed technical documentation explaining the system design, logic, and implementation decisions.

- **README.md**  
  Project overview and usage instructions.

---

## Notes & Future Improvements

Potential extensions discussed for this system include:

- Group bookings under a single user ID  
- Ticket limits per user  
- Adjacent seat suggestions for multi-seat bookings  
- Discount and refund logic  
- Unit testing for automated validation  
- Alternative seat labeling to support unlimited capacity growth  

---

## License

This project is licensed under the MIT License.
