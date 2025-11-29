# live-portfolio-dashboard

A Python-based interactive portfolio tracker with a GUI, live stock prices, and dynamic charts. Built with Tkinter, yfinance, pandas, and Matplotlib.  

Track your stocks in real-time, visualize your portfolio allocation, and see total value over time. Add or remove stocks dynamically — perfect for building a mini trading dashboard!


## Features

- Live portfolio table with:
  - Ticker, Shares, Buy Price
  - Current Price, Position Value, Gain/Loss, Return %
- Add new stocks dynamically (enter ticker, shares, and buy price)
- Remove selected stocks from the portfolio
- Auto-refresh every 10 seconds
- Pie chart: shows portfolio allocation by stock
- Line chart: tracks total portfolio value over time
- Fully embedded GUI using Tkinter


## Installation

1. Clone the repository:

```bash
git clone https://github.com/<USERNAME>/<REPO>.git
cd <REPO>
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
pip install yfinance pandas matplotlib
python portfolio_gui.py

![Image 11-29-25 at 14 17](https://github.com/user-attachments/assets/8dbcbd3a-9b75-47ca-a378-405ecc013ebe)
