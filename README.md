
# AstroDash - NBA Dashboard - WEB102 PROJECT 5

AstroDash is an interactive NBA dashboard built using React and Vite. The application retrieves NBA game information from an external API and displays it in a clean, user-friendly interface.

This project was developed as part of CodePath's WEB102 Web Development course.

## Demo

![AstroDash Demo](./DEMO.gif)

## Features

- **NBA Game Dashboard:** Displays NBA games and team matchups using data retrieved from an API.
- **API Integration:** Fetches and processes NBA game information dynamically.
- **Search and Filtering:** Allows users to filter displayed game information.
- **Responsive Layout:** Organizes game information in a clean, responsive interface.
- **Reusable Components:** Uses React components to organize and display data.

## Technologies Used

- React.js
- JavaScript
- HTML5
- CSS3
- Vite
- REST API
- Git & GitHub

## Installation

To run this project locally, follow these steps.

### 1. Clone the Repository

```bash
git clone https://github.com/SamM-SWE/WEB102-PROJECT5.git
```

### 2. Navigate to the Project Directory

```bash
cd WEB102-PROJECT5
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

If using an API key, create a `.env` file in the root directory.

```env
VITE_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your API key.

### 5. Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal, typically:

```
http://localhost:5173/
```

## How It Works

1. The application sends a request to an external NBA API.
2. The API returns game information in JSON format.
3. React processes the returned data and updates the dashboard.
4. Users can view game information and filter the displayed results.

## Project Structure

```text
WEB102-PROJECT5/
├── public/
├── src/
├── .gitignore
├── DEMO.gif
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Future Improvements

- Add detailed game statistics.
- Include individual team information.
- Improve search and filtering capabilities.
- Add additional NBA statistics and visualizations.

## Author

**Samuel Monneh**

