# DistriFlow Wholesale ERP & CRM

DistriFlow is a full-stack **ERP & CRM system** designed for wholesale and distribution businesses. It manages customers, products, inventory, sales challans, invoices, and CRM follow-ups with role-based access control.

## 🚀 Features

- 🔐 JWT Authentication & Role-Based Access
- 👥 Customer CRM & Follow-ups
- 📦 Product & Inventory Management
- 🔄 Stock IN/OUT & Audit Trail
- 🧾 Sales Challans with Auto Stock Deduction
- 🚫 Negative Stock Prevention
- 🔁 Stock Restoration on Challan Cancellation
- 📄 PDF Invoice Generation
- 📡 REST APIs
- 🐳 Docker Support

## 👤 User Roles

| Role | Access |
|------|--------|
| Admin | Full System Access |
| Sales | CRM & Sales Challans |
| Warehouse | Products & Inventory |
| Accounts | Challans & Invoices |

## 🛠️ Tech Stack

**Frontend        :**   React 19, TypeScript, Tailwind CSS  
**Backend         :**   Node.js, Express.js, TypeScript  
**Authentication  :**   JWT, bcryptjs  
**PDF             :**  jsPDF, jspdf-autotable  
**Tools           :**   Vite, tsx, Docker


##  🐳 Docker Containerization
```text
# Build Docker image
docker build -t distriflow-erp .

# Run container on port 3000
docker run -p 3000:3000 distriflow-erp

# Or launch via docker-compose
docker-compose up --build
```

## 🏗️ Architecture

```
React Frontend
      ↓
REST API
      ↓
Node.js + Express
      ↓
Business Logic
      ↓
CRM | Inventory | Sales | Invoices
```

## 🚀 Running Locally
```
# 1. Install dependencies
npm install

# 2. Copy environment file
cp .env.example .env

# 3. Start development server (Node + Express + Vite on Port 3000)
npm run dev

# 4. Open in browser
http://localhost:3000

```
## 🎥 Project Demo Video

[Watch Project Demo Video](https://drive.google.com/drive/folders/1aEW8BLrs0Y1LP_QtkeJp9v15phehh0Ng?usp=sharing)

## 📄 Project Documentation

[View Project Documentation](https://drive.google.com/drive/folders/1aEW8BLrs0Y1LP_QtkeJp9v15phehh0Ng?usp=sharing)
