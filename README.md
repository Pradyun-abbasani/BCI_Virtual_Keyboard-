# BCI Virtual Keyboard using CNN

## Overview
This project implements a **Brain-Computer Interface (BCI) Virtual Keyboard** that uses a **Convolutional Neural Network (CNN)** to decode EEG signals and predict alphabet characters in real-time. The system features efficient signal processing, accurate predictions, and an interactive Python-based GUI.

## Features
- **EEG Signal Processing**: Prepares raw EEG data for accurate model input.
- **CNN Model**: Identifies patterns in EEG data to predict alphabets.
- **Real-Time Interaction**: Provides predictions and displays them via a virtual keyboard.
- **Python GUI**: A user-friendly interface for seamless interaction.

## Applications
- Assistive technologies for individuals with disabilities.
- Hands-free communication.
- Integration into gaming, education, and healthcare systems.

## Technologies Used
- **Python**: For implementing the model and GUI.
- **TensorFlow/Keras**: For developing and training the CNN.
- **EEG Data**: Sourced from public datasets or custom recordings.
- **PyQt/Tkinter**: For the graphical user interface.

## How It Works
1. **Data Collection**: EEG signals are recorded while focusing on specific alphabet characters.
2. **Signal Processing**: Raw EEG signals are cleaned and prepared for input.
3. **Model Training**: The CNN learns patterns associated with each letter from the processed data.
4. **Real-Time Prediction**: The trained model predicts the alphabet from test data.
5. **GUI Display**: Predictions are visualized through a virtual keyboard.

## Future Enhancements
- Add support for numbers and symbols.
- Improve prediction accuracy and real-time performance.
- Introduce multi-language support for the virtual keyboard.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/BCI_Virtual_Keyboard.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Contributions
We welcome contributions! Feel free to fork this repository, submit pull requests, or open issues to suggest improvements or report bugs.

---

### Acknowledgments
Special thanks to the open-source EEG datasets and libraries that made this project possible.
#
