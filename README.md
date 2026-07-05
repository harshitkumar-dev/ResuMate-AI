# ResuMate AI

ResuMate AI is an AI-powered resume builder that helps users create professional and modern resumes effortlessly using the Gemini AI API. Users can customize resume templates, change accent colors, upload profile images, and build resumes tailored for job applications.

---

## Features

* AI-powered resume generation using Gemini AI API
* User authentication (Signup/Login)
* Multiple modern resume templates
* Accent color customization
* Profile image upload using ImageKit Private API
* Responsive and modern UI
* Easy resume editing and customization
* Secure user authentication and data handling
* Can share Resume
* Print to PDF

---

## Tech Stack

### Frontend

* React.js
* Vite
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### APIs & Services

* Gemini AI API
* ImageKit Private API

---

## Installation

### Clone the repository

```bash
git clone https://github.com/harshitkumar-dev/ResuMate-AI.git
cd ResuMate-AI
```

---

## Setup Frontend

```bash
cd client
npm install
```

### Run frontend development server

```bash
npm run dev
```

### Build frontend for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

---

## Setup Backend

```bash
cd server
npm install
```

### Run backend server

```bash
npm start
```

### Run backend in development mode

```bash
npm run server
```

---

## Environment Variables

Create a `.env` file inside the `server` folder and add:

```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key

OPENAI_API_KEY=your_gemini_api_key
OPENAI_BASE_URL=https://generativelanguage.googleapis.com/v1beta/openai/
OPENAI_MODEL=gemini-2.5-flash

IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

---

## Repository

[ResuMate AI GitHub Repository](https://github.com/harshitkumar-dev/ResuMate-AI)
---

## Future Improvements

* More resume templates
* Dark mode support

---

## Author

Harshit Kumar

---

## License

This project is licensed under the MIT License.
