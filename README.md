# 🛰️ ISS Overhead Notifier

A Python automation project that tracks the current location of the International Space Station (ISS) and notifies the user when the ISS is passing overhead during nighttime.

The application uses real-time APIs to retrieve the ISS position and local sunrise/sunset information, making it possible to determine the best time to spot the ISS in the night sky.

## 🚀 Features

* Real-time ISS location tracking
* Nighttime detection based on user coordinates
* Uses external APIs for live data
* Automated notification system
* Lightweight and beginner-friendly project

## 🛠️ Technologies Used

* Python 3
* Requests Library
* Datetime Module
* ISS Location API
* Sunrise-Sunset API

## ⚙️ How It Works

1. Fetches the current ISS coordinates.
2. Checks whether the ISS is within ±5 degrees of the user's location.
3. Retrieves local sunrise and sunset times.
4. Determines whether it is currently nighttime.
5. Sends a notification when both conditions are satisfied.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/kevaldabhi461-del/issoverhead.git
```

Navigate to the project directory:

```bash
cd issoverhead
```

Install dependencies:

```bash
pip install requests
```

## ▶️ Run the Project

```bash
python main.py
```

## 📍 Configuration

Update your coordinates inside `main.py`:

```python
MY_LAT = YOUR_LATITUDE
MY_LONG = YOUR_LONGITUDE
```

## 🌐 APIs Used

* Open Notify ISS API
* Sunrise Sunset API

## 🎯 Learning Outcomes

* API Integration
* Working with JSON Data
* Automation with Python
* Time and Date Handling
* Real-world Programming Projects

## 🔮 Future Improvements

* Email notifications using SMTP
* SMS notifications
* Desktop notifications
* Graphical User Interface (GUI)
* Automatic background monitoring

## 👨‍💻 Author

Keval Dabhi

GitHub: https://github.com/kevaldabhi461-del

## ⭐ Support

If you found this project helpful, consider giving it a star on GitHub.
