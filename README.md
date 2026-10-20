# Mistvale Tea Store 🍃

A modern, premium, e-commerce web application designed for artisanal and estate-grown Indian teas. Built with vanilla HTML, CSS, and JavaScript, featuring a fully responsive layout, robust filtering and search, cart management, simulated backend delivery checks, and performance optimizations.

![Mistvale Home Preview](images/home-section.png)

---

## ✨ Features

- **Rich Product Catalog:** Explore premium black, green, herbal teas, and exclusive gift boxes.
- **Dynamic Filtering & Search:** Filter by category (Black, Green, Herbal, Gifts) and search live through product names and descriptions with a simulated backend API.
- **Interactive Cart & Checkout:** Add products with stock limits, apply discount codes (`WELCOME10`), calculate free shipping thresholds (₹599+), and persist data via `localStorage`.
- **Pincode Delivery Check:** Simulated delivery time estimator based on Indian postal zones.
- **Quick View Modal:** Inspect product details, ratings, and reviews in an accessible modal dialog.
- **Performance Optimized:** Features native lazy loading (`loading="lazy"`), async image decoding, and smooth fade-in transitions.
- **SEO & Accessibility:** Fully responsive design with semantic HTML, ARIA labels, and structured JSON-LD schema markup.

---

## 🛠️ Tech Stack

- **Markup & Styling:** HTML5, CSS3 (Custom properties, Flexbox/Grid)
- **Scripting:** Vanilla JavaScript (ES6+, Promises, LocalStorage, Intersection Observer)
- **Assets:** Custom product photography, web fonts, and optimized images.

---

## 📂 Project Structure

```text
mistvale/
├── index.html          # Main application file (HTML, CSS, and JavaScript)
├── images/             # Product photography and UI assets
│   ├── assam.jpg
│   ├── darjeeling-1.jpg
│   ├── Kashmiri.jpg
│   ├── Masala Chai Blend.jpg
│   ├── greentea.jpg
│   ├── tulsitea.jpg
│   ├── rosetea.png
│   └── teabox.png
├── NOTES.md            # Development notes
└── PROMPTS.md          # Session history and prompt logs
```

---

## 🚀 Getting Started Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/mistvale.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd mistvale
   ```
3. **Open the project:**
   Simply open `index.html` in your preferred web browser, or use a local development server like Live Server in VS Code.

---

## 🌐 Deploying to GitHub Pages

1. Push your repository to GitHub.
2. Go to your repository **Settings** > **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose your `main` branch and the `/ (root)` folder, then click **Save**.
5. Your live site link will appear at the top of the Pages settings once deployed!

---

## 📄 License

This project is open-source and available for educational and portfolio purposes.
