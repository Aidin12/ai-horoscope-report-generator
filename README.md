# AI-Powered Horoscope Report Generator
This prototype automates the creation of personalized Vedic astrology reports. It combines structured birth chart data with GPT-4 to generate emotionally intelligent, spiritually resonant answers across 10 core life questions. Final output is ready for formatting into a branded Google Doc or PDF.

---


##  Project Flow

1. **Input user birth details** (date, time, location)
2. **Pull astrology chart data** from API (mocked here for demo)
3. **Loop through 10 life-focused questions**
4. **Generate GPT-4 answers** with poetic, spiritual tone
5. **Structure responses** into sections
6. **(Planned)** Format into Google Docs and export to PDF

---

## Example Questions

- What does this person's Sun placement reveal about their core self?
- How does their Moon sign affect their emotional world?
- What karmic lessons does this chart suggest?

Each question receives a ~500-word personalized response tuned to planetary placements.

---

## 📂 Folder Structure

├── gpt_writer.ipynb # Main Colab notebook
├── prompt_helper.py # GPT call wrapper using OpenAI client
├── astrology_questions.py # 10-question bank
├── mock_chart_data.json # Sample astrology API response
└── README.md


---

## 💡 Technologies Used

- OpenAI GPT-4 API
- Python 3.10+
- Markdown rendering in Colab
- (Planned) Google Docs API or Zapier for document generation

---

## 🔮 Future Integration Plans

- Automated birth chart generation from external API  
- Structured JSON > Jinja2 > Google Docs  
- Full PDF generation + optional email delivery

---

## 🤝 Use Case

Perfect for astrology-based wellness platforms, coaches, or creators who want to offer deep, branded reports at scale — blending LLM intelligence with emotional resonance and Vedic tradition.

---

## Contact

Developed by Nidia Sahjara Sukhu  
LLM Engineer • NLP Researcher • Emotional AI Architect  
