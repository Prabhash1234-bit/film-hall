# Film Hall 🎬

This is the user-facing web application for **Film Hall**, an online ticket booking system for local theatres in Odisha.

## 🔥 Features

- 🎥 Browse uploaded movies with posters and showtimes
- 💺 Select seats and book tickets online
- 💳 Integrated Razorpay payment gateway
- 📄 Auto-download ticket as PDF after payment
- 🕒 Booking closes 2 hours before showtime

## 🌐 Live Website
👉 [Visit Film Hall Booking System](https://Prabhash1234-bit.github.io/film-hall/)

## 📁 Project Structure
public/
├── index.html
├── seat-booking.html
├── ticket.html
├── login.html
├── owner-dashboard.html
├── js/
│   ├── firebase-config.js
│   ├── auth.js
│   ├── upload.js
│   ├── index.js
│   ├── booking.js
├── css/
│   └── style.css


Firestore DB:
├── theatres (Collection)
│   └── <theatre_id> (Document)
│       ├── name: "Film Hall 1"
│       ├── ownerEmail: "owner1@example.com"
│       └── movies (Subcollection)
│           └── <movie_id>
│               ├── title
│               ├── showtimes [ ]
│               ├── price
│               └── posterURL
├── bookings (Collection)
│   └── <booking_id>...
## 📁 Project Structure

film-hall/
├── index.html            # Movie listing page
├── seat-booking.html     # Seat selection and payment
├── firebase-config.js    # Firebase setup
├── style.css             # (Optional) Stylesheet
## 🚀 How to Use

1. Open `index.html` to see available movies
2. Click on "Book Now"
3. Select your seat and showtime
4. Pay via Razorpay
5. Ticket auto-downloads after payment

## ⚙️ Technologies

- Firebase Firestore (movie/poster/showtime/price)
- Firebase Hosting (optional)
- Razorpay (payment)
- HTML/CSS/JavaScript

## 🛠 Admin Panel

Admin uploads movies using [`film-hall-admin`](https://github.com/Prabhash1234-bit/film-hall-admin) repository.

---

## 👤 Created By
**Prabhash Barik**  
GitHub: [@Prabhash1234-bit](https://github.com/Prabhash1234-bit)
