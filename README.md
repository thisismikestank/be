# be

# 🌟 WholeSelf (MVP)

_A human-centered portfolio platform to showcase who you are — not just what you do._

---

## ✨ Project Vision

WholeSelf helps people present their **multidimensional identities** by combining career highlights, personal passions, life roles, values, and reflections into a modular, shareable profile.

This MVP focuses on:
- Modular profile builder with customizable content blocks
- Core values + alignment tags
- Public, shareable profile page
- Basic privacy controls

We aim to create a space for authentic self-expression — beyond resumes, beyond LinkedIn, beyond the performance game.

---

## 💻 Tech Stack

- Frontend: React + Tailwind CSS (via Bolt.new)
- Backend: Node.js (simple CRUD API or mock data store)
- Hosting: Bolt.new environment (expandable to Vercel/Netlify later)

---

## 🏗 Project Structure

/src
/components → reusable React components (blocks, editor, renderer)
/pages → routed pages (create, profile, etc.)
/styles → Tailwind CSS + custom styles
/data → mock or local data for testing
/server
index.js → Node.js backend with basic CRUD routes


---

## 🚀 MVP Features

✅ Modular profile builder (About Me, Career, Passions, Life Roles, Projects, Reflections)  
✅ Core values + alignment tags  
✅ Public profile renderer at `/profile/:username`  
✅ Per-block visibility (public/private)  
✅ Shareable public link

---

## 🔧 Setup & Run (Local or Bolt.new)

1️⃣ Clone the repo or start a new Bolt.new project
git clone https://github.com/your-username/wholeself-mvp.git
cd wholeself-mvp


2️⃣ Install dependencies

npm install


3️⃣ Start the dev server

npm run dev


4️⃣ Access frontend and backend in Bolt.new or localhost

---

## 📅 Roadmap

### Phase 1
- [x] Project scaffolding + routing
- [x] Profile data model + local storage
- [x] Basic CRUD backend (or in-memory)

### Phase 2
- [ ] Modular block editor + reorder logic
- [ ] Public profile rendering
- [ ] Core values/tag system

### Phase 3
- [ ] Privacy controls
- [ ] Design polish + responsive layout
- [ ] Demo-ready version

---

## 🌿 Future Directions

- User authentication
- Media uploads + richer embeds
- Discovery/matching features
- Federated architecture (ActivityPub or similar)
- Community-building + mentorship modules

---

## 🤝 Contributing

Pull requests welcome! Please open an issue to discuss feature ideas or improvements.

---

## 📄 License

MIT License © 2025 Michael Stankiewicz

---

## ✉ Contact

Michael Stankiewicz  
m.stank.mi@gmail.com  
[LinkedIn](https://linkedin.com/in/mikestank)


