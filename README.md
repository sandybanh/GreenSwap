# TechNova-2025

# 🌱 GreenSwap

Swipe, match, trade — good for you, better for the planet.  
[View on Devpost](https://devpost.com/software/greenswap-aifrk3?_gl=1*mprxb3*_gcl_au*MTUyMzg2MTM1Ny4xNzU4OTM3NTg5*_ga*ODI0NjU4NzI2LjE3NDAwOTI1ODU.*_ga_0YHJK3Y10M*czE3NTkxNzY3NzQkbzQkZzEkdDE3NTkxNzY3ODIkajUyJGwwJGgw)

🏆 **Winner of the Sustainability Theme at TechNova 2025**  

Think **Tinder meets Facebook Marketplace, powered by sustainability -- plus it's free.**  


---

## 🌱 Inspiration
“One’s trash can be another’s treasure.”

A 2023 report shows that a large portion of the items going into waste are in functional condition; in particular, around **460,000 tons of textiles were discarded in 2018, with 65% of them being reusable**.

Targeting young adult consumers in local areas, GreenSwap encourages people to **trade items they no longer need for something useful**, instead of contributing to landfills. The platform strengthens community connections while promoting **circular economy practices**.

---

## ✨ What It Does
GreenSwap is a web application that allows people to upload used items they wish to exchange.  

- Users sign up with a **username + email**  
- Upload items for trade  
- Swipe on items from other users  
- When there’s a match, both users coordinate pick-up time and location  

This creates a **first-come, first-served system** where locals can save money, reduce waste, and do good for the planet.  

> **In short**: GreenSwap is **Tinder + Facebook Marketplace + Sustainability**.  

---

## 💭 How We Built It
**Frontend**  
- [Next.js 14](https://nextjs.org/) (App Router)  
- [TypeScript](https://www.typescriptlang.org/) for type safety  
- [Tailwind CSS](https://tailwindcss.com/) for styling  
- [Lucide-React](https://lucide.dev/) for icons  
- [Radix-UI](https://www.radix-ui.com/) for low-level components  
- [Framer Motion](https://www.framer.com/motion/) for swipe animations  

**Backend**  
- [Python](https://www.python.org/) with [Flask](https://flask.palletsprojects.com/)  
- [MongoDB Atlas](https://www.mongodb.com/atlas) for storage and retrieval  

---

## 🤔 Challenges We Ran Into
- **Development environment control** — ensuring consistent setups across different machines (dependencies, VSCode configs, etc.)  
- **Backend hurdles** — implementing multiple APIs under hackathon time constraints  
- **Integration** — connecting frontend + backend was harder than expected  
- **Time pressure** — three of the four team members were first-time hackathon participants  

---

## 🎉 Accomplishments We’re Proud Of
- **Database setup** — successfully configured MongoDB Atlas  
- **Frontend visuals** — sleek, intuitive UI with swipe animations  
- **Working MVP** — shipped under intense hackathon conditions  

---

## 📝 What We Learned
- **Adaptation**: learned to debug with unfamiliar tools like Turbopack in Next.js  
- **Teamwork**: communication and time management were key to finishing the project  
- **Resilience**: learned to push through technical roadblocks under pressure  

---

## 💚 What’s Next
- Integrate **Gemini AI** to analyze user preferences  (We did this in Test, by embedding item tags into MongoDB for cosine similarity, but was never fully integrated.)
- We hope to push the **algorithm** we made that learns users' preferences based on type of items that swiped right.
- Add a **tagging system** for better search + matching  
- Implement **chatroom functionality** for seamless communication  

---

## 🛠️ Tech Stack
- **Frontend**: Next.js, TypeScript, Tailwind CSS, Lucide-React, Radix-UI, Framer Motion  
- **Backend**: Flask (Python)  
- **Database**: MongoDB Atlas  

---

## 🚀 Running Locally

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/greenswap.git
cd greenswap
```

### 2. Run frontend
```bash
cd frontend
npm install
npm run dev
```

### 3. Run backend
```bash
cd backend
pip install -r requirements.txt
flask run
```

### Made by Team Lumina: Sandy Banh, Xena Patel, Victoria Gao, Jiamiao Zeng (TechNova 2025)

