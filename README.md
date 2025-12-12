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

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ installed
- An Appwrite account (free tier available at [appwrite.io](https://appwrite.io))(You will need to set up all routing in appwrite in order for this project to work properly if you need any help email me at uzomaworks123@gmail.com)
- Git installed on your machine

### Installation

1. **Clone the repository**
```bash