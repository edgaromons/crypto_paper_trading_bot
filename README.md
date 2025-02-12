In this project, we:

•	Developed a cryptocurrency paper trading bot using Python and the Alpaca API to identify and capitalize on volatile assets.

•	Integrated CoinGecko API to fetch real-time cryptocurrency data for market analysis and decision-making.

•	Implemented a PostgreSQL database using SQLAlchemy to store and manage cryptocurrency prices, orders, and portfolio performance.

•	Utilized TA-Lib library to calculate technical indicators such as Bollinger Bands and RSI for identifying trading signals.

•	Built a Dockerized application for deploying and automating the cryptocurrency trading bot.

•	Utilized object-oriented programming principles to create modular and maintainable code for the trading bot.

•	Developed a custom trading strategy based on technical analysis and volatility to identify profitable trading opportunities.

Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
