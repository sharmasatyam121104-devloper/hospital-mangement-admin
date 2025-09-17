
````markdown
# Prescripto Admin Panel  
**Smart Hospital Management & Online Appointment Booking System**

This **Admin Panel** is part of the Prescripto system, allowing administrators to manage **Doctors, Users, Appointments**, and **system settings** efficiently.

---

## **Features**

- **Doctor Management:** Add, edit, and remove doctors.  
- **User Management:** View and manage registered users.  
- **Appointment Management:** Track all appointments, approve or cancel as needed.  
- **System Settings:** Configure payment gateways, analytics, and other system-wide settings.  

---

## **Technologies / Stack**

- React.js / Next.js (or your frontend framework)  
- Node.js (if fullstack integration needed)  
- Axios (API calls)  
- Tailwind CSS / Bootstrap (UI styling)  

---

## **Installation Steps**

1. Clone the repository:

```bash
git clone https://github.com/sharmasatyam121104-devloper/hospital-mangement-admin.git
cd hospital-mangement-admin
````

2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file (if required for API endpoints):

```env
REACT_APP_API_URL=http://localhost:5000
```

4. Start the Admin Panel:

```bash
npm start
```

Panel will run on `http://localhost:3000` (default React port).

---

## **API Endpoints**

*(These endpoints connect to the backend server)*

* `/api/admin/login` – Admin login
* `/api/admin/doctors` – Add/Edit/Delete doctors
* `/api/admin/users` – Manage users
* `/api/admin/appointments` – View and manage appointments

> Make sure the **backend server** is running before using the Admin Panel.

---

## **Contributors / Author**

* Satyam Sharma



