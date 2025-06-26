@about.html Study this file and 
move all of it's css codes in @global.css page.
then use that css file to style in the about page.
The existing design must be remain same. i repeat the existing design must not change. so study each every word of code carefully and then proceed.




# PASMA-Personalised-AI-Powered-Smart-Medical-Assistant-
Personalised AI-powered health care system built with Flask. Features a medical admin panel with CRUD functionality, chatbot integration, role-based access, and structured JSON storage for managing patients, doctors, and medicines in a web-based environment.

Personalised AI-Powered Health Care System (PAHCS)
==================================================

📌 Overview:
------------
PAHCS is a web-based administrative medical platform designed to manage patients, doctors, and medicines with CRUD operations. 
It includes a built-in chatbot (chatbot.py) for basic health-related queries and supports JSON-based data storage (no database needed). 
The project is built using Flask and Python and is ideal for educational or small-clinic scenarios.

👨‍⚕️ Key Features:
------------------
- Admin login and session-based authentication
- Add/Edit/Delete Doctors, Patients, and Medicines
- View statistical dashboards
- Integrated medical chatbot
- File-based JSON storage (no SQL database)
- Role-based admin management (normal admin & super admin)

📁 Project Structure:
---------------------
PAHCS/
├── main.py                      → Chatbot and system controller (optional)
├── admin/
│   ├── main.py                  → Admin panel Flask app
│   ├── templates/               → HTML templates for admin pages
│   └── static/                  → Static assets used by admin
├── doctors.json                 → Stores doctor records
├── user_details.json            → Stores patient records
├── purchase_medicines.json      → Stores medicine data
├── admins.json                  → Stores admin login credentials
├── datasets/                    → CSVs for symptoms, training, and medications
└── README.txt                   → This file

🚀 How to Run:
---------------
1. Install Python 3.8 or higher
2. Navigate to the project directory:
   $ cd PAHCS

3. (Optional) Create a virtual environment:
   $ python -m venv venv
   $ source venv/bin/activate   (Linux/Mac)
   $ venv\Scripts\activate    (Windows)

4. Install Flask:
   $ pip install flask

5. Run the **admin panel** (IMPORTANT):
   $ cd admin
   $ python main.py

6. Open in your browser:
   http://127.0.0.1:5002/

🧑‍💻 Default Admin Credentials:
-------------------------------
Email   : admin@pasma.com
Password: admin123

🗃️ JSON Files Description:
----------------------------
- doctors.json              → Each entry is a dict with fields like name, specialization, phone, etc.
- user_details.json         → Stores user data with email as the unique key
- purchase_medicines.json   → List of medicine entries (name, price, stock, etc.)
- admins.json               → Stores admin credentials

⚠️ Important Notes:
-------------------
- Profile picture upload functionality is disabled.
- All data is stored in JSON files; no database is used.
- Make sure the `data/` and `static/uploads/` folders exist for smooth operation.

📬 Contact:
-----------
Developed by: Farhana Sharmin  
Email: far.camelia@gmail.com
