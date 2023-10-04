 Apponintment system
This is a simple outpatient appointment system API built using Node.js and Express.js. It allows users to list doctors, view details of a specific doctor, and book appointments with available doctors.

#Features

List doctors with their specialties and schedules. View details of a specific doctor. Book appointments with available doctors. Limit the number of patients a doctor can see.

#Getting Started

Node.js installed on your machine. npm or yarn package manager. #Usage Listing Doctors To list all available doctors, make a GET request to the /doctors endpoint:

http://localhost:3000/

Viewing Doctor Details To view details of a specific doctor, make a GET request to the /doctors/{doctorId} endpoint, replacing {doctorId} with the actual doctor's ID:

http://localhost:3000/doctors/1

Booking Appointments To book an appointment with a doctor, make a POST request to the /appointments endpoint with the doctor's ID and patient's name API Endpoints GET /: List all doctors.

GET /doctors/{doctorId}: Get details of a specific doctor.

POST /appointments: Book an appointment with a doctor.
