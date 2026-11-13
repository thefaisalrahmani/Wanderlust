# 🌍 Wanderlust – Full-Stack Travel Accommodation Platform

Wanderlust is a full-stack travel accommodation platform that allows users to explore, create, and manage property listings. Users can browse available accommodations, view property details, upload images, and share their experiences through reviews and ratings.

The application provides secure authentication and authorization to ensure that users can manage only their own listings and reviews.

## 🚀 Live Demo

[Visit Wanderlust](https://wanderlust-ki5a.onrender.com)

## ✨ Features

- **User Authentication:** Secure user registration and login functionality.
- **Property Listings:** Browse and explore available accommodation listings.
- **Create Listings:** Authenticated users can create new property listings with images and details.
- **Update & Delete Listings:** Users can edit or delete only their own listings.
- **Image Uploads:** Upload and manage property images.
- **Review & Rating System:** Users can add reviews and ratings to listings.
- **Review Management:** Users can edit or delete only their own reviews.
- **Authorization:** Ownership-based access control to protect user-specific operations.
- **Responsive Interface:** User-friendly interface for a smooth browsing experience.

## 🛠️ Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript
- EJS (Embedded JavaScript Templates)
- Bootstrap

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Authentication & Other Tools**
- Passport.js
- Express-session
- Multer
- Cloudinary
- Git & GitHub

## 📂 Project Structure

```text
Wanderlust/
│
├── controllers/       # Application business logic
├── models/            # MongoDB database models
├── routes/            # Application routes
├── views/             # EJS templates
├── public/            # CSS, JavaScript and static files
├── utils/             # Utility functions
├── middleware.js      # Custom authentication middleware
├── app.js             # Main application entry point
├── cloudConfig.js     # Cloud image configuration
├── schema.js          # Input validation schemas
├── package.json       # Project dependencies
└── .gitignore         # Git ignored files
```

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

**1. Clone the repository**

```bash
git clone https://github.com/thefaisalrahmani/Wanderlust.git
```

**2. Navigate to the project directory**

```bash
cd Wanderlust
```

**3. Install dependencies**

```bash
npm install
```

**4. Configure environment variables**

Create a `.env` file in the root directory and configure the required credentials.

```env
PORT=8080
ATLASDB=your_mongodb_connection_string
SECRET=your_session_secret
```

Add any additional environment variables required by your Cloudinary configuration.

**5. Start the application**

```bash
node app.js
```

Or, if you have Nodemon installed:

```bash
nodemon app.js
```

**6. Open in your browser**

```text
http://localhost:8080
```

## 🔐 Security Features

- Authentication to restrict access to protected routes.
- Authorization to ensure users can modify only their own listings.
- Ownership-based review management.
- Server-side validation of user inputs.
- Environment variables to protect sensitive configuration credentials.

## 🎯 Future Enhancements

- Advanced search and filtering functionality.
- Map integration for property locations.
- Wishlist functionality for saving favourite accommodations.
- AI-powered image moderation to detect inappropriate uploads.
- Online booking and payment integration.

## 👨‍💻 Developer

**Faisal Rahmani**

- GitHub: [@thefaisalrahmani](https://github.com/thefaisalrahmani)
- Project: [Wanderlust](https://github.com/thefaisalrahmani/Wanderlust)
- Live Application: [Visit Website](https://wanderlust-ki5a.onrender.com)

---

⭐ If you find this project interesting, consider giving it a star on GitHub!
