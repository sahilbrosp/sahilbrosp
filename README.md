# Sahil Sabale - Formal Portfolio & CV

A clean, formal, high-legibility portfolio and curriculum vitae website designed for software engineers. Pre-configured for seamless deployment to **Netlify**.

---

## 📁 Project Structure

```text
Portfolio/
├── index.html        # Semantic HTML5 portfolio markup & Netlify form
├── styles.css        # Formal monochrome/slate styles + dark/light mode + print styling
├── script.js         # Theme toggle, clipboard email copy, active scroll-spy
├── netlify.toml      # Netlify deployment configuration & security headers
├── README.md         # Deployment & customization guide
└── resume.pdf        # (Optional) Drop your real PDF resume here
```

---

## 🛠️ How to Customize Your Portfolio

Open [index.html](file:///c:/Users/Sahil%20Sabale/OneDrive/Desktop/Projects/Portfolio/index.html) in your editor and update the following sections:

1. **Header & Intro (`hero-section`)**:
   - Update your name, job title, and brief summary.
   - Replace `sahilsabale@example.com` with your real email.
   - Replace the social links for **LinkedIn** and **GitHub** with your actual profile URLs.
2. **About Section (`#about`)**:
   - Personalize your professional background, current status, and languages.
3. **Work Experience (`#experience`)**:
   - Update companies, roles, dates, bulleted achievements, and technology tags.
4. **Projects (`#projects`)**:
   - Replace the project names, descriptions, GitHub repository URLs, and live demo links with your own work.
5. **Technical Skills (`#skills`)**:
   - Add or remove programming languages, frameworks, databases, and tools to match your tech stack.
6. **Contact Information (`#contact`)**:
   - Update your verified profile handles (LinkedIn, GitHub, LeetCode, X/Twitter).
   - The contact form is already pre-configured with `data-netlify="true"`. When someone submits a message on your deployed Netlify site, you will receive it directly in your Netlify dashboard!
7. **Resume Download**:
   - Place your exported PDF resume into this folder named `resume.pdf`.

---

## 🌐 Deploying to Netlify (3 Easy Methods)

### Method 1: Netlify Drop (Instant Drag-and-Drop — 30 Seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop) (log in or sign up for a free Netlify account).
2. Open your File Explorer to:
   `c:\Users\Sahil Sabale\OneDrive\Desktop\Projects\Portfolio`
3. Drag the entire `Portfolio` folder and drop it into the upload box on Netlify.
4. **Done!** Netlify will instantly give you a live production URL (e.g. `https://sahil-portfolio.netlify.app`).

---

### Method 2: Git & GitHub Integration (Recommended for Continuous Updates)
1. Initialize a git repository in this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial formal portfolio commit"
   ```
2. Create a new repository on [GitHub](https://github.com/new) (e.g., `portfolio`).
3. Push your code to GitHub:
   ```bash
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
4. Log into [Netlify](https://app.netlify.com), click **"Add new site"** &rarr; **"Import an existing project"** &rarr; select **GitHub**.
5. Select your `portfolio` repository.
6. Leave the build settings as default (Publish directory: `.`), and click **Deploy**.
7. Every time you push changes to GitHub, Netlify will automatically update your live site!

---

### Method 3: Netlify CLI
Run the following in your terminal inside this directory:
```bash
npx netlify deploy --prod
```
Follow the interactive prompts to log into Netlify and select the current directory (`.`) to publish.

---

## 💻 Local Preview
To preview locally on your machine, simply double-click `index.html` to open it in your browser, or run a lightweight local dev server:
```bash
npx serve .
```
