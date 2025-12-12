# CareLove - Healthcare Appointment Management System

A modern, full-stack healthcare appointment scheduling platform that streamlines the patient registration and appointment booking process while providing healthcare providers with a comprehensive admin dashboard for appointment management.

## ⚠️ **IMPORTANT SECURITY NOTICE**

**DO NOT USE REAL PERSONAL INFORMATION IN THIS APPLICATION.**

This is a demonstration project for portfolio purposes. Any information entered into this system will be stored in a database. **If you choose to enter real personal information (names, phone numbers, emails, medical details, etc.), you do so at your own risk.** The creator of this project is not responsible for any misuse or theft of information you voluntarily provide.

**For testing purposes, please use fictional data only.**

---

## 🎯 Project Purpose

CareLove addresses real-world problems in healthcare appointment scheduling by providing:

### Patient-Facing Features:
- **Quick Registration**: Patients can register and upload their information in minutes
- **Smart Caching**: Patient information is stored securely in Appwrite's database, eliminating the need to re-enter data for future appointments
- **Unlimited Appointments**: No restrictions on the number of appointments a patient can schedule
- **Intuitive Date Picker**: Easy-to-use interface for selecting appointment dates and times
- **Document Upload**: Ability to upload identification documents during registration

### Healthcare Provider Features:
- **Admin Dashboard**: Comprehensive view of all scheduled, pending, and canceled appointments
- **Appointment Management**: Accept or cancel appointments with a single click
- **Real-time Statistics**: Live counts of appointment statuses
- **Customizable Physician List**: Easily update the roster of available doctors and physicians


## 🚀 Getting Started
### For Healthcare Providers (Admin Access)

**IMPORTANT: To view the appointment you just scheduled as a patient, you MUST access the admin dashboard.**

1. **Access the Admin Dashboard**
   - On the home page, locate and click the green **"ADMIN"** button in the top right corner
   - You will be prompted to enter a passkey

2. **Enter the Passkey**
   - **Enter: `123456`**
   - Click "Access Admin" or press Enter
   - *Note: In a production environment, this would be a one-time password (OTP) sent to the healthcare provider's email or phone for authentication. For demonstration purposes, a static passkey is used.*

3. **View Your Scheduled Appointment**
   - Once logged in, you'll immediately see the admin dashboard
   - Your newly scheduled appointment will appear in the appointments table
   - The dashboard displays:
     - **Statistics**: Total scheduled, pending, and canceled appointments
     - **Appointments Table**: All appointments with patient names, status, date/time, and assigned doctor

4. **Manage Appointments**
   - For each appointment in the table, you can:
     - **Schedule/Confirm**: Click the **green calendar icon** to confirm a pending appointment
     - **Cancel**: Click the **red X icon** to cancel an appointment
   
5. **Schedule or Cancel Actions**
   - When you click an action button, a modal will appear
   - **To Schedule**: 
     - Confirm the appointment details
     - Optionally add scheduling notes
     - Click "Schedule Appointment"
   - **To Cancel**:
     - Enter a cancellation reason (required)
     - Click "Cancel Appointment"
   - The appointment status will update immediately in the table

---

## 🔄 Complete User Flow Example

To see the full application in action:

1. **Step 1**: Go to the home page and click "Get Started"
2. **Step 2**: Fill in patient information and schedule an appointment
3. **Step 3**: Return to the home page
4. **Step 4**: Click the green **"ADMIN"** button
5. **Step 5**: Enter passkey `123456`
6. **Step 6**: View your scheduled appointment in the admin dashboard
7. **Step 7**: Try scheduling or canceling the appointment to see real-time updates

This demonstrates the complete patient-to-provider workflow that healthcare facilities would use in production.

---

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** - React framework with App Router for server-side rendering and optimal performance
- **TypeScript** - Type-safe development for better code quality and developer experience
- **Tailwind CSS** - Utility-first CSS framework for rapid UI development
- **shadcn/ui** - High-quality, accessible component library built on Radix UI

### Backend & Database
- **Appwrite** - Open-source backend-as-a-service platform providing:
  - Database for storing patient and appointment data
  - Authentication system
  - File storage for identification documents
  - Server-side SDK for secure operations

### Additional Libraries
- **React Hook Form** - Efficient form management with validation
- **Zod** - TypeScript-first schema validation
- **TanStack Table** - Powerful table component for the admin dashboard

---

### Prerequisites
- Node.js 18+ installed
- An Appwrite account (free tier available at [appwrite.io](https://appwrite.io))(You will need to set up all routing in appwrite in order for this project to work properly if you need any help email me at uzomaworks123@gmail.com)
- Git installed on your machine

### Installation

1. **Clone the repository**
```bash