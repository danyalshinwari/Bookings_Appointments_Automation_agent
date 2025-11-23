AI Appointment Booking Assistant
A conversational web application designed to assist users with booking and retrieving appointments using a step-by-step, natural language interface. The application leverages Google Generative AI (Gemini-2.0-flash) via LangChain for processing user input and generating responses, while using SQLite for persistent data storage.

Features
Conversational Interface: Interact with an AI assistant that guides you through booking an appointment.
Step-by-Step Appointment Booking: Collects user details including name, email, appointment date, time, and reason.
Appointment Retrieval: Allows users to check existing appointment details.
Appointment Cancellation: Enables users to cancel all appointments by providing only their email address.
Input Validation: Ensures email addresses are in a valid format and checks for duplicate appointments.
Database Management: Automatically creates and updates a SQLite database to store appointment records.
Friendly Response Formatting: Uses an LLM to generate clear, user-friendly confirmations and appointment summaries.
