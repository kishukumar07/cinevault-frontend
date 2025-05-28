
# 🎬 CineVault Frontend

A responsive and user-friendly frontend application for the [Movie Store API](https://github.com/your-username/movie-store-api), built using HTML, CSS, and JavaScript. CineVault allows users to browse, search, filter, sort, and paginate movie data fetched from a RESTful backend.

---

## 🚀 Features

- 🎞️ Display movies from the backend API
- 🔍 Search by title
- 🎯 Filter by title and rating
- 📊 Sort results by any field (e.g., title, rating)
- 📄 Pagination for large datasets
- 📱 Fully responsive layout
- ⚠️ Error and loading state handling

---

## 🛠️ Tech Stack

- HTML
- CSS (or Tailwind/Bootstrap if applicable)
- JavaScript (Vanilla or with framework)
- Fetch API / Axios (for HTTP requests)
- REST API powered by [Node.js, Express, MongoDB](https://github.com/your-username/movie-store-api)

---

## 📂 Project Structure

```
cinevault-frontend/
│
├── index.html
├── /css
│   └── styles.css
├── /js
│   └── app.js
├── /assets
│   └── images/
└── README.md
```

> If using a framework like React or Vue, update the structure accordingly.

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cinevault-frontend.git
cd cinevault-frontend
```

### 2. Run the Frontend

- If using plain HTML/CSS/JS, open `index.html` with **Live Server** or your preferred method.
- If using a bundler or framework:

```bash
npm install
npm start
```

### 3. Connect Backend

Make sure your [Movie Store API](https://github.com/your-username/movie-store-api) is running on `http://localhost:5000` (or your deployed URL).

---

## 🌐 API Usage

All movie data is fetched from:

```
GET /movies
GET /movies/:id
```

### Query Parameters:

| Parameter | Description                         |
|-----------|-------------------------------------|
| `q`       | Search by movie title               |
| `title`   | Filter by exact title               |
| `rating`  | Filter by rating                    |
| `sortBy`  | Sort results by a field (e.g. rating) |
| `page`    | Page number for pagination          |
| `limit`   | Number of results per page          |

---

## 📸 Screenshots

_Add your UI screenshots here._

---

## 🧪 Future Improvements

- Add movie details page
- Add poster thumbnails
- Add user authentication
- Ratings and reviews support
- Admin dashboard (if needed)

---

## 📄 License

MIT © [Niket_sahu]
