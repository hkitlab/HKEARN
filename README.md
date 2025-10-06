# 💼 HK EARN— টাস্ক করে আয় করুন 💰

একটি আধুনিক **HK EARN** যেখানে ইউজাররা দৈনিক টাস্ক (যেমন ভিডিও দেখা, লাইক দেওয়া, সাবস্ক্রাইব করা, ভোট দেওয়া ইত্যাদি) সম্পন্ন করে টাকা আয় করতে পারে।  
এটি একটি সম্পূর্ণ **Frontend Demo Version (HTML + CSS + JS)** — ভবিষ্যতে সহজেই Laravel / PHP / Firebase backend যুক্ত করা যাবে।

---

## 🌐 Project Overview

**Project Name:** Task Earn BD  
**Type:** Task Earning Platform  
**Technology:** HTML, CSS, JavaScript  
**Version:** v1.0.0 (Frontend Demo)  
**Language:** বাংলা + English  
**Author:** Md. Kibriya  
**License:** MIT  

---

## 🚀 Live Features

### 👤 User Features
- Login / Register System  
- User Dashboard (Balance, Tasks, Withdraw, Referral)  
- Task List (Video, Like, Subscribe, App Install etc.)  
- Package Purchase System (Free, Bronze, Silver, Gold, Diamond)  
- Withdraw Request Page  
- Referral System (Referral Link & Bonus)  
- Profile & Support Page  
- Notification Bar  

### 👑 Admin Features
- Admin Dashboard (Total Users, Earnings, Withdraw Stats)  
- User Management (View, Block, Add Balance)  
- Task Management (Create, Approve, Reject)  
- Package Management (Create, Edit, Delete)  
- Payment Gateway Setup (Bkash/Nagad Manual UI)  
- Withdraw Approvals  
- Notification System  
- Reports & Analytics  

---

## 💳 Package System (Demo Data)

| প্যাকেজ নাম | মূল্য | মেয়াদ | দৈনিক টাস্ক | প্রতি টাস্ক আয় |
|-------------|--------|--------|---------------|----------------|
| Free | 0৳ | Unlimited | 3 | 1৳ |
| Bronze | 200৳ | 30 দিন | 10 | 2৳ |
| Silver | 500৳ | 30 দিন | 25 | 3৳ |
| Gold | 1000৳ | 30 দিন | 50 | 4৳ |
| Diamond | 2000৳ | 60 দিন | 100 | 5৳ |

---

## 🗂 Folder Structure

hkearn/
│
├── index.html
├── login.html
├── register.html
│
├── user/
│ ├── dashboard.html
│ ├── tasks.html
│ ├── packages.html
│ ├── withdraw.html
│ ├── referral.html
│ ├── profile.html
│ └── support.html
│
├── admin/
│ ├── dashboard.html
│ ├── users.html
│ ├── tasks.html
│ ├── packages.html
│ ├── payments.html
│ ├── withdraw.html
│ ├── notifications.html
│ └── reports.html
│
├── assets/
│ ├── css/
│ │ ├── style.css
│ │ ├── user.css
│ │ ├── admin.css
│ │ ├── responsive.css
│ │ └── darkmode.css
│ ├── js/
│ │ ├── main.js
│ │ ├── user.js
│ │ ├── admin.js
│ │ ├── payment.js
│ │ └── api.js
│ ├── images/
│ │ ├── logo.png
│ │ ├── banner.jpg
│ │ └── icons/
│ └── fonts/
│
├── data/
│ ├── packages.json
│ ├── tasks.json
│ ├── users.json
│ └── transactions.json
│
└── README.md
---

## 🧭 How to Use Locally

1. **Clone or Download:**
   ```bash
   git clone https://github.com/hkitlab/hkearn.git
   npm install -g live-server
live-server
Open index.html
