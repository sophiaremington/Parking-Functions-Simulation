# Parking Function Simulation with Dissatisfaction and VIP Reservations

This project was developed as a final assignment for **MATH 3705: Parking Functions** and explores how classical parking functions behave under new constraints like **driver dissatisfaction** and **VIP prioritization**. It combines combinatorics, probability, and simulation to study parking efficiency and fairness.

##  Project Overview

We simulate a parking lot scenario where each driver:
- Has a preferred parking spot
- Attempts to park in that spot or the next available one
- Accrues **dissatisfaction** for parking far from their preference
- Receives a **penalty** if they cannot park at all

###  VIP Extension

A second version introduces **VIP drivers** who get priority parking. Non-VIP drivers:
- Cannot take VIP-preferred spots
- Must avoid reserved spots when parking

We measure how **VIP reservations** affect fairness and efficiency.

##  Key Components

- **Core Functions**
  - `parking_function_with_penalties(preferences, penalty)`
  - `parking_with_vip_reservations(preferences, vip_flags, penalty)`

- **Metrics Tracked**
  - Total dissatisfaction
  - Parking success rate
  - Validity of the parking function

- **Analyses Performed**
  - How VIP ratio affects outcomes
  - How penalty size affects total dissatisfaction
  - Theoretical vs observed success rates

##  Visualizations

Using `matplotlib`, we visualize:
-  *VIP Ratio vs. Parking Outcomes*
-  *Penalty vs. Dissatisfaction*
-  *Theoretical parking function counts*

These help reveal surprising stability in parking success, even as constraints increase.

##  Randomized Simulation

We simulate thousands of parking scenarios with random preferences, VIP distributions, and penalty settings to evaluate performance statistically.

---

🔗 **[Click here to view the full interactive simulation (HTML)](ParkingFunctionsFinal.html)**

