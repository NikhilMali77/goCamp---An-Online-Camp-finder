# 🏕️ goCamp

goCamp is a full-stack web application inspired by YelpCamp. It allows users to discover, create, and review campgrounds. The app integrates user authentication, image uploads, and map-based location services.

## 🚀 Features

- User authentication and authorization
- Create, edit, and delete campgrounds
- Upload campground images using Cloudinary
- View campgrounds on an interactive map using Mapbox
- Leave reviews on campgrounds
- Responsive EJS templating
- Flash messages for user feedback
- Clean and organized UI

## 🛠️ Tech Stack

- **Frontend:** EJS, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose)
- **Image Storage:** Cloudinary
- **Map Services:** Mapbox
- **Authentication:** Passport.js (Local Strategy)
- **Other Tools:** Express-session, connect-flash, method-override

## 📸 Screenshots

_Add some screenshots here if available._

## 🔧 Setup Instructions

### 1. Clone the Repository

``` bash
git clone https://github.com/yourusername/goCamp.git
cd goCamp
```

### 2. Install Dependencies

<pre><code>npm install
</code></pre>

### 3. Setup Environment Variables

Create a `.env` file in the root directory and add the following:

```bash
DATABASE_URL=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
MAPBOX_TOKEN=your_mapbox_token
SESSION_SECRET=your_secret_key
</code></pre>
```

### 4. Run the App

<pre><code>npm start
</code></pre>

Go to: `http://localhost:3000`

> Ensure you add the required `.env` variables to the platform's config.

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

### 🙌 Made with ❤️ by [Your Name]
