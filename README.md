# ✈️ Flight Reservation System in C++

A complete **Flight Reservation System** developed in **C++** as a  project. This system models real-world airline operations using only custom-built data structures — **no STL used**. It supports managing flights, airports, planes, customers, ticketing, class-based reservations (Business & Economy), offers, and more.

---

## 🔧 Features

- 🛫 Flight booking with **source & destination**
- 🧍 Customer registration, search, and cancellation
- 🪑 Reservation in **Business** or **Economy** class
- 🎟️ Ticket generation with detailed info
- 🏙️ Manage **airports** and routes
- 🛩️ Assign **planes** to specific flights
- ⏳ Waitlist system using **Queues**
- 🌟 Dynamic **offers & discounts** on select flights
- 📊 Search/sort flights and customers
- ✅ All core structures implemented from scratch

---

## 🧱 Data Structures Used

- 🔁 `DoublyLinkedList<T>` — used for managing airports, planes, and customer records  
- 🌳 `BST<T>` — for fast lookups of flights and customers  
- 📥 `Queue<T>` — used for managing waitlisted passengers and offers  
- 🧾 `Custom Classes` — including `Flight`, `Customer`, `Airport`, `Ticket`, `Plane`, `Offer`, and more  

---

## 💻 Technologies

- **Language**: C++  
- **OOP**: Fully object-oriented design  
- **No STL**: All data structures are implemented manually  
- **CLI Based**: Console input/output system  

---

## 📁 Modules Overview

```cpp
Flight
Customer
Airport
Plane
Ticket
Offer
Queue<T>
BST<T>
DoublyLinkedList<T>
