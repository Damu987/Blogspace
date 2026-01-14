# BlogSpace

BlogSpace is a simple and interactive **blog posting web application** built using **HTML, CSS, and Vanilla JavaScript**. It demonstrates how to fetch, display, and create blog posts dynamically using the **Fetch API** and basic DOM manipulation.

This project is designed to showcase **core JavaScript skills** such as working with APIs, handling form submissions, and updating the UI without page reloads.

---

## Features

* Fetches and displays blog posts from an external API
* Displays latest posts dynamically on page load
* Allows users to create new blog posts using a form
* Updates UI instantly without refreshing the page
* Uses Fetch API for GET and POST requests
* Clean and minimal UI structure

---

## Tech Stack

* **HTML5** – Page structure
* **CSS3** – Styling
* **JavaScript (ES6)** – Logic & DOM manipulation
* **API:** JSONPlaceholder (via Scrimba proxy)
* **Version Control:** Git & GitHub

---

## Project Structure

```
blogspace/
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## How It Works

1. On page load, the app fetches blog posts from the API:

   * `GET https://apis.scrimba.com/jsonplaceholder/posts`
   * Displays the first 5 posts

2. Users can submit a new post using the form:

   * Title and body are collected from input fields
   * A `POST` request is sent to the API
   * The new post is added to the top of the blog list

3. The UI updates dynamically using JavaScript without reloading the page.

---

## Key Learnings

* Using Fetch API with GET and POST methods
* Handling form submissions with `preventDefault()`
* Updating the DOM dynamically
* Managing data using JavaScript arrays
* Working with external APIs
* Understanding asynchronous JavaScript

---

## Getting Started

### Prerequisites

* A modern web browser
* Basic knowledge of HTML, CSS, and JavaScript

### Installation

```bash
git clone https://github.com/Damu987/Blogspace.git
cd blogspace
open index.html
```

---

## 📸 Screenshots

*<img width="400" height="400" alt="Image1" src="https://github.com/user-attachments/assets/8bb6d637-999c-4c8f-a8bd-b6f5e1ab62e9" />


---

## Future Enhancements

* Delete and edit blog posts
* User authentication
* Pagination for posts
* Backend integration with a real database
* Improved responsive design

---

## License

This project is licensed under the MIT License.

---

## Author

**Damini S**
Frontend Developer (Fresher)
GitHub: [https://github.com/Damu987](https://github.com/Damu987)

---

⭐ If you like this
