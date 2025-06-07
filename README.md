# 🌙 LunaChatbot — Intelligent Food Ordering Assistant

**LunaChatbot** is a smart, conversational food ordering system built using **Dialogflow ES**, **FastAPI**, **Python**, and **MySQL**  seamlessly integrated into a custom frontend webpage. Designed to handle real-time food orders, modifications, and tracking via natural conversation, Luna brings the magic of Tamil-inspired cuisine to life through a chatbot experience.

![Screenshot 2025-06-05 165726](https://github.com/user-attachments/assets/75421549-4559-4b84-82df-1e08bfc11da5)


---

## 🚀 Tech Stack

- **Dialogflow ES** – NLP engine for intent recognition  
- **Python** – Core logic and backend processing  
- **FastAPI** – Lightweight ASGI-based webhook server  
- **MySQL** – Persistent database for menu and orders  
- **Custom Frontend Webpage** – Embedded chatbot interface for real users  
- **Ngrok/Render/Vercel** – For local/public webhook exposure

---

## 📦 Features

- ✅ Place new orders with multiple food items and quantities  
- ➕ Add/remove items from ongoing orders  
- 🔍 Track active orders by ID  
- ❌ Cancel or modify specific items  
- 🌐 Web-based chatbot interface (embedded via iframe or Dialogflow Web Demo)  
- 🍱 Tamil cuisine menu: Poori Masala, Mini Oothappam, Mango Panakam, and more  

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/lunachatbot.git
cd lunachatbot
````

### 2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Up MySQL Database

* Run `menu.sql` to seed food menu
* Ensure your DB credentials match those in `db_helper.py` or `.env`

### 5. Run the FastAPI Server

```bash
uvicorn main:app --reload
```

---

## 🌐 Web Integration

LunaChatbot is embedded into a **simple static webpage** using Dialogflow’s Web Demo snippet or iframe-based integration. Users can interact with the chatbot on your website just like a live chat assistant.

> You can customize the page's styling, greetings, and user flow as per your brand.

---


## 💬 Example User Commands

> “I want 2 mini oothappams and 1 mango panakam”
> “Can you track my order?”
> “Remove poori masala from my order”
> “Add 1 vegetable biryani and 2 mango panakams”

---

## 📸 Screenshots

![Screenshot 2025-06-05 165627](https://github.com/user-attachments/assets/a2814c9c-4561-4770-9b73-a049473e079f)

![Screenshot 2025-06-05 165726](https://github.com/user-attachments/assets/a1cbca5f-8e16-4d30-96af-6904365074eb)

![Screenshot 2025-06-05 163323](https://github.com/user-attachments/assets/4e61bd7a-1bb2-4993-9ad2-237132907889)



---

## 🧠 Credits

Built with ❤️ by Naresh B A
Inspired by the flavors of Tamil Nadu and powered by conversational AI.

---

## 📜 License

MIT License — open for learning, forking, and contribution.


