# 🎬 Filmy Gyaan: The Ultimate Bollywood AI Quiz

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Now-FFD700?style=for-the-badge&logo=firebase)](https://filmy-gyaan-a3351.web.app)
[![Powered By](https://img.shields.io/badge/AI-Gemini%20API-4285F4?style=for-the-badge&logo=google)](https://deepmind.google/technologies/gemini/)

**Filmy Gyaan** is an immersive, single-page web application that blends Bollywood nostalgia with cutting-edge AI. It features a dynamic quiz engine, creative AI writing tools, and fun mini-games, all wrapped in a classic cinema aesthetic.

**🌟 Live Demo:** [https://filmy-gyaan-a3351.web.app](https://filmy-gyaan-a3351.web.app)

## ✨ Blockbuster Features

This isn't just a quiz; it's a full Bollywood experience powered by **Google Gemini**:

* **🧠 Dynamic AI Quiz:** Questions are fetched live using the Gemini API, ensuring fresh content every time you play.
* **🤖 AI Critic Reviews:** Get roasted or praised by an AI "Film Critic" in Hinglish based on your score.
* **🎥 The Casting Director:** Enter your name and a quirk, and the AI will cast you in a fictional blockbuster with a plot and role description.
* **✍️ Filmy Writer:** Turn boring real-life situations (like "asking for a raise") into dramatic, over-the-top Bollywood dialogues.
* **💊 The Filmy Pharmacist:** Feeling down? The AI "Doctor" prescribes a Bollywood movie and song as medicine for your mood.
* **🧩 Emoji Pictionary:** Guess the movie title based on a sequence of AI-generated emojis.
* **🎨 Cinematic UI:** Fully responsive design with "film strip" borders, spotlight animations, and a rich red-and-gold palette.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Styling:** Tailwind CSS (via CDN)
* **AI Logic:** Google Gemini API (LLM)
* **Hosting:** Firebase Hosting (Serverless)
* **Icons/Fonts:** FontAwesome, Google Fonts (Cinzel, Rozha One)

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/IamSmitChitroda/Filmy-Gyaan.git
    cd Filmy-Gyaan
    ```

2.  **Open the project:**
    * Simply open `index.html` in your web browser.
    * **Recommended:** Use the "Live Server" extension in VS Code for the best experience.

3.  **API Key Setup:**
    * The project currently uses a demo key. For production, replace the `apiKey` variable in `index.html` with your own key from [Google AI Studio](https://aistudio.google.com/).

## ☁️ Deployment (Firebase)

This project is configured for **Firebase Hosting**.

1.  **Install Firebase CLI:**
    ```bash
    npm install -g firebase-tools
    ```

2.  **Login & Init:**
    ```bash
    firebase login
    firebase init
    # Select 'Hosting', choose your project, and set public directory to '.' (current directory)
    ```

3.  **Deploy:**
    ```bash
    firebase deploy
    ```


## 🤝 Contributing

Got a "Superhit" idea? Contributions are welcome!
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Made with ❤️, 🍿, and Code by [Smit Chitroda](https://github.com/IamSmitChitroda)*