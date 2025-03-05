# EventHub - Documentation

This is the public documentation for the **EventHub** project.

## 📌 Access to the Original Code
This project is private. If you wish to access the original repository, please send a request.

🔒 **Link to the original repository:** [EventHub (private repo)](https://github.com/vegaFlex/EventHub) *(requires approval)*

📩 If you would like access, please contact me via [GitHub Issues](https://github.com/vegaFlex/EventHub_README/issues) or send me a direct message.

---

# EventHub - Event Management Platform

EventHub is a multifunctional web platform that allows users to browse, book, and purchase tickets for events while interacting with artists, organizers, and other attendees. The system includes advanced administrative capabilities and integrations for ticket management, orders, and payments.

---

## Table of Contents
1. [Features](#features)  
2. [Installation & Setup](#installation--setup)  
3. [Core Modules](#core-modules)  
4. [JavaScript & Interactive Features](#javascript--interactive-features)  
5. [Admin Panel](#admin-panel)  
6. [Technologies](#technologies)  
7. [Contact & Support](#contact--support)  

---

## Features
- Event management (create, edit, delete events)
- Ticket reservation and purchase with Stripe integration
- QR code generation for ticket validation
- User authentication (email confirmation, Google login, AJAX-based login)
- Order processing and history tracking
- Reviews and ratings system
- Admin panel for event, ticket, and order management
- Multilingual support (Bulgarian & English)
- Google Maps and OpenWeather API integration
- SendGrid email notifications

---

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/vegaFlex/EventHub.git
cd EventHub
```

### 2. Create a Virtual Environment
```sh
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

### 4. Database Setup
```sh
python manage.py migrate
```

### 5. Create a Superuser
```sh
python manage.py createsuperuser
```

### 6. Run the Server
```sh
python manage.py runserver
```

Project is accessible at: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)  
After deployment: [https://eventhub-fta3fsb7dgctfagd.italynorth-01.azurewebsites.net/bg/](https://eventhub-fta3fsb7dgctfagd.italynorth-01.azurewebsites.net/bg/)  

---

## Core Modules

### 1. Event Management
- **Create, edit, and delete events** (admin panel)
- **Search and filter events** by category, date, location
- **Featured events section**
- **Event details:** images, description, price, date
- **Seat availability tracking**
- **Google Maps integration for location display**
- **Weather forecast for event location (OpenWeather API)**

### 2. Ticket Management
- **Ticket purchase via Stripe**
- **Seat selection (standard & VIP options)**
- **Temporary reservation for 5 minutes**
- **QR code generation for ticket validation**
- **View purchased tickets in user profile**
- **Hide used tickets option**

### 3. User Accounts
- **AJAX-based login and registration**
- **Email confirmation with verification code**
- **Google OAuth2 login support**
- **Remember Me feature**
- **Profile management and ticket history**
- **Favorite events management**
- **Event participation requests**

### 4. Order Processing
- **Automatic order creation after successful payment**
- **Link orders to tickets and events**
- **Admin overview of all orders**
- **Distinction between registered and guest users**
- **Email confirmation for purchases**

### 5. Reviews & Ratings
- **User reviews on events**
- **Filter reviews by rating**
- **Admin approval required for reviews**
- **Star rating system**

---

## JavaScript & Interactive Features
- **AJAX-based ticket booking and favorite events**
- **Success messages with toast notifications**
- **Dynamic featured events slider**
- **Interactive seat selection**
- **Responsive design for mobile & desktop**
- **Language switcher (Bulgarian & English)**

---

## Admin Panel

🔗 **Access:** [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)  
After deployment: [https://eventhub-fta3fsb7dgctfagd.italynorth-01.azurewebsites.net/bg/admin/](https://eventhub-fta3fsb7dgctfagd.italynorth-01.azurewebsites.net/bg/admin/)  

### Admin Features
- **Manage Events:** Add, edit, delete events
- **Manage Tickets:** Monitor and validate ticket sales
- **View Orders:** Track and update order statuses
- **Approve Event Participation Requests**
- **Track ticket validation and usage**
- **Sales analytics via charts**
- **Top-selling events statistics**

---

## Technologies
- **Backend:** Django 5.1.2, Django REST Framework
- **Database:** PostgreSQL
- **Frontend:** TailwindCSS, JavaScript (AJAX, Swiper.js)
- **Payments:** Stripe API
- **External APIs:** Google Maps API, OpenWeather API, SendGrid API

---

## Contact & Support
For questions or issues, contact **vegaFlex@github.com**.

---

# EventHub_README
