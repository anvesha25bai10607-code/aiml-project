♻️ Waste Management Request System (Python)
A simple Python-based Waste Management Request System that allows users to register waste collection requests, update their status, and generate statistics about waste types and collection progress.
This project demonstrates the use of Object-Oriented Programming (OOP) concepts such as classes, objects, class variables, and methods.
📌 Features
Register new waste disposal requests
Automatically generate unique request IDs
Store waste details such as:
Waste type
Weight
Pickup location
Update request status
View all requests
Generate waste management statistics
Simple command-line output
🧠 Concepts Used
This project demonstrates:
Object-Oriented Programming (OOP)
Classes and Objects
Class Variables
Lists and Dictionaries
Loops and Conditional Statements
Data aggregation and statistics
⚙️ How the System Works
The system contains two main classes:
1️⃣ WasteRequest
Represents a single waste collection request.
Attributes
request_id → Unique ID for each request
waste_type → Type of waste (Recyclable, Hazardous, General)
weight_kg → Weight of the waste
location → Pickup address
status → Request status (Pending, Scheduled, Completed)
2️⃣ WasteManager
Manages all waste requests and provides system operations.
📈 Future Improvements
Add user input interface
Create GUI using Tkinter
Add database support (SQLite / MySQL)
Add location tracking
Create web version using Flask or Django
