# 🚀 Portfolio Generator

**Automated Full-Stack Portfolio Creation & Deployment**

The **Portfolio Generator** is a full-stack application that automates the end-to-end workflow of creating and deploying personalized portfolio websites. From template selection to live deployment, everything happens in **\~30 seconds** — saving hours of manual effort.

---

## ✨ Features

* 🔧 **Dynamic Portfolio Templates** – Choose and customize with user data
* 📦 **Automated File Generation & Packaging** – Projects zipped on-the-fly
* ☁️ **Cloud Storage Integration** – Store & retrieve via Supabase
* 🔗 **GitHub Automation** – Programmatic repo creation & commits in chunks
* ⚡ **Continuous Deployment** – Auto-connected to Vercel
* 📧 **Email Notifications** – Instant access to repo, live site, and downloads

---

## 🛠️ Tech Stack

* **Frontend Templates:** EJS (Embedded JavaScript)
* **Backend:** Node.js, Express.js
* **Storage:** Supabase
* **Version Control:** GitHub REST API
* **Deployment:** Vercel
* **Notifications:** Nodemailer

---

## 🔄 Workflow

1. **Collect** – User submits info via form
2. **Inject** – Data merged into EJS templates
3. **Generate** – Project folder created dynamically
4. **Compress** – Files zipped for storage
5. **Upload** – ZIP pushed to Supabase
6. **Commit** – Files committed to GitHub in logical chunks
7. **Deploy** – Repo auto-connected & deployed via Vercel
8. **Notify** – Email sent with download link, repo URL, and live portfolio

---

## ⚡ Optimizations

* **Removed `node_modules`** → Reduced project size from **GBs → \~600MB**
* **Efficient Compression** → Faster ZIP creation & uploads
* **Streamlined Cloud Uploads** → Supabase integration for rapid access
* **Automated CI/CD** → GitHub → Vercel pipeline, no manual steps

---

## 📊 Results

* ⚡ **Speed:** Workflow reduced from **hours → 30 seconds**
* 📉 **Resource Efficiency:** Smaller file sizes & faster transfers
* 🌍 **Instant Access:** Users get live portfolio, repo, and code archive instantly

---

## 📬 Example Email Output

* 📂 Supabase ZIP Link
* 🖥️ GitHub Repository Link
* 🌐 Live Portfolio URL

---

## 🚧 Challenges

Automating this complex pipeline was challenging due to:

* Managing large project dependencies
* Orchestrating multiple API calls (Supabase, GitHub, Vercel)
* Maintaining natural commit histories programmatically

---

## ✅ Impact

* **Instant onboarding** for students & developers
* **Scalable & reusable** deployment pipeline
* **Community-friendly** – simplifies professional branding

---

## 📦 Installation (For Local Dev)

```bash
# Clone repo
git clone https://github.com/<your-username>/portfolio-generator.git
cd portfolio-generator

# Install dependencies
npm install

# Set environment variables
cp .env.example .env   # Add Supabase, GitHub, Vercel tokens

# Run server
npm start
```

---

 
 
 
