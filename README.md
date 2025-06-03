# Student Management Frontend

Ye simple frontend hai jo aapke Flask backend se data fetch karta hai aur student ko add karne ki facility deta hai.

---

## Files

- `index.html` — Web page jahan form aur student list dikhai deti hai
- `main.js` — JavaScript file jo backend API se baat karti hai

---

## Kaise Use Karein

1. **Open index.html:**

   - Bas `index.html` file ko apne browser me double-click karke open karo
   - Ya agar VS Code use karte ho to Live Server extension se run karo

2. **Student Add Karna:**

   - Form me ID, Name aur Age daalo
   - "Add" button dabao, student backend me add ho jayega

3. **Student List Dekhna:**

   - "Load Students" button dabao
   - Neeche table me backend se sab students aa jayenge

---

## Important

- Backend Flask app ko pehle chalana zaruri hai (default port 5000)
- Frontend JavaScript me URL `http://localhost:5000/students` set hai, agar backend kisi aur address pe ho to wahan change karna padega
- Browser me agar CORS error aaye to backend me `flask-cors` enable karna padega (already included hai)

---

## Author

Sujeet Kushwaha
