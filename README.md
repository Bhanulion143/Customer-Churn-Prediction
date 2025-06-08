# Customer-Churn-Prediction
# AI Playground 🚀

A React-based dashboard featuring multiple machine learning demos:
- Stock Price Prediction
- Handwritten Digit Recognition (MNIST)
- Customer Churn Analysis

![React](https://img.shields.io/badge/React-18.2+-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-3178C6)
![Vite](https://img.shields.io/badge/Vite-4.0+-646CFF)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-4.0+-FF4154)



## Features
- **Multi-Page Dashboard**:
  - Stock price forecasting
  - Real-time digit recognition (MNIST CNN)
  - Customer churn risk analysis
- **Modern UI**:
  - ShadCN UI components
  - Responsive design
- **State Management**:
  - TanStack Query for data fetching
  - Client-side routing (React Router)
- **Error Handling**:
  - 404 page for invalid routes
  - Toast notifications

## Tech Stack
| Frontend               | State Management      | UI Toolkit           |
|------------------------|-----------------------|----------------------|
| React 18 + TypeScript  | TanStack Query v4     | ShadCN UI            |
| Vite (Build Tool)      | React Router v6       | Tailwind CSS         |

Project Structure
text
ai-playground/
├── src/
│   ├── components/         # Reusable UI components
│   │   └── ui/            # ShadCN components
│   ├── pages/             # Route components
│   │   ├── Index.tsx      # Main dashboard
│   │   ├── DigitRecognition.tsx
│   │   ├── CustomerChurn.tsx
│   │   └── NotFound.tsx
│   ├── App.tsx            # Root component (this file)
│   └── main.tsx           # Entry point
├── public/
│   └── screenshots/       # App previews
└── README.md

Available Routes
Route	Description
/	Home dashboard
/digit-recognition	MNIST digit classifier
/customer-churn	Churn prediction analysis
* (Catch-all)	404 Not Found page
