# PlanPilot – Your AI Life Organizer

PlanPilot is a Streamlit-based AI app designed to simplify your life as a student by automating task planning and scheduling. Powered by LangChain and ChatGroq, it breaks down any task—academic, personal, or extracurricular—into manageable subtasks with priorities and schedules, saving you time and reducing the stress of organizing your busy life. 

---

## How PlanPilot Helps You

- Saves Time: Automatically splits tasks like "Plan a weekend trip" or "Finish project" into 3-5 subtasks with a schedule, so you don’t need to plan manually.  
- Reduces Stress: Organizes your tasks to make your day-to-day feel manageable, whether it’s schoolwork or personal goals.  
- Tracks Tasks: Saves tasks to a JSON file for easy access anytime.  
- Remembers Context: Uses conversational memory to understand related tasks for smarter planning.  
- User-Friendly: Simple web interface fits into your busy student life.  

---


### Prerequisites
- Python 3.8+  
- Streamlit  
- LangChain  
- langchain-groq  
- Groq API key (set as `GROQ_API_KEY`)  


---

## Daily Use

- Open PlanPilot in your browser.  
- Enter a task (e.g., "Organize a study session" or "Plan a workout routine").  
- Click **Plan Task** to get a prioritized subtask list with a schedule.  
- Click **View All Tasks** to see all saved tasks.  
- PlanPilot remembers past inputs for consistent planning.  

---

## Future Scope

- Google Calendar Integration: Sync tasks and schedules with Google Calendar for seamless access across devices.  
- Weekly/Monthly Goal Planning: Input weekly or monthly goals (e.g., "Learn a new recipe this week" or "Save $100 this month") to generate tailored plans for any personal or academic objective.  
- Email-Based Reminders: Receive automated email reminders for upcoming subtasks and deadlines to stay on track.  

---

## Dependencies

- streamlit: Web interface  
- langchain: AI and memory features  
- langchain-groq: Groq AI integration  
- python: 3.8+  

---

## Notes

- Set `GROQ_API_KEY` before running.  
- Tasks are saved in `data/tasks.json`.  
- Uses deepseek-r1-distill-llama-70b model from Groq.  
- For API issues, see xAI's API docs.  

---

## Contributing

Have ideas to improve PlanPilot for students? Submit a pull request or issue!  

---

## License

MIT License
