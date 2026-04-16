# 📚 CourseVault — Personal Course Organizer

A 4-page, fully responsive Personal Course Organizer website built with semantic HTML5 and an external CSS file. Designed for deployment on GitHub Pages.

---

## 📁 Project Structure

```
course-organizer/
├── index.html          ← Home page
├── courses.html        ← My Courses (with data table)
├── add-course.html     ← Add Course (complete form)
├── contact.html        ← Contact Us (form + info)
├── css/
│   └── style.css       ← External stylesheet (unified theme)
└── README.md
```

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in.
2. Click **New repository**.
3. Name it `course-organizer` (or any name you prefer).
4. Make it **Public**.
5. Click **Create repository**.

### Step 2 — Upload the Files
**Option A — GitHub Web Interface (easiest):**
1. Inside the new repo, click **Add file → Upload files**.
2. Drag and drop the entire `course-organizer/` folder contents (all HTML files + the `css/` folder).
3. Click **Commit changes**.

**Option B — Git CLI:**
```bash
cd course-organizer
git init
git add .
git commit -m "Initial commit: CourseVault site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/course-organizer.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. In your repo, go to **Settings → Pages**.
2. Under **Source**, select `Deploy from a branch`.
3. Choose branch: `main`, folder: `/ (root)`.
4. Click **Save**.

### Step 4 — Access Your Live Site
After ~60 seconds your site is live at:
```
https://YOUR_USERNAME.github.io/course-organizer/
```

---

## ✅ Features Checklist

| Feature                        | Status |
|-------------------------------|--------|
| 4 pages (Home, Courses, Add, Contact) | ✅ |
| Semantic HTML (header, nav, main, section, footer) | ✅ |
| Navigation linking all pages  | ✅ |
| Course table with 6 sample entries | ✅ |
| Complete Add Course form      | ✅ |
| External CSS only             | ✅ |
| Unified color theme           | ✅ |
| Styled navigation bar         | ✅ |
| Styled table & form           | ✅ |
| Responsive layout (mobile)    | ✅ |
| Hover effects & transitions   | ✅ |
| GitHub Pages ready            | ✅ |
