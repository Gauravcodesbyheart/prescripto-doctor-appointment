# prescripto-doctor-appointment
Online Doctor Appointment System
Prescripto is a comprehensive full-stack web platform crafted to enhance accessibility in healthcare by streamlining the doctor appointment booking process. It features role-based access with three distinct user types—Patients, Doctors, and Admins—each equipped with specialized functionalities to meet their specific needs. The application incorporates secure payment processing through Stripe and Razorpay gateways, ensuring reliable and hassle-free transactions. Developed on the MERN stack (MongoDB, Express.js, React.js, Node.js), Prescripto delivers a responsive, intuitive, and efficient experience for patients and medical professionals alike.
🛠️ Technology Stack

Frontend: React.js
Backend: Node.js with Express.js
Database: MongoDB
Payment Integrations: Stripe and Razorpay
Authentication: JSON Web Tokens (JWT)

🔑 Core Features

Multi-Role Authentication System
Patient Portal:
Users can register, authenticate, and schedule appointments with available doctors.
Easily view, reschedule, or cancel bookings.
Flexible payment choices: Cash, Stripe, or Razorpay for secure online transactions.
Personalized profile management, including updates to name, email, address, gender, date of birth, and profile image.
Doctor Portal:
Secure login to oversee scheduled appointments.
Intuitive dashboard showcasing total earnings, patient count, appointment volume, and recent bookings.
Profile customization options: Update bio, consultation fees, location, and availability status.
Detailed appointment insights, including patient details, payment method, and current status.
Admin Portal:
Full control over doctor registrations and profiles.
Analytics-driven dashboard highlighting total doctors, appointments, patients, and latest activities.
Tools to add new doctors with comprehensive details (photo, specialization, qualifications, experience, location, fees, etc.).
System-wide appointment oversight with options to cancel or mark as completed.


🏠 Landing Page
An engaging and intuitive homepage that allows visitors to:

Browse and search doctors by medical specialty.
Discover featured top doctors and access their detailed profiles.
Explore informative sections such as About Us, Delivery Details, Privacy Policy, and Contact Information.
Navigate effortlessly via a comprehensive footer with links to key pages: Home, About, Delivery Info, Privacy, and Contact.

🩺 Doctors Directory Page

Comprehensive listing of all registered doctors.
Advanced filtering by specialty for quick searches.
Direct links to individual doctor profiles, leading to the dedicated appointment scheduling page.

📄 About Us Page

Detailed overview of Prescripto's mission to revolutionize healthcare access.
"Why Choose Us" highlights:
Streamlined Efficiency: Simplified booking workflow.
Ultimate Convenience: Anytime online scheduling and payments.
Customized Experience: Personalized features tailored to user needs.

Reinforced with footer links for easy site navigation.

📞 Contact Page

Clear display of office location and communication channels.
Dedicated section for career opportunities.
Consistent footer with essential navigation options.

📅 Doctor Profile & Booking Page

In-depth doctor details: Profile photo, credentials, years of experience, and professional summary.
Integrated booking interface: Select preferred date, slot, and payment option.
Support for cash or online payments via Stripe/Razorpay.
Suggested related doctors for alternative options.
Mandatory login or registration for booking confirmation.

👤 My Profile Section

Available post-login for personalized management.
Edit core details: Upload avatar, modify personal info (name, email, address, etc.).
Centralized view of upcoming and historical appointments.
Secure logout functionality.

🗄️ Admin Dashboard

Key metrics at a glance: Counts of doctors, appointments, patients, and recent transactions.
Quick actions to manage or cancel bookings.
Dedicated "Add Doctor" module with full-form inputs for profile creation.
Doctor management list with edit/delete capabilities.
Global appointments overview, including patient demographics, timing, doctor assignment, fees, and status updates (cancel/complete).

🩺 Doctor Dashboard

Financial summary: Cumulative earnings from confirmed consultations.
Detailed appointment roster with patient info, timing, payment details, and status.
Actionable controls: Mark as completed or cancel.
Seamless profile updates for bio, fees, address, and availability.

💳 Payment Processing

Versatile options: On-site cash, or digital via Stripe/Razorpay.
Prioritizes security and user convenience for frictionless experiences.

🌐 Local Setup Guide
To run the project on your machine:

Clone the Repository:textgit clone https://github.com/your-username/prescripto.git
cd prescripto
Install Dependencies:textnpm install
cd client
npm install
Configure Environment Variables:
Create a .env file in the root folder with:textMONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_API_KEY=your_stripe_api_key
RAZORPAY_API_KEY=your_razorpay_api_key
Launch the Application:textnpm run dev

📦 Project Structure
textprescripto/
├── client/          # React.js Frontend Components
├── server/          # Node.js & Express.js Backend Logic
├── models/          # MongoDB Data Schemas
├── controllers/     # Business Logic & API Handlers
├── routes/          # Endpoint Definitions
├── middleware/      # Auth Guards & Error Management
├── config/          # Setup & Connection Files
├── utils/           # Helper Functions & Tools
├── public/          # Static Assets
└── .env             # Sensitive Configuration Variables
