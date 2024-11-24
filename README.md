##  Airline-Management


This repository showcases a web application built using the MERN stack, which includes:

**MongoDB**: A NoSQL database for storing application data.

**Express.js**: A web application framework for Node.js.

**React.js**: A JavaScript library for building user interfaces.

**Node.js**: A JavaScript runtime for server-side programming.

The application leverages Node.js as the server powered by a MongoDB database. 

**Key Features of the Flight Booking Website:**

1) User Registration
The website requires all users to create an account to book flights. The process involves signing up with essential details such as name, email address, and password. Existing users can log in to their accounts using their credentials.

2) Flight Search
  Users can search for flights based on:
    • Departure and Destination Cities: Enter the desired locations to view available flights.
    • Travel Date: Specify the departure date to narrow down flight options.
    • Preferences: Additional filters may include direct flights, preferred airlines, or flight timings.

3) Flight Selection
  From the search results, users can:
    • Browse available flight options tailored to their input.
    • View important details such as departure time, arrival time, flight duration, layovers (if any), and price.
    • Select the most suitable flight for their journey.

4) Booking Process
  Once a flight is selected, the user is guided through a seamless booking process:
    • Seat Selection: Choose from available seats on the flight, such as aisle, window, or premium options.
    • Traveler Details: Input details of the passengers, including name, age, and ID details (if required).
    • Review Information: Double-check the flight details, seat preferences, and traveler information before proceeding to payment.
    • Payment Simulation: The website simulates a payment gateway for testing purposes. While no real transaction takes place, users can experience the full process of booking a flight.

5) Ticket Retrieval
  After completing the booking process, users can:
    • Access their flight tickets in the Profile section.
    • View booking confirmations, including seat number, flight details, and other relevant information.

6) E-Ticket Access
  Users can view their electronic tickets (E-tickets) directly in their profiles.
  The platform offers options to:
    • Share the E-ticket via email or other digital means.
    • Download the ticket as a PDF for offline access.

# Development steps

1. **Clone the repository:**
   - Begin by cloning the repository to your local machine.
   - You will find two main folders: `frontend` and `backend`.

2. **Set up the backend:**
   - Open a terminal and execute the following commands :
     cd backend
     npm install
     npm start
     
   - Confirm that the backend is running.

3. **Set up the frontend:**
   - Open a new terminal and to run these commands:
     cd frontend
     npm install

   - try IF FACING ERRORS:
     npm install --legacy-peer-deps
     
   - Then start the frontend using npm run start
   - Verify that the frontend is running.

Now, the website should be operational on your local computer, and you can proceed with testing.


1. **User Registration:**         Sign up is required for booking flights.

2. **Flight Search:**             Search for flights by destination, date, and preferences.

3. **Flight Selection:**          Choose from a list of available flights based on your search criteria.

4. **Booking Process:**           Seamlessly go through seat selection, traveler details, review, and payment.

5. **Ticket Retrieval:**          Post-payment, locate your flight ticket in the profile section.

6. **E-Ticket Access:**           View and manage your e-tickets in your profile, with options to share and download.

## TESING THE APPLICATION

1. **Login Credentials:**
   - Use the following details to log in OR you can sign up with your own mail ID:
     - **Email:** john@gmail.com
     - **Password:** John@123

2. **Flight Search:**
   - Since the database contains a limited number of flights, please use the following routes and dates for testing:
     - Guwahati to Delhi on June 20
     - Chennai to Mumbai on June 21
     - Kolkata to Bangalore on June 22
     - Visakhapatnam to Hyderabad on June 22
    
3. Begin by selecting your preferred seat, ensuring your comfort throughout the flight. Next, enter your traveler details to personalize your journey. Review all the information to ensure everything is in order before proceeding to the payment simulation. Since this is a mock-up, there’s no actual transaction—simply navigate back to find your ticket securely saved in your profile, ready for your upcoming adventure!
