[Visit The Live Website](https://code-help-blogs.vercel.app/)


# 📘 Blog Website

A responsive and theme-enabled blog website built using **React**, **JavaScript**, and **Tailwind CSS**, which fetches data from an external API and displays blog posts with support for **pagination**, **routing**, and **dark mode**.

---

## 🚀 Features

- Fetches blog data via API using **Axios**
- Supports **light/dark mode** with local storage preference
- **Multiple pages** using **React Router**
- **Pagination** for easy navigation
- Dynamic content filtering by **category** and **tags**
- Responsive design with clean UI
- Smooth navigation using **ScrollToTop** and loading **spinners**

---

## 🧱 Project Structure

- `index.js`: App entry point, renders `App` inside context provider  
- `App.js`: Main logic, handles theme, data fetch, and routing  
- `AppContext.js`: Manages global state (theme, loading, posts, pages)  
- `index.css`: Custom styles and Tailwind setup  

### 🔧 Components

- `Header`: Top bar with theme switcher  
- `Posts`, `Pagination`, `BlogDetails`: UI for posts and navigation  
- `Spinner`, `ScrollToTop`: UX enhancements  

---

## 📄 Pages

- **Home**: Lists all blog posts with pagination  
- **Category**: Shows posts by selected category  
- **Tag**: Filters posts by tag  
- **Blog Page**: Full post details with related content  

---

## 🛠 Technologies Used

- React  
- JavaScript  
- Tailwind CSS  
- Axios  
- React Router  
- use-local-storage  
- React Icons  

---

## 💡 Theme Handling

Users can toggle between light and dark mode. Theme preference is saved using **local storage** and managed through **React Context**.

---

## 📦 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/blog-website.git

# Navigate to the project folder
cd blog-website

# Install dependencies
npm install

# Start the development server
npm start
