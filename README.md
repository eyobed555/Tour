# Tour Booking & Travel Package Management System
Overview
This C++ program is a simple Tour Booking and Travel Package Management System that allows users to manage tours and handle customer bookings. The system uses a combination of arrays (for tour storage) and linked lists (for booking management) to provide basic CRUD operations for tours and bookings.

Features
Tour Management:

Add new tours with destination, date, and available seats

Search for tours by ID

Update existing tour information

Delete tours

Display all available tours

Booking Management:

Create new bookings linking customers to tours

Cancel existing bookings

View all current bookings

Data Structures Used
Array: Used to store and manage tour information

Linked List: Used to manage bookings with efficient insertion and deletion

How to Use
Compile the program using a C++ compiler (e.g., g++)

Copy
g++ tour_management.cpp -o tour_management
Run the executable

Copy
./tour_management
Follow the menu prompts to manage tours and bookings

Menu Options
Add Tour

Search Tour

Update Tour

Delete Tour

Display Tours

Book Tour

Cancel Booking

Display Bookings

Exit

Limitations
Uses simple console interface

Data is not persisted between program runs (all data is lost when program exits)

Limited error handling for user inputs

Fixed array size for tours (maximum 100 tours)

Future Enhancements
Add file persistence to save data between runs

Implement more sophisticated search functionality

Add input validation

Expand the data model with more fields (e.g., pricing, duration)

Implement a graphical user interface

Author
[Group 4]

License
This project is open-source and available under the MIT License.
