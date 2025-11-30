# 🎬 QuickShow | Movie Ticket Booking Web App

QuickShow is a full-stack web application that allows users to explore movies, book tickets, and manage bookings. It features modern user authentication, dynamic seat selection, real-time notifications, and an admin dashboard for managing movies and bookings.  

---

## ✨ Features

### 👤 User Features
- **Signup/Login:** Sign up using Email, Phone number, or Social accounts via [Clerk](https://clerk.com/) 📧📱.  
- **Multi-Session Support:** Create and switch between multiple profiles without signing out 🔄.  
- **Movie Exploration:** Browse available movies with showtimes and details 🎥.  
- **Seat Selection:** Choose preferred seats while booking tickets 💺.  
- **Booking Confirmation & Reminders:** Receive email confirmations and reminders for booked movies ✉️⏰.  
- **Payment Handling:** If payment fails or is cancelled, seats are reserved for 10 minutes to retry payment ⏳💳.  

### 🛠 Admin Features
- **Movie Management:** Add, edit, and delete movies in the catalog 🎬📝.  
- **Booking Management:** View and manage all ticket bookings 📋.  

### ⚡ Background Jobs
- **Email Notifications:** Using [Inngest](https://www.inngest.com/), automatic emails are sent to users for:
  - New movie announcements 🆕🎥  
  - Booking confirmations ✅  
  - Reminders a few hours before movie time ⏰  

---

## 🛠 Tech Stack
- **Frontend:** React.js, TailwindCSS 💻  
- **Backend:** Node.js, Express.js 🖥️  
- **Database:** MongoDB 🗄️  
- **Authentication:** Clerk (Email, Social, Phone) 🔐  
- **Background Jobs:** Inngest ⚡  
- **Payment Integration:** Online payment gateway with seat reservation mechanism 💳💺  

---

## 🚀 How It Works
1. **User Authentication:**  
   - Users can sign up using multiple options and manage multiple profiles 👤🔄.  

2. **Movie Booking:**  
   - Select movie → choose seats → make payment → receive confirmation email 🎟️✅.  
   - Failed payments reserve seats for 10 minutes before releasing them ⏳💺.  

3. **Admin Dashboard:**  
   - Admin can add new movies, view bookings, and manage users 🎬📝.  

4. **Notifications:**  
   - Background jobs handle sending emails for movie announcements, booking confirmations, and reminders ⚡✉️.  

---

### 🟣 Hero Section
![Hero Section](https://github.com/user-attachments/assets/4b237777-d656-47d2-8720-86114b42c957)


