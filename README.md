# Interview EQ Analyzer - Frontend

## Overview

The **Interview EQ Analyzer** is a React application designed to facilitate audio recording and uploading for interview responses. The recorded audio is sent to the backend, where it is processed by a machine learning model to classify the emotional intelligence of the responses.

## Features

- Record audio responses directly within the app.
- Upload audio files for analysis.
- Send audio data to the backend for classification.
- Display results from the machine learning model.

## Technologies Used

- **React**: For building the user interface.
- **Axios**: For making HTTP requests to the backend.
- **Audio API**: To handle audio recording and playback.
- **CSS**: For styling the application.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js (v14 or higher)
- npm (v5.6 or higher)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd interview-eq-analyzer-frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Running the Application

To start the development server, run:

```bash
npm start
```

This will open the app in your default browser at `http://localhost:3000`.

### Recording and Uploading Audio

1. Click on the **Record** button to start recording your audio response.
2. Once finished, click on the **Stop** button to stop recording.
3. After stopping, you can choose to upload the recorded audio or record a new response.
4. The uploaded audio will be sent to the backend for processing, and you will receive the classification results.

## API Integration

Ensure your backend server is running and is accessible. The frontend communicates with the backend API to send audio data and retrieve results. Update the API endpoint in the code as needed.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the contributors and open-source libraries that made this project possible.
