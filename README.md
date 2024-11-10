# Thief Detection Alarm

This project is a web-based security application designed to detect intruders and trigger an alarm. It leverages AI and webcam integration for real-time monitoring, providing an effective solution to detect and alert users to unauthorized access.

## Technologies Used

- **Next.js**: For optimized, server-rendered React-based application.
- **React**: To build a responsive and interactive UI.
- **Tailwind CSS**: For custom styling and a modern design.
- **JavaScript**: Core language for detection logic and interactivity.
- **TensorFlow.js**: For real-time object detection using machine learning in the browser.
- **React Webcam**: To capture real-time webcam video feed within the application.

## Features

- **Real-time Object Detection**: Uses TensorFlow.js for detecting movement and specific objects in real-time.
- **Alarm System**: Triggers an audio alarm when suspicious activity is detected.
- **Modular Interface**: Built with a modular structure for easy customization.

## Project Structure

- **/app**: Contains the core files for layout, global styles, and the main page.
- **/components**: Houses \`object-detection.js\`, the main component responsible for integrating TensorFlow and handling the webcam feed.
- **/utils**: Contains utility scripts, such as \`render-prediction.js\`, used for rendering detection results on the video feed.
- **/public**: Includes static assets such as images and audio files for the alarm.

## Installation

1. **Clone the Repository**
   \`\`\`bash
   git clone <repository-url>
   cd Thief_Detection_Alarm-main
   \`\`\`

2. **Install Dependencies**
   \`\`\`bash
   npm install
   \`\`\`

3. **Run the Application**
   \`\`\`bash
   npm run dev
   \`\`\`

## Dependencies

- **TensorFlow.js**: Used in \`object-detection.js\` for processing video frames and detecting objects.
- **React Webcam**: Allows the application to access the device camera directly.
- **render-prediction.js**: A custom utility function to render prediction boxes on detected objects.

## Configuration

- **Object Detection**: Configurable in \`object-detection.js\` to adjust model parameters.
- **Audio Alarm**: Customizable audio file located in \`/public\`.

## Usage

1. Start the application.
2. Monitor the display for any detected objects.
3. The alarm will activate upon detecting unauthorized objects.

## License

This project is licensed under the MIT License.
