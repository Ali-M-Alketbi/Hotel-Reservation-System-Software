Hotel Management System
This project provides a simple class-based system to manage hotel reservations, rooms, guests, and payments. The code defines four main classes: Room, Guest, Reservation, and Payment, each handling specific functionalities related to a hotel booking system.

Classes
1. Room
Represents a room in the hotel with attributes such as:

room_number: The unique room number.
room_type: The type of the room (e.g., "Single", "Double").
price_per_night: The price of the room per night.
status: The availability status of the room ("Available" or "Occupied").
Methods:

Getter and setter methods for room attributes.
check_availability(): Returns whether the room is available for booking.
2. Guest
Represents a guest in the hotel with attributes:

guest_name: The name of the guest.
email: The guest's email address.
phone: The guest's contact phone number.
Methods:

Getter and setter methods for guest attributes.
3. Reservation
Handles the reservation process with attributes:

reservation_id: The unique reservation ID.
guest: The guest who made the reservation.
room: The room reserved.
check_in_date: The check-in date.
check_out_date: The check-out date.
total_price: The total cost of the reservation (calculated based on room price and duration of stay).
Methods:

Getter and setter methods for reservation attributes.
calculate_total_price(): Calculates the total price for the stay based on the room price and the number of nights.
4. Payment
Handles payment processing with attributes:

payment_id: The unique payment ID.
payment_method: The method of payment (e.g., "Credit Card", "PayPal").
amount: The amount to be paid.
Methods:

Getter and setter methods for payment attributes.
process_payment(): Simulates processing the payment based on the payment method and amount.
