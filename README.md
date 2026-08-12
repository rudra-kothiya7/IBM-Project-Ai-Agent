# 🌿 Rann Mitra — Smart Rann of Kutch Eco-Tourism & Carrying Capacity Planner

> An AI-powered, single-page eco-tourism assistant for the **Rann of Kutch**, Gujarat, India.  
> Built with HTML, CSS, and JavaScript — powered by the [Groq](https://groq.com) LLM API.

---

## 🗺️ Overview

**Rann Mitra** ("Friend of the Rann") is an agentic AI chatbot that helps travellers plan sustainable, responsible visits to the Rann of Kutch. It internally simulates **five specialist agents** to answer questions about crowd forecasts, eco-friendly itineraries, ecological fragility, artisan communities, and site-impact dashboards — all in one conversational interface.

---

## ✨ Features

| Agent | What it does |
|-------|-------------|
| 📊 **Load Forecast Agent** | Estimates tourist crowding for any Kutch site and date using seasonality, festival calendars, and hotspot data |
| 🗺️ **Itinerary Planner Agent** | Builds multi-day sustainable itineraries mixing famous and offbeat sites, recommending homestays and eco-practices |
| 🌿 **Ecological Carrying Capacity Agent** | Gives qualitative capacity verdicts for fragile sites (Banni Grasslands, Great Rann salt crust, Chhari Dhand, Wild Ass Sanctuary) |
| 🧵 **Artisan & Community Linkage Agent** | Connects tourists to genuine Kutch crafts — Rogan art, Ajrakh printing, Rabari embroidery — and the villages behind them |
| 📋 **Impact Dashboard Agent** | Generates a compact markdown table of Load Level, Ecological Sensitivity & Suggested Actions for major sites |

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- A **Groq API key** — free at [console.groq.com](https://console.groq.com)

### Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/rudra-kothiya7/IBM-Project-Ai-Agent.git
   cd IBM-Project-Ai-Agent
   ```

2. **Open the app**  
   Simply open `rann_mitra.html` in your browser — no build step, no server needed.

3. *(Optional)* **Replace the API key**  
   Edit line ~294 in `rann_mitra.html` and replace the `GROQ_API_KEY` value with your own key:
   ```js
   const GROQ_API_KEY = "your_groq_api_key_here";
   ```

---

## 📁 Project Structure

```
IBM-Project-Ai-Agent/
├── rann_mitra.html   # Main single-page application
├── 1.png             # Project / UI assets
├── 2.png
├── 3.png
├── 4.png
├── 5.png
└── README.md         # This file
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| AI Model | `llama-3.3-70b-versatile` via Groq API |
| Markdown rendering | Custom lightweight JS renderer |
| Hosting | Static — no server required |

---

## 🌍 Key Sites Covered

- **White Desert / Dhordo** — iconic salt flat, peak during Rann Utsav (Nov–Feb)
- **Kalo Dungar (Black Hill)** — highest point in Kutch, panoramic views
- **Banni Grasslands** — biosphere buffer zone, invasive species challenges
- **Chhari Dhand Wetland** — flamingo & migratory bird sanctuary
- **Wild Ass Sanctuary (Little Rann)** — largest wildlife sanctuary in India
- **Nirona, Ajrakhpur, Bhujodi, Hodka, Khavda** — living craft villages

---

## ♻️ Sustainability Philosophy

Rann Mitra is designed to nudge every traveller towards **responsible tourism**:
- Mixing famous sites with lesser-known alternatives to distribute tourist load
- Recommending local homestays over large resorts
- Flagging ecologically sensitive zones and advising minimal-waste behaviour
- Encouraging direct artisan purchases to support local livelihoods

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- Built as part of the **IBM AI Agent Project**
- Powered by [Groq](https://groq.com) ultra-fast LLM inference
- Inspired by the rich ecology and culture of the **Rann of Kutch, Gujarat, India**

---

<p align="center">Made with ❤️ using IBM Bob &nbsp;·&nbsp; Rann Mitra — Eco-Tourism Planner</p>
