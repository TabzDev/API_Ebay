# PokeTrader - Pokémon Card Sold Price Search

PokeTrader is a lightweight web app that lets you search **recent eBay sold prices** for any Pokémon card.
Simply type a card name or number (e.g. "Charizard EX 199/165") and see prices, stats, and sale links.

---

## 🔧 Features

- Fetches sold eBay listings (last 90 days)
- Converts all prices to GBP using real-time exchange rates
- Displays listings with title, final sale price, and direct links
- Shows stats: average and max price
- Clean, modern UI with chart and responsive layout

---

## 🚀 Getting Started

### 1. Clone or Download the Project
```bash
git clone https://github.com/yourusername/poketrader.git
cd poke_app


# How to Run PokeTrader on a New Computer (Windows / macOS / Linux)

1. Install Python
- Go to https://www.python.org/downloads/
- Download and install Python 3.10 or later for your operating system.
- IMPORTANT: During installation, make sure to check "Add Python to PATH" (Windows) or verify Python is accessible in Terminal (macOS/Linux).

2. Open Terminal or Command Prompt
- Windows: Press Win + R, type cmd, and press Enter.
- macOS/Linux: Open Terminal from Applications or Spotlight.

3. Navigate to Your Project Folder
Use the `cd` command to change directories to your PokeTrader app folder.

Example:
- Windows:
  cd "C:\Users\YourName\Downloads\API Ebay Task\poke_app"
- macOS/Linux:
  cd ~/Downloads/API\ Ebay\ Task/poke_app

4. (Optional but Recommended) Create and Activate a Virtual Environment
To isolate dependencies, run:

- Create virtual environment:
  python -m venv venv

- Activate virtual environment:
  Windows:
    venv\Scripts\activate
  macOS/Linux:
    source venv/bin/activate

5. Install Required Python Packages
Run the following to install all dependencies from requirements.txt:

pip install -r requirements.txt

6. Run the Flask App
Start the Flask web server by running:

python app.py

You should see output like:
* Running on http://127.0.0.1:5000

7. Open the App in Your Web Browser
Open your browser and go to:

http://127.0.0.1:5000

You should see the PokeTrader search page.

8. Use the App
- Type a Pokémon card name or number (e.g., Charizard EX 199/165).
- Click the Search button.
- View sold listings and prices converted to GBP.

Troubleshooting:
- If 'python' command is not found, try 'python3' instead.
- Make sure you have an active internet connection.
- To stop the app, press CTRL + C in the terminal.

---

That’s it! Your PokeTrader app should now be up and running.
