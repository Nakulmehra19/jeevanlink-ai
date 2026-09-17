# JeevanLink AI

### Intelligent Donor–Recipient Matching Platform

JeevanLink AI is an AI-powered blood and organ donor–recipient matching platform developed to make donation coordination more organized, intelligent, and efficient.

The platform provides a centralized system for donor registration, emergency requests, donor matching, verification, request management, analytics, and AI-powered assistance.

## Features

- Donor registration and availability management
- Emergency blood and organ request creation
- Blood group compatibility checking
- Donation-type compatibility checking
- Location-based donor prioritization
- Match scoring and donor ranking
- Donor verification and status management
- Admin Portal for donor and request management
- Persistent data storage using Supabase
- Interactive dashboard and analytics
- Gemini-powered AI Assistant
- Activity and match management

## Technologies Used

| Technology | Purpose                                   |
| ---------- | ----------------------------------------- |
| Python     | Core application development and logic    |
| Streamlit  | Web application interface and dashboard   |
| Supabase   | Persistent data storage                   |
| Gemini AI  | AI Assistant and intelligent assistance   |
| Pandas     | Data processing and data handling         |
| Plotly     | Interactive charts and data visualization |


## How the Matching Works

1. Donor details are registered in the system.
2. A recipient creates a blood or organ request.
3. The system checks donor availability.
4. Donation type and blood compatibility are evaluated.
5. Location is considered for prioritization.
6. Donor verification status is checked.
7. A match score is calculated.
8. Suitable donors are ranked and displayed.

## Project Structure

```text
jeevanlink-ai/
│
├── app.py
├── ai_engine.py
├── data_store.py
├── requirements.txt
│
├── page_views/
│   ├── admin_portal.py
│   ├── ai_assistant.py
│   ├── dashboard.py
│   ├── find_matches.py
│   ├── home.py
│   ├── post_request.py
│   ├── register_donor.py
│   └── settings.py
│
└── .streamlit/
