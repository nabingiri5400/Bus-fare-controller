# Bus-fare-controller
# Smart Bus Route & Fare System 🚌

## Overview
This is a **school project** that simulates a smart bus route and fare system.  
The system helps a user find available bus routes between a **start location** and **destination**, select a bus, handle transfers if needed, and calculate the total fare including **student discounts**.  

The main goal is to **provide an easy and transparent travel experience** for users, even in cities with multiple bus routes and transfers.

---

## Features

1. **Automatic Route Detection**
   - System detects if a **direct route is available**.
   - If no direct route exists, system finds **best transfer route** automatically.

2. **Bus Selection**
   - Shows available buses for each route or segment.
   - User selects preferred bus for each segment.

3. **Transfer Handling**
   - Shows where a bus change is required (e.g., A → G → Z).
   - Displays bus names for each segment.

4. **Fare Calculation**
   - Calculates fare for each segment.
   - Calculates total fare for the entire trip.

5. **Student Discount**
   - Prompts the user if they are a verified student.
   - Applies **40% discount** if eligible.

6. **Detailed Bill**
   - Displays:
     - Route path
     - Bus name(s)
     - Fare for each segment
     - Discount applied
     - Total payable

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/bus-project.git
