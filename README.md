# 🏠 Senior-Switchman: Automated Home Switch Control System

## 📌 Project Description

**Senior-Switchman** is a Python-based GUI application designed to control up to **16 electrical switches** in a home environment. It allows users to turn **single or multiple switches** ON/OFF manually or **schedule them** to operate automatically at specific times.

The application simulates room switch states using a graphical interface with status images and includes **sound feedback** for enhanced accessibility, making it especially suitable for senior users or smart home environments.

---

## 🧩 Key Features

- 🔘 Control individual switches manually  
- 🔀 Control multiple switches at once  
- 🕒 Schedule auto ON/OFF times for any switch  
- 🖼️ Graphical feedback using switch state images  
- 🔊 Audio feedback with click sounds  
- 💡 Real-time status update per room and switch  

---

## 🛠️ Technologies Used

- 🐍 Python 3.x
- 🧪 Tkinter (GUI)
- 🖼️ PNG images for switch states
- 🔊 MP3 sound effects for interactions

---

## 🖼️ GUI Demo Images

Below are sample room states (on/off) visualized in the GUI:

```

images/
├── front.png              # Homepage
├── room1-1,2on.png        # Room 1 - both switches ON
├── room1-1,2off.png       # Room 1 - both switches OFF
├── room2-1on.png          # Room 2 - switch 1 ON
├── thank\_you.png          # Exit screen


```

> You can find all switch state images in the root directory.

---

## 📁 File Structure

```

├── PythonApplication1.py         # Main application code
├── PythonApplication1.pyproj     # Project file (for IDE)
├── PythonApplication1.sln        # Solution file
├── front.png, img\*.png, room\*.png  # All GUI images
├── click.mp3                     # Audio feedback
├── Elegant\_Slides.pdf            # Project presentation slides
├── README.md                     # Documentation
├── LICENSE                       # MIT License

````

---

## 🚀 How to Run the Project

### Prerequisites:
- Python 3.x installed
- Tkinter (comes preinstalled with Python)

### Run the application:
```bash
python PythonApplication1.py
````

> Make sure all image and sound files are in the same directory.

---

## 🎯 Use Cases

* Elderly-friendly home automation
* Smart room lighting/switch simulation
* Timed control of devices (e.g., fans, lights, heaters)
* Assistive systems for users with limited mobility

---

## 📄 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for more details.

---

## 🙌 Contributions

Contributions are welcome!
Feel free to fork the repo and enhance UI, scheduling logic, or integration with physical devices.
