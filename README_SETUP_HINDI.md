# JeevanSetu — Registration Flow

App open → REGISTER → do options:
1. 🩸 Register as Donor
2. 🆘 Register as Receiver

Basic required details: Name, DOB, Mobile, Blood Group, State, District, City/Area, Password.

IMPORTANT: Donor/Receiver choice permanent role nahi hai. Account banne ke baad har user:
- 🆘 Blood chahiye → Find Blood se request kar sakta hai.
- 🩸 Blood dena hai → Donor Dashboard me Available ON kar sakta hai.

## College 2-phone demo
Phone 1: Receiver registration, B+, Bihar Sharif, availability OFF.
Phone 2: Donor registration, B+, Bihar Sharif, availability ON.

Phone 1 → Find Blood → B+ → Find Matching Donors → Send Request.
Phone 2 → Donor Dashboard → request → ACCEPT.
Phone 1 → My Requests → Accepted → CALL DONOR / WHATSAPP.

Both phones must use the same Firebase project. Enable Firebase Authentication (Email/Password), create Firestore, publish firestore.rules, and paste web config into firebase-config.js.

This is a college prototype. Do not enter real patient/donor sensitive information.
