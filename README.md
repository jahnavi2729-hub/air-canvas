#  Air Canvas – Virtual Hand Paint App using Hand Gestures

This is an interactive project built in **Jupyter Notebook** using **Python**, **OpenCV**, and **Mediapipe**.  
It allows users to **draw in the air** by using hand gestures tracked via webcam — no mouse or stylus required!

---

##  Project Description

The Air Canvas app uses your **index finger** as a brush and detects hand gestures in real-time using Mediapipe.  
You can draw on a virtual canvas by moving your hand in the air, and you can change brush colors or clear the canvas using gesture-based UI buttons.

---

## Technologies Used

- Python 3.11
- OpenCV – for webcam feed and drawing functions
- Mediapipe – for real-time hand tracking
- NumPy – for image array manipulation
- Jupyter Notebook – for running and visualizing the project

---

## Features

- Real-time hand gesture detection with only one hand
- Draw using your fingertip tracked via webcam
- Change brush color (Blue, Green, Red, Yellow)
- Clear the canvas with a gesture
- Uses deque data structure for smooth line tracking
- Press `q` to quit

---

##  How to Run in Jupyter Notebook

1. **Install the dependencies**:
   ```bash
   pip install opencv-python mediapipe numpy
   ```

2. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   Open your `air_canvas.ipynb` notebook.

3. **Run all cells** to start the virtual paint window.

4. **Controls**:
   - Move your index finger over buttons to select color or clear.
   - Keep your thumb away from index finger to draw.
   - Press `q` inside the webcam window to stop the program.

---



##  Author

**Jahnavi**  
Final Year CSBS Student  
Focused on Accessibility + AI

---

##  Future Enhancements

- Add save-to-image functionality
- Use voice commands to change tools or colors
- Implement shape drawing (rectangles, circles)
- Add eraser mode
- Add multi-hand support
