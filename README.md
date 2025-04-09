# TimezoneBuddy

TimezoneBuddy is a web application that helps you manage time across different timezones. It allows you to:

- Look up current time in any timezone
- Compare times between multiple timezones
- Schedule meetings and see what time it would be in each timezone

## Features

- Modern, responsive UI with Material-UI components
- Dark/Light theme toggle
- Real-time timezone conversion
- Meeting time calculator
- Clean and intuitive interface

## Prerequisites

- Python 3.8+
- Node.js 14+
- npm or yarn

## Setup

### Backend Setup

1. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Start the backend server:

```bash
cd backend
uvicorn main:app --reload
```

### Frontend Setup

1. Install dependencies:

```bash
cd frontend
npm install
```

2. Start the development server:

```bash
npm start
```

## Usage

1. Open your browser and navigate to `http://localhost:3000`
2. Use the "Current Time Lookup" section to search for time in any timezone
3. Use the "Meeting Time Calculator" to schedule meetings across multiple timezones

## API Endpoints

- `GET /time/{location}` - Get current time for a specific timezone
- `POST /meeting-times` - Calculate meeting times across multiple timezones
- `GET /timezones` - Get list of all available timezones

## Contributing

Feel free to submit issues and enhancement requests!
