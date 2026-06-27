# Hostel-Management-System
A complete Hostel Management System built with Oracle APEX and Oracle Database featuring 12 entities, role-based access, real-time dashboard, and automated notifications
# 🏨 Hostel Management System

A complete enterprise-level Hostel Management System 
built with Oracle APEX and Oracle Database.

## 📋 Project Overview

The Hostel Management System (HMS) is a full-featured 
web application designed for COMSATS University 
Islamabad to digitize and streamline all hostel 
operations.

## ✨ Features

### Core Features
- 🔐 Role-based access control (Warden/Staff/Student)
- 📊 Real-time dashboard with 8 stat cards & 5 charts
- 👨‍🎓 Complete student management with room allocation
- 🛏 Room inventory management
- 👷 Staff management with shift tracking
- 💰 Payment tracking and financial dashboard
- 🔧 Maintenance request lifecycle management
- 👥 Visitor log management
- 📢 Student complaint portal
- 👕 Laundry service management
- 📦 Inventory and asset management
- 🔄 Room transfer request system
- 🍽 Mess menu planning
- 🔒 Locker assignment management

### Advanced Features
- 🔔 Automated notification system
- 📈 Analytics and reporting dashboard
- 💰 Financial dashboard with revenue tracking
- 🔍 Global search across all entities
- 🏆 Certificate generation for staff
- 📅 Payment calendar view
- 📋 Audit trail logging
- 👥 User management portal
- ⏱ Session timeout security
- 📥 Download reports (CSV/Excel/PDF)

## 🗄️ Database Design

### Entities (12 Tables)
| # | Entity | Description |
|---|--------|-------------|
| 1 | ROOM | Room inventory management |
| 2 | STUDENT | Student registration |
| 3 | STAFF | Staff management |
| 4 | PAYMENT | Fee tracking |
| 5 | MAINTENANCE | Repair requests |
| 6 | VISITOR | Visitor logs |
| 7 | COMPLAINT | Grievance portal |
| 8 | LAUNDRY | Laundry service |
| 9 | INVENTORY | Asset management |
| 10 | ROOM_TRANSFER | Room changes |
| 11 | MESS_MENU | Meal planning |
| 12 | LOCKER | Locker assignment |

### Additional Tables
- CERTIFICATES — Staff performance certificates
- NOTIFICATIONS — System notifications
- AUDIT_LOG — Activity tracking
- HMS_USERS — User role management

## 🛠️ Technology Stack

| Technology | Usage |
|------------|-------|
| Oracle APEX 26.1 | Frontend & Backend |
| Oracle Database | Data storage |
| PL/SQL | Business logic |
| SQL | Data manipulation |
| HTML/CSS/JavaScript | UI customization |

## 📁 Project Structure
## 🌐 Live Demo

**Application URL:** https://apex.oracle.com/pls/apex/r/usman123456/hostel-management-system/home

### Demo Credentials

| Role | Username | Password | Access Level |
|------|----------|----------|--------------|
| 🔑 Warden | `admin` | `Hms@Comsats2024!` | Full Access |
| 👷 Staff | `staff1` | `Hms@Staff2024!` | Limited Access |
| 👨‍🎓 Student | `student1` | `Hms@Student2024!` | View Only |

### Role Permissions

| Feature | Warden | Staff | Student |
|---------|--------|-------|---------|
| Dashboard | ✅ | ✅ | ✅ |
| Students | ✅ | ✅ | ❌ |
| Rooms | ✅ | ✅ | ❌ |
| Staff | ✅ | ❌ | ❌ |
| Payments | ✅ | ✅ | ❌ |
| Maintenance | ✅ | ✅ | ✅ |
| Complaints | ✅ | ✅ | ✅ |
| Laundry | ✅ | ✅ | ✅ |
| Certificates | ✅ | ❌ | ❌ |
| Notifications | ✅ | ✅ | ✅ |
| User Management | ✅ | ❌ | ❌ |
