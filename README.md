# IRCTC Clone

A simple Python-based IRCTC clone using OOP. Fetches train data via `requests` and manages bookings in memory.

---

## Features

* Search Trains by source, destination, and date
* View Train Details (number, name, times)
* Check live train status
  *Built purely with OOP—no DB or web framework.*

---

## Tech Stack

* Python 3.x
* `requests`

---

## Installation & Usage

```bash
git clone https://github.com/lifedebugging/irctc-clone.git
cd irctc-clone
python3 -m venv venv && source venv/bin/activate
pip install requests
python app.py
```

Follow prompts to search, book, or cancel tickets.

---

## Future Improvements

* Live API integration
* Persistent storage (SQLite/JSON)
* Add a simple UI for user interaction
* Unit tests

---

*Note : This is an Experimental code*
