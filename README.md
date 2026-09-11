# 💬 Kanye Quotes

A desktop quote application built with Python and Tkinter that retrieves random Kanye quotes using the Kanye Rest API.

## Features

- **Interactive GUI:** Features a custom background canvas and a clickable button.
- **On-Demand Quotes:** Generates a new random quote each time the button is clicked.
- **Dynamic Text Display:** Seamlessly updates the quote text centered on the speech bubble canvas.
- **Error Handling:** Validates HTTP responses using `raise_for_status()`.

## Technologies & Concepts

- **Python 3**
- **Tkinter:** GUI layout, window configuration, canvas rendering, and image buttons.
- **Requests:** Handling HTTP GET requests to external REST endpoints.
- **REST APIs & JSON:** Consuming and extracting data from JSON API responses.

## API Reference

This application uses the free and public [Kanye Rest API](https://api.kanye.rest) to fetch random quotes. No authentication or API key is required.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/techaseeb/kanye-quotes.git
   cd kanye-quotes
   ```

2. Install the required dependency:
   ```bash
   pip install requests
   ```

3. Launch the application:
   ```bash
   python3 main.py
   ```

## About the Course

Built as part of Angela Yu's **100 Days of Code: The Complete Python Pro Bootcamp**.

## Author

- [techaseeb](https://github.com/techaseeb)
