<h1 style="display: flex; align-items: center;">
  <img src="./assets/readyplato.png" width="50" style="margin-right: 10px;">
  ReadyPlato
</h1>

ReadyPlato is a smart food pre-booking platform that allows users to select restaurants, choose food items, and reserve tables with seating capacity in advance. The system reduces waiting time and improves dining efficiency.

---

## 👤 User Authentication & Profile

After successful authentication, the user is redirected to the profile completion page.

Users must provide:
- Name  
- Age  
- Address  
- Place  
- Pincode  
- Phone Number  
- Email  

Users can also view and update their profile anytime.

---

## 🍴 Restaurant Authentication & Profile

After authentication, the restaurant must complete its profile with:

- Restaurant Name  
- Owner Name  
- Address  
- Place  
- Pincode  
- Phone Number  
- Email  
- FSSAI Certificate  

These details are sent for admin verification before access is granted.

---

## 🔄 User Flow

1. Users browse different restaurants  
2. Select a restaurant to view:
   - Details  
   - Food categories  
   - Food items with variants and quantities  
3. Select food items  
4. Proceed to table selection  

---

## 🪑 Table Selection Logic

- Users must enter the number of guests  
- Tables are enabled based on guest count  

### Rules:
- Tables matching guest count are prioritized  
- If unavailable, larger tables are shown  
- Users can select larger tables if needed  
- If selecting partially available seats → extra charge per seat may apply  

---

## 📅 Booking Process

1. User selects a time slot  
2. Booking request sent to restaurant  

### Conditions:
- Restaurant must accept/reject within **5 minutes**  
- If accepted → user must pay within **10 minutes**  
- If not paid → booking is automatically cancelled  

---

## ✅ Verification

Upon arrival:
- User shows **Booking ID (QR Code)** OR  
- Restaurant manually verifies  

After verification → booking is confirmed.

---

## 📱 Applications

### 👤 User App
- Browse restaurants  
- Select food items  
- Reserve tables  
- Manage bookings  
- View reviews  
- Manage profile  

---

### 🍴 Restaurant App
- Authentication & profile setup  
- Admin verification required  
- Manage tables and food items  
- Handle bookings  
- View payments  
- Generate reports  
- Update profile  

---

### ⚙️ Admin App
- Manage users and restaurants  
- Verify restaurant registrations  
- Manage categories  
- Generate reports  

---

## 📌 Status

🚀 Actively in development  

---

## ⚠️ Usage Notice

This project is publicly visible for portfolio purposes only.  
All rights are reserved. Unauthorized use, copying, or distribution is prohibited.