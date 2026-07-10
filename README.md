# 🎬 CineSage-AI

AI-powered Movie Information Extractor built using **LangChain**, **Mistral AI**, **Pydantic**, and **Streamlit**.

Simply paste any movie description, and the application automatically extracts structured movie metadata including title, genre, cast, director, release year, rating, and summary.

---

## 🚀 Features

✅ Extract movie information from plain English descriptions

✅ Uses Mistral AI LLM

✅ LangChain Prompt Templates

✅ Pydantic Output Parser

✅ Beautiful Streamlit Interface

✅ Structured JSON Output

---

## Demo

![Demo](assets/screenshot.png)

---

## Tech Stack

- Python
- Streamlit
- LangChain
- Mistral AI
- Pydantic
- dotenv

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/CineSage-AI.git

cd CineSage-AI
```

Create virtual environment

```bash
python -m venv .venv
```

Activate environment

Windows

```bash
.\.venv\Scripts\activate
```

Mac/Linux

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env`

```
MISTRAL_API_KEY=YOUR_API_KEY
```

Run the application

```bash
streamlit run app.py
```

---

## Example Input

```
An alien stranded on Earth begins questioning religious beliefs and social customs while searching for a way to return home.
```

---

## Example Output

```json
{
    "title": "PK",
    "release_year": null,
    "genre": [
        "Comedy",
        "Drama"
    ],
    "director": "Rajkumar Hirani",
    "cast": [
        "Aamir Khan",
        "Anushka Sharma",
        "Sushant Singh Rajput"
    ],
    "rating": null,
    "summary": "An alien stranded on Earth begins questioning religious beliefs..."
}
```

---

## Future Improvements

- Movie Poster Generation
- IMDb API Integration
- TMDb Integration
- Multi-language Support
- Download JSON
- Export CSV
- Chat with Movies

---

## Learning Outcomes

- Prompt Engineering
- LangChain Prompt Templates
- Output Parsers
- Pydantic Models
- LLM Structured Outputs
- Streamlit UI Development

---

## Author

**Aditi Singh**

MCA | AI & Prompt Engineering Enthusiast

 
