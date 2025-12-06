# Movie Theater Seat Reservation System

A simple console-based **Movie Theater Seat Reservation System** built in Java using 2D arrays.

I created this project to practice Java fundamentals like arrays, loops, user input, and error handling.

## Features
- 5 rows × 8 seats = **40 total seats**
- Live seating chart with "SCREEN THIS SIDE" at the top
- Available seats show their number (1-40)
- Reserved seats marked as **X**
- Full input validation (only accepts 1-40 or 0 to quit)
- Clean and easy-to-read output
- Prevents double booking

## How to Run

```bash
javac SeatReservationSystem.java
java SeatReservationSystem
How to Use

The current seating chart is displayed
Enter the seat number (1-40) you want to book
Enter 0 to exit the program
Enjoy your reserved seat!

Sample Output
text=== CURRENT SEATING CHART ===

          SCREEN THIS SIDE
   --------------------------------
Row 1   1   2   3   4   5   6   7   8 
Row 2   9  10  11  12  13  14  15  16 
Row 3  17  18  19  20  21  22  23  24 
Row 4  25  26  27  28  29  30  31  32 
Row 5  33  34  35  36  37  38  39  40 
   --------------------------------
Legend: Numbers = Available,  X  = Reserved
What I Learned

Working with 2D arrays
Converting seat numbers to row-column using math
Input validation with try-catch
Formatting output nicely
Building interactive console apps

Made by me with love for Java
