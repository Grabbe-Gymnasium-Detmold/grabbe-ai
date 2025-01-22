# GrabbeAI: A School's Leap into the Future of AI 🚀🎓

Welcome to the official documentation of **GrabbeAI**, the first AI model developed specifically for a school! GrabbeAI is a groundbreaking project implemented at the **Christian-Dietrich-Grabbe-Gymnasium (GGY)** in Detmold, Germany. Its purpose is to revolutionize the way information is accessed and communication is handled for students, teachers, and parents. Fully integrated into the school’s homepage, GrabbeAI serves as a digital assistant for a wide range of tasks, making school life simpler, smarter, and more connected. You can use GrabbeAI directly on it's [own web-app](https://app.grabbe.site) or on the [Grabbe-Gymnasium's homepage](http://www.grabbe-gymnasium.de/#grabbeAI)!

---

## Table of Contents 📝
- [Overview](#overview)
- [Components](#components)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Dataset](#dataset)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Security and Authentication](#security-and-authentication)
- [Setup and Installation](#setup-and-installation)
- [Development Workflow](#development-workflow)
- [Deployment](#deployment)
- [Community and Contribution](#community-and-contribution)
- [Acknowledgments](#acknowledgments)
- [References](#references)
- [License](#license)

---

## Overview 🌟
GrabbeAI is a cutting-edge AI solution, fine-tuned from OpenAI's **GPT-4o mini** model, making it the first school-focused AI implementation of its kind. Officially launched in **January 2025**, it combines the latest advancements in AI with tailored functionalities to meet the unique needs of the Christian-Dietrich-Grabbe-Gymnasium community.
GrabbeAI is the **first-ever school-focused AI model**, officially launched in **January 2025**. It was meticulously designed to meet the needs of the Christian-Dietrich-Grabbe-Gymnasium community, combining the latest advancements in artificial intelligence with a user-centric approach. GrabbeAI simplifies complex communication chains and ensures that relevant information is always just a click away.

### Key Benefits:
- **For Students** 📚: Instant access to timetables, assignments, FAQs, and extracurricular activities.
- **For Teachers** 👩‍🏫: Effortless class management and parent communication.
- **For Parents** 👨‍👩‍👧: Timely updates on their child’s progress, events, and important announcements.

The platform represents a significant step forward in education technology, showcasing how AI can create a better, more efficient learning environment.

---

## Components 🧩
GrabbeAI is built on three foundational components that work seamlessly together:

### Frontend 🌐
The **frontend** delivers a sleek, interactive user interface that is fully responsive and easy to navigate. This part of the system is designed to provide users with a simple yet powerful experience on any device.

🔗 [Frontend Repository](https://github.com/Grabbe-Gymnasium-Detmold/grabbe-ai-website)

#### Highlights:
- **Modern Design**: Developed using **React**, **Vite**, and **TailwindCSS**.
- **Localization**: Multi-language support via **i18next** ensures inclusivity.
- **Engaging Animations**: Powered by **Framer Motion** for smooth, visually appealing interactions.

### Backend 🛠️
The **backend** forms the AI-powered brain of GrabbeAI. It integrates directly with OpenAI's state-of-the-art models to generate intelligent responses and manages all API interactions.

🔗 [Backend Repository](https://github.com/Grabbe-Gymnasium-Detmold/grabbe-ai-backend)

#### Features:
- **Efficient AI Integration**: Leveraging OpenAI for quick and accurate responses.
- **Simple and Secure**: Though it lacks traditional authentication, GrabbeAI employs secure methods to protect sensitive information while remaining user-friendly.
- **Database Support**: Uses **MySQL** to store key data reliably.

### Dataset 📊
The dataset is the cornerstone of GrabbeAI’s ability to answer questions effectively. It includes:
- Detailed FAQs covering school policies, events, and procedures.
- Comprehensive teacher and staff directories.
- Key documents and downloadable resources.

🔗 [Dataset Repository](https://github.com/Grabbe-Gymnasium-Detmold/grabbe-ai-dataset)

---

## Features ✨
GrabbeAI is loaded with features that make it an indispensable tool for the Grabbe-Gymnasium community:

1. **Custom AI Assistance**: Tailored for school-related queries, ranging from timetables to teacher contact details.
2. **Seamless Communication**: Facilitates better interaction between teachers, students, and parents.
3. **Real-Time Information**: Provides instant updates on events, schedules, and announcements.
4. **User-Friendly Interface**: Accessible to users of all technical skill levels.
5. **AI-Powered Insights**: Intelligently answers questions using OpenAI’s advanced models.

---

## Technology Stack 🛠️
The development of GrabbeAI involved a robust stack of modern technologies:

### Frontend:
- **React**: Building dynamic and scalable user interfaces.
- **Vite**: A high-performance build tool.
- **TailwindCSS**: Utility-first CSS for rapid styling.
- **Framer Motion**: Library for animations and transitions.
- **i18next**: Enabling multi-language support.

### Backend:
- **Node.js**: JavaScript runtime for server-side processing.
- **Nitropack**: Framework for fast API responses.
- **MySQL**: Relational database management system.
- **OpenAI API**: Powers AI capabilities.
- **IPinfo**: Provides geolocation data based on IP addresses.

---

## Security and Authentication 🔒
Although GrabbeAI does not implement complex authentication protocols, it ensures security by:
- Using **secure API endpoints**.
- Maintaining user privacy by limiting data access.
- Restricting contributions and interactions to authorized members of the Grabbe-Gymnasium community.

The simplicity of its security framework allows for faster user onboarding while maintaining a high standard of data integrity.

---

## Setup and Installation ⚙️
Getting started with GrabbeAI is straightforward:

### Frontend:
1. Clone the repository:
   ```bash
   git clone https://github.com/Grabbe-Gymnasium-Detmold/grabbe-ai-website.git
   ```
2. Navigate to the directory:
   ```bash
   cd grabbe-ai-website
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```

### Backend:
1. Clone the repository:
   ```bash
   git clone https://github.com/Grabbe-Gymnasium-Detmold/grabbe-ai-backend.git
   ```
2. Navigate to the directory:
   ```bash
   cd grabbe-ai-backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Configure the environment:
   Create a `.env` file with the necessary keys (refer to the backend README).
5. Start the server:
   ```bash
   npm run dev
   ```

---

## Development Workflow 🚧
Development involves these core scripts:

- **Frontend:**
  - `npm run dev`: Starts the development server.
  - `npm run build`: Prepares the application for production.

- **Backend:**
  - `npm run dev`: Starts the API server.
  - `npm run build`: Prepares the backend for deployment.

---

## Deployment 🚀

### Frontend:
1. Build the application:
   ```bash
   npm run build
   ```
2. Deploy the contents of the `dist/` directory to a static hosting provider such as **GitHub Pages** or **Vercel**.

### Backend:
1. Build the API:
   ```bash
   npm run build
   ```
2. Deploy the backend to a cloud service like **DigitalOcean** or **AWS**.

---

## Community and Contribution 🤝
GrabbeAI was developed by the school community, for the school community. Contributions are currently limited to authorized staff and students of Grabbe-Gymnasium. If you are part of the school and would like to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add feature XYZ'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request for review.

---

## Acknowledgments 💖
GrabbeAI was envisioned and brought to life by:
- **Finn Busse**
- **Maximilian von Beck**

Special thanks to the entire Grabbe-Gymnasium community for their support and input during the development process.

---

## References 📚
- **Finn Busse**: Primary developer and visionary.
- **Maximilian von Beck**: Lead backend engineer.

---

## License 📜
This project is the exclusive property of Christian-Dietrich-Grabbe-Gymnasium. Unauthorized use, copying, or distribution is prohibited.

For inquiries or support, contact:
- `grabbeai@finnbusse.de`
- `kontakt@maximilianvonbeck.de`

---
