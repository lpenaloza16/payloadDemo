# Next.js + Payload CMS

🚀 Experimenting with Next.js templating and integrating the headless CMS [Payload](https://payloadcms.com/).

## 📌 Features
- Next.js for frontend templating  
- Payload CMS as the backend  
- API-driven content management  
- Server-side rendering (SSR) and static site generation (SSG) support  

## 🛠 Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

### 2️⃣ Install Dependencies  
```bash
npm install
```

### 3️⃣ Setup Payload CMS  
Ensure you have MongoDB running locally or use a cloud database. Update your `.env` file with the database URL:  

```ini
MONGO_URL=mongodb://localhost:27017/payload
PAYLOAD_SECRET=your-secret-key
```

### 4️⃣ Start Development Server  
```bash
npm run dev
```

## 📂 Project Structure  
```
/payload         # Payload CMS config
/pages          # Next.js pages
/components     # Reusable UI components
/public         # Static assets
```

## 🚀 Deployment  
You can deploy this project on **Vercel**, **Netlify**, or any Node.js server. Make sure to configure your environment variables properly.

## 📜 License  
This project is open-source under the [MIT License](LICENSE).  

---

Made with ❤️ using Next.js & Payload!

