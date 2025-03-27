# EmployWise User Management System

A React-based user management system that integrates with the Reqres API to perform basic user management functions. This application provides authentication, user listing, and user management capabilities.

## 🌟 Live Demo

Visit the live application: [EmployWise User Management](https://strong-treacle-d4724c.netlify.app)

## ✨ Features

- **Authentication**
  - Secure login system
  - Token-based authentication
  - Protected routes

- **User Management**
  - View paginated list of users
  - Edit user details
  - Delete users
  - Search and filter users

- **Modern UI/UX**
  - Responsive design
  - Clean and intuitive interface
  - Real-time feedback
  - Loading states
  - Toast notifications

## 🛠️ Technologies Used

- React 18
- TypeScript
- Tailwind CSS
- React Router DOM
- Axios
- React Hot Toast
- Lucide React (for icons)
- Vite (Build tool)

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm (v9 or higher)

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd employwise-assignment
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

5. **Preview production build**
   ```bash
   npm run preview
   ```

## 🔑 Environment Variables

No environment variables are required as the application uses the public Reqres API.

## 📱 Usage

1. **Login**
   - Use the following credentials:
     - Email: eve.holt@reqres.in
     - Password: cityslicka

2. **User Management**
   - View users in a paginated list
   - Search users by name or email
   - Edit user details using the edit button
   - Delete users using the delete button
   - Navigate through pages using the pagination controls

## 🏗️ Project Structure

```
src/
├── api/          # API integration and axios configuration
├── components/   # Reusable components
├── pages/        # Page components
├── types/        # TypeScript type definitions
└── main.tsx      # Application entry point
```

## 🔒 Security Features

- Protected routes using React Router
- Token-based authentication
- Secure token storage in localStorage
- Automatic redirect to login for unauthorized access

## 🌐 API Integration

The application integrates with the Reqres API (https://reqres.in/):

- POST /api/login - Authentication
- GET /api/users - Fetch users list
- PUT /api/users/{id} - Update user
- DELETE /api/users/{id} - Delete user

## 📱 Responsive Design

The application is fully responsive and works seamlessly across:
- Desktop devices
- Tablets
- Mobile devices

## ⚡ Performance Optimizations

- Lazy loading of routes
- Optimized bundle size
- Efficient state management
- Debounced search functionality

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
