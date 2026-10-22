# Project Title: AI Road Damage Detector Using Deep Learning

Act as an expert AI/ML engineer and full-stack developer. Build a complete, working hackathon project called AI Road Damage Detector.

## Objective
Develop an AI-powered web application that detects potholes and cracks in road images, estimates the severity of the detected damage, and displays reported damage locations on an interactive map.

## Required Features

1. **Image Upload:** Allow users to upload road images in JPG, JPEG, and PNG formats.
2. **AI-Based Detection:** Use a YOLO object detection model to detect potholes and road cracks. Draw bounding boxes around detected damage and display confidence scores.
3. **Severity Estimation:** Classify detected damage as Low, Medium, or High using transparent, configurable rules. Clearly explain that this is a prototype estimate.
4. **GPS Location:** Allow users to enter coordinates or provide device location permission to record where the road damage was found.
5. **Interactive Map:** Display reported road damage locations using Leaflet and OpenStreetMap.
6. **Dashboard:** Show total reports, detected damage categories, severity distribution, and recent reports.
7. **Report Management:** Save reports with timestamps, uploaded image references, detection results, and coordinates using SQLite.
8. **Download Report:** Allow users to download a damage report as a CSV file.
9. **User Interface:** Create a modern, responsive, professional interface suitable for a college hackathon demonstration.

## Technology Stack

- Python
- YOLO with a suitable pretrained or fine-tuned road damage detection model
- OpenCV
- Streamlit
- SQLite
- Pandas
- Folium or Leaflet for maps

## Development Requirements

- Provide the complete project folder structure.
- Write the complete code for every required file.
- Include requirements.txt and setup instructions.
- Explain how to install dependencies and run the application locally.
- Use a real road damage dataset for training or evaluation, and explain how to configure the model weights.
- Do not pretend that a generic pretrained model can detect potholes accurately without suitable training or verification.
- Add error handling for invalid images, missing model weights, and unavailable GPS coordinates.
- Include sample data for demonstration, clearly marked as sample data.
- Never fabricate detection results or GPS coordinates.
- Keep the code modular, readable, and suitable for students.
- Include a README with the problem statement, proposed solution, architecture, features, limitations, and future enhancements.

## Expected Output
Deliver a functional MVP that can be demonstrated during a hackathon. Start with the simplest working version, then explain how to add advanced features. Provide the implementation step by step and ensure that the project can run on a normal laptop without requiring paid services.
