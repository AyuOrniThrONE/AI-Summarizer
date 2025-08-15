# AI-Summarizer

A simple web application that generates concise summaries of articles or blogs by simply copy-pasting the content into the input field. The app is powered by the OpenAI GPT API, delivering AI-based summarization quickly and easily.

---

## Live Demo
🔗 **[Click here to try the app](https://ayushbuildaisummarizer.netlify.app/)**

---

## Features
- Paste any article or blog text into an input field and receive a concise summary.
- Lightweight, intuitive, and responsive web interface.
- Powered by OpenAI GPT API.

---

## Getting Started

### Prerequisites
- **Node.js** (v14 or newer) and **npm** installed.
- An **OpenAI API Key**, configured via an environment variable.

### Installation
```bash
git clone https://github.com/AyuOrniThrONE/AI-Summarizer.git
cd AI-Summarizer
npm install
```

### Configuration
1. Create a `.env` file in the project root:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```

2. (Optional) Configure any other environment-specific variables.

### Running the App
#### Development Mode
```bash
npm run dev
```

#### Production Build
```bash
npm run build
npm run serve
```

The app will be accessible at `http://localhost:3000`.

---

## Usage
1. Open the app in your browser.
2. Paste the text of any article or blog into the input field.
3. Click **"Summarize"**.
4. View the generated summary instantly.

---

## Technologies Used
- **Frontend**: JavaScript (Vite, possibly React/Vue/Svelte), Tailwind CSS
- **AI Service**: OpenAI GPT API
- **Build Tools**: Vite, npm

---

## File Structure
```
AI-Summarizer/
│
├── public/              # Static assets
├── src/
│   ├── index.html       # Main HTML template
│   ├── main.js/ts       # Entry point
│   ├── App.vue/jsx/...  # Main app component
│   └── styles/          # CSS, Tailwind config
│
├── .env                 # Environment variables
├── .gitignore
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

---

## Contributing
1. Fork the repository.
2. Create a new branch:  
   ```bash
   git checkout -b feature/my-feature
   ```
3. Commit your changes:  
   ```bash
   git commit -m "feat: add X feature"
   ```
4. Push to your branch:  
   ```bash
   git push origin feature/my-feature
   ```
5. Open a Pull Request.

---

## License
This project is licensed under the **[MIT License](LICENSE)**.

---

## Contact
**Author**: Ayush Prakash Thaware
**GitHub**: [@AyuOrniThrONE](https://github.com/AyuOrniThrONE)
