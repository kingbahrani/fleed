# 🚀 fleed

My personal blog built with [Hugo](https://gohugo.io/) – a place where I write about classic everything

> 🌐 Live at: [https://fleed.ir](https://fleed.ir)

---

## ⚙️ Built With

- **[Hugo](https://gohugo.io/)** – The world's fastest static site generator.
- **[PaperMod](https://github.com/adityatelange/hugo-PaperMod)** – A clean, fast, and responsive Hugo theme.

---

## 📁 Project Structure

```
.
├── content/                # All your blog posts
│   └── posts/              # Markdown files live here
├── static/                 # Images, CSS, and other static assets
├── themes/                 # Hugo themes (PaperMod)
├── hugo.toml               # Main configuration file
└── README.md              # This file
```

---

## 🧑‍💻 Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kingx87/fleed.git
   cd fleed
   ```

2. **Start the Hugo development server (with drafts enabled):**
   ```bash
   hugo server -D
   ```

3. **View your site:**
   Open your browser and go to `http://localhost:1313`

4. **Build for production:**
   ```bash
   hugo
   ```
   The static site will be generated in the `public/` folder.

---

## 📝 Adding a New Post

```bash
hugo new posts/your-post-name/index.md
```

Place your images inside the same folder (e.g., `content/posts/your-post-name/`).

---

## 🖼️ Adding Images & Captions

Use Hugo's built-in `figure` shortcode for images with captions:

```go
{{< figure src="imageq.jpg" alt=" alt text " caption="caption text " link="https://whatever.com" >}}
```

---

## 👤 Author

**kingbahrani**

- GitHub: [@kingbahrani](https://github.com/kingbahrani)
- Website: [fleed.ir](https://fleed.ir)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
