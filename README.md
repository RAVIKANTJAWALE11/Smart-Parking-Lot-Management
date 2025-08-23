#  Smart Parking Lot Management (C++)

# Overview

The Smart Parking Lot Management System is a C++ program that manages the entry and exit of cars in a parking lot.
It uses a Linked List to store details of currently parked cars, allowing efficient insertions and deletions.
The program also ensures that the lot cannot exceed its maximum capacity, demonstrating overflow handling.

This project is a practical application of data structures and shows how they can be used in real-world systems.

#  Features

 Park a Car → Add car details (license number, owner name, entry time)

 Exit a Car → Remove a car from the parking lot using license number

 Display Parked Cars → View the list of all cars currently parked

 Overflow Handling → Prevents parking if the lot is already full

 Dynamic Memory Management → Cars are stored in memory only when parked

#  Data Structures Used

Struct (Car) → To store details of each car (license, owner, entryTime)

Singly Linked List → To maintain the list of currently parked cars

Dynamic Memory Allocation (new / delete) → For adding/removing cars dynamically

Counter Variable (count) → Tracks current number of cars to ensure capacity is not exceeded


# How to Run

1. Clone the repository

git clone https://github.com/RAVIKANTJAWALE11/Smart-Parking-Lot-Management.git

cd Smart-Parking-Lot/src

2.Compile the code

g++ parking_lot.cpp -o parking_lot

3.Run the program

./parking_lot
