# AI Agents for Smart Trip Planning

## 🏝️ About the Project
**AI Agents for Smart Trip Planning** is an AI-powered travel planning system that leverages multiple AI agents to provide a seamless and budget-friendly travel experience. Using **CrewAI** and **Gemini AI**, this project helps travelers plan their trips efficiently by researching historical sites, estimating budgets, and creating well-balanced itineraries.

## 🎯 Features
- 🔎 **Travel Researcher Agent**: Finds historical sites, nearby hotels, public transport details, and real-time weather.
- 💰 **Budget Planner Agent**: Suggests budget flights, hotels, and daily expenses while keeping the total cost under a specified limit.
- 📅 **Itinerary Planner Agent**: Creates a detailed 3-day travel plan while considering budget and weather conditions.
- 🌐 **Real-time Data**: Uses **SerperDevTool** for live travel information.
- 🤖 **LLM-Powered Agents**: Uses **Gemini 2.0 Flash** for intelligent trip planning.

---

## 🛠️ Installation
To run this project, ensure you have **Python 3.8+** installed.

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/AI-Agents-Smart-Trip-Planning.git
cd AI-Agents-Smart-Trip-Planning
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up API Keys
Before running the script, set up the required API keys:

- **Gemini API Key** (for AI-powered responses)
- **Serper API Key** (for real-time travel data search)

```bash
export GOOGLE_API_KEY=your_gemini_api_key
export SERPER_API_KEY=your_serper_api_key
```

Alternatively, in Google Colab, store them using:
```python
from google.colab import userdata
gemini_key = userdata.get('gemini_key')
serper_key = userdata.get('serper_key')
```

---

## 🚀 Usage
Run the script with your desired destination and budget.
```python
python main.py --destination "Delhi" --budget "25000 INR"
```

Or modify the script to input values directly:
```python
result = crew.kickoff(inputs={'destination': 'Delhi', 'budget': '25000 INR'})
print(result)
```

---

## 🏗️ Project Structure
```
AI-Agents-Smart-Trip-Planning/
│── main.py                # Entry point for running the AI agents
│── agents.py              # Defines Travel Researcher, Budget Planner & Itinerary Planner
│── tasks.py               # Defines tasks assigned to each agent
│── requirements.txt       # Dependencies
│── README.md              # Project documentation
```

---

## 📌 Future Improvements
- ✅ Add support for multi-day and multi-city trips
- ✅ Integrate hotel and flight booking APIs
- ✅ Enhance LLM capabilities for personalized recommendations

---

## 🤝 Contributing
Pull requests are welcome! Feel free to contribute by improving functionality or adding new features.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📞 Contact
- **Author:** Furqan Ahmed  
- **LinkedIn:** [Your Profile](https://linkedin.com/in/your-profile)  
- **GitHub:** [Your GitHub](https://github.com/your-username)  

Happy Traveling! ✈️🌍

