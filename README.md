The provided project README outlines a comprehensive social media application built with modern technologies such as React, Appwrite, Tailwind CSS, and TypeScript. Here's a summary and key highlights:

---

### **Project Overview**
This project is a **Social Media Application** with robust features, focusing on user interaction and seamless performance. It incorporates user authentication, profile management, post creation/editing, and real-time data fetching. The application is designed to provide a responsive and visually appealing UI with modern styling.

---

### **Key Features**
1. **Authentication System**: Secure and user-friendly login and sign-up.
2. **Post Management**:
   - Create, edit, like, and save posts.
   - Dedicated pages for managing saved and liked content.
3. **User Interaction**:
   - Explore posts and other user profiles.
   - Detailed post pages with related content.
4. **Responsive UI**:
   - A mobile-app feel with a bottom navigation bar.
5. **Optimized Performance**:
   - Integration of **React Query** for efficient data fetching.
   - Backend powered by **Appwrite** for seamless database and authentication services.
6. **Customizable Profiles**: View and update user details.

---

### **Tech Stack**
- **Frontend**: React.js, Tailwind CSS, Shadcn
- **Backend as a Service (BaaS)**: Appwrite
- **State Management**: React Query (Tanstack Query)
- **Type Safety**: TypeScript

---

### **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/adrianhajdin/social_media_app.git
   cd social_media_app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables in a `.env` file:
   ```plaintext
   VITE_APPWRITE_URL=
   VITE_APPWRITE_PROJECT_ID=
   VITE_APPWRITE_DATABASE_ID=
   VITE_APPWRITE_STORAGE_ID=
   VITE_APPWRITE_USER_COLLECTION_ID=
   VITE_APPWRITE_POST_COLLECTION_ID=
   VITE_APPWRITE_SAVES_COLLECTION_ID=
   ```
   Replace placeholders with your **Appwrite** credentials.
4. Run the development server:
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

### **Tutorial and Community**
- The project is accompanied by an in-depth tutorial on the **JavaScript Mastery** YouTube channel.
- For troubleshooting and community support, join the active **Discord Community** with 27k+ members.

---

### **Snippets and Reusability**
- **Reusable Components**: Shared CSS and utility classes in `globals.css`.
- **Constants**: Modular navigation links and settings in `constants.index.ts`.

---

This project serves as a practical resource for developers looking to build feature-rich web applications. If you need help customizing or extending this app, let me know!