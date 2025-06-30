# 🧭 NavIndoor - Personalized Indoor Navigation for Poornima Institute of Technology

NavIndoor is a smart, interactive, and scalable indoor navigation solution designed specifically for **Poornima Institute of Technology (PIT)**. The project enables students, faculty, and visitors to navigate through campus buildings, departments, labs, and facilities with ease, using real-time location and route guidance.

---

## 🚀 Features

- 🗺️ **Interactive Map of PIT Campus**
- 📍 **Real-Time Indoor Navigation**
- 🧑‍🏫 **Department, Lab, and Room Identification**
- 📱 **Mobile-Friendly Flutter UI**
- 🔄 **Dynamic Pathfinding using Dijkstra’s Algorithm**
- 🌐 **Backend Integration for Admin Data Control**
- 🧑‍🎓 **Personalized Experience for Students and Faculty**

---

## 📌 Use Cases

- **Freshers** locating classrooms or labs.
- **Visitors** finding specific departments or event locations.
- **Faculty** accessing different buildings or facilities quickly.
- **Admins** managing indoor mapping and location data.

---

## 🛠️ Tech Stack

| Technology        | Description                                |
|------------------|--------------------------------------------|
| 💙 Flutter        | Cross-platform front-end mobile application |
| 🐍 Python         | Backend logic and algorithm integration     |
| 🌐 Django / FastAPI | RESTful APIs for map and user data         |
| 📊 SQLite / PostgreSQL | Database for rooms, users, and nodes       |
| 🧭 SVG / Custom Map | Interactive, scalable indoor map UI        |

---

## 🔄 How It Works

1. **User opens the app and selects their current and destination location.**
2. **App computes the shortest path using Dijkstra’s Algorithm.**
3. **Map dynamically displays the route with clear visual instructions.**
4. **Admin panel allows authorized staff to update maps and locations.**

---

## 📂 Project Structure

```

NavIndoor/
├── assets/                 # Map images and icons
├── lib/                    # Flutter main code
│   ├── screens/            # Home, Map, Search
│   ├── services/           # API integration
│   └── widgets/            # Reusable UI components
├── backend/                # Python/Django backend
│   ├── algorithms/         # Dijkstra and path logic
│   └── api/                # Route and room data endpoints
└── README.md               # Project documentation

```

---

## 📸 Screenshots

> _(Add screenshots here for homepage, map view, route display, and admin panel interface)_

---

## 🧪 Future Enhancements

- 🔒 User Login & Role-Based Access
- 📡 BLE or Wi-Fi Based Indoor Positioning
- 🧠 AI-based Smart Suggestions for Paths
- 🌍 Multi-floor Support with Elevators & Stairs
- 🏫 Extendable to Other Campuses or Institutions

---

## 🤝 Contributing

We welcome contributions! Please follow the standard `fork -> feature branch -> pull request` flow. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📃 License

This project is licensed under the [MIT License](LICENSE).

---

## 📞 Contact & Support

> For queries, contact:  
📧 **navindoor.pit@gmail.com**  
🌐 [Poornima Institute of Technology](https://www.poornima.org)

---
