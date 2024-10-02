
# Adaptive Personalized Learning Platform Using Cognitive Behavioral Data

![Project Logo](link-to-your-logo-image) <!-- Replace with your logo image link or remove this line -->

## Overview

The **Adaptive Personalized Learning Platform** is designed to enhance learning outcomes by analyzing user interactions and emotional responses. Leveraging cognitive behavioral data, this platform personalizes the learning experience based on user performance and emotions, aiming to improve engagement with educational content.

## Features

- **User Interaction Simulation**: Simulates user interactions with tasks, logging performance, time spent, and emotions detected.
- **Emotion Recognition**: Utilizes emotion recognition to gauge user engagement and adapt learning materials accordingly.
- **Performance Prediction**: Employs machine learning models to predict user performance and tailor the learning experience.

## Requirements

To run this project, ensure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `opencv-python`
- `deepface`
- `scikit-learn`

You can install the required libraries using pip:


pip install numpy pandas opencv-python deepface scikit-learn
```
### Create Sample Data

Create the sample log and CSV files if they are not already present. You can run the following code in a Python environment to create the log files:

```python
# Create user_interactions.log
log_data = """{'user_id': 1, 'task_id': 1, 'time_spent': 15, 'performance': 1, 'emotion': 'happy', 'timestamp': '2024-10-01 10:00:00'}
{'user_id': 1, 'task_id': 2, 'time_spent': 20, 'performance': 1, 'emotion': 'neutral', 'timestamp': '2024-10-01 10:15:00'}
{'user_id': 1, 'task_id': 3, 'time_spent': 10, 'performance': 0, 'emotion': 'sad', 'timestamp': '2024-10-01 10:30:00'}
{'user_id': 2, 'task_id': 1, 'time_spent': 25, 'performance': 1, 'emotion': 'happy', 'timestamp': '2024-10-01 11:00:00'}
{'user_id': 2, 'task_id': 2, 'time_spent': 30, 'performance': 1, 'emotion': 'excited', 'timestamp': '2024-10-01 11:30:00'}
{'user_id': 2, 'task_id': 3, 'time_spent': 15, 'performance': 1, 'emotion': 'happy', 'timestamp': '2024-10-01 12:00:00'}
...
"""
with open('user_interactions.log', 'w') as f:
    f.write(log_data)

# Create user_interactions.csv similarly
```

### Run the Platform

Execute the main code to simulate user interactions and analyze the results:

```bash
python adaptive_learning_platform.py
```

## Usage

- The platform simulates user interactions, logging performance, time spent, and detected emotions in `user_interactions.log`.
- Use the `user_interactions.csv` file to analyze user behavior in a structured format.
- Modify the `adaptive_learning_platform.py` script to customize user interaction simulations or the machine learning model.

## Dataset

### user_interactions.log

- Contains logs of user interactions, detailing user IDs, task IDs, time spent, performance, emotions, and timestamps.

### user_interactions.csv

- A structured dataset for analyzing user interactions and performance.

## Future Work

- Enhance emotion detection algorithms for more accurate recognition.
- Integrate real-time feedback mechanisms to adapt learning materials based on emotional states.
- Expand the dataset with more user interactions to improve model training.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by cognitive behavioral theories in education.
- Utilizes the DeepFace library for emotion detection.
- Developed with support from the open-source community.

## Contact

For questions or feedback, please reach out to [your.email@example.com](mailto:sehanbalajee@gmail.com).
```

### Customization
- Replace `link-to-your-logo-image` with an actual link to your project's logo image, or remove this line if you don't have one.
- Change `yourusername` in the clone URL to your actual GitHub username.
- Update the email address in the contact section with your actual email address.
- Adjust any other sections as needed to better reflect your project.

Feel free to ask if you need further adjustments or additional information!
