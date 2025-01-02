# BoredBot

BoredBot is a fun and interactive web app that helps users find activities to try when they're bored. It fetches random activities using the Bored API and displays them in an engaging way.

## Features

- Fetches random activities from the Bored API.
- Displays the activity name and type (e.g., recreational, educational, etc.).
- Simple, responsive, and user-friendly UI.
- Interactive button to fetch a new activity.

## Technologies Used

- **HTML**: Structure of the web app.
- **CSS**: Styling the interface.
- **JavaScript**: Logic and interaction with the Bored API.
- **Bored API**: Source for random activity suggestions.

## Getting Started

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- A code editor like VS Code.
- A browser to run the project.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Kevin1skyrj/BoredBot.git
   ```

2. Open the `index.html` file in your browser to run the app.

## Usage

1. Open the web app in your browser.
2. Click the **"Give Me an Activity!"** button to fetch a random activity.
3. Enjoy trying out the suggested activity!

## Project Structure

```
BoredBot/
├── index.html       # HTML file for the web app
├── style.css        # CSS file for styling
├── script.js        # JavaScript file for functionality
├── README.md        # Project documentation (this file)
```

## API Reference

- **API Used**: [Bored API](https://www.boredapi.com/)
- **Endpoint**: `/api/activity/`

Example Response:

```json
{
  "activity": "Learn how to fold a paper crane",
  "type": "education",
  "participants": 1,
  "price": 0.1
}
```

## Screenshots

![BoredBot Screenshot](#)
_Add a screenshot of your project here_

## Future Enhancements

- Add a feature to filter activities by type (e.g., recreational, cooking).
- Allow users to share activities on social media.
- Save favorite activities locally.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

**Rajat Pandey**

- GitHub: [Kevin1skyrj](https://github.com/Kevin1skyrj)
- LinkedIn: [Your LinkedIn Profile](#)

---

Thank you for checking out BoredBot! If you like the project, don't forget to give it a star ⭐ on GitHub!

