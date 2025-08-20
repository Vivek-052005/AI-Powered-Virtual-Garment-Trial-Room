# AI-Powered Virtual Garment Trial Room 👗🕶️
https://68a577efea47bae7a427c95a--statuesque-madeleine-854f58.netlify.app/

An **innovative AI and AR-based system** that enables users to virtually try on clothes and accessories in real-time. This project enhances the **online shopping experience** by reducing product returns and increasing customer satisfaction, all without requiring expensive hardware.

---

## 🚀 Features

* **Virtual Try-On**: Overlay garments and accessories on live webcam feed.
* **Admin Dashboard**: Add, update, and delete product catalog items.
* **User System**: Register, log in, shop, add to cart, and try clothes virtually.
* **Real-Time AR**: Uses **OpenCV**, **Dlib**, and **CNNs** for detection and alignment.
* **Cost-Effective**: Works with standard devices (no Kinect or high-end hardware required).
* **Scalable**: Future scope includes integration with **Pose Alignment Networks (PAN)**, **Texture Refinement Networks (TRN)**, and **VR systems**.

---

## 🛠️ Tech Stack

* **Language**: Python 3.10.8
* **Framework**: Flask (for backend + integration with HTML front-end)
* **Libraries**:

  * OpenCV
  * Dlib
  * NumPy
  * SciPy
  * Tkinter
  * CMake
* **IDE**: PyCharm
* **OS Support**: Windows 7/8/10

---

## 📂 Modules

### 🔹 Admin Module

* Login with authentication
* Manage product catalog (CRUD operations)

### 🔹 User Module

* Register & login
* Browse products & add to cart
* Try-on clothes using webcam (AR overlay)

### 🔹 AR Module

* Real-time body & face detection (Haar cascades + Dlib)
* Garment overlay with alignment and transparency

### 🔹 Video Processing Module

* Capture webcam feed with OpenCV
* Process frames for garment overlay
* Render real-time try-on experience

---

## ⚙️ Installation & Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/yourusername/virtual-garment-trial-room.git
   cd virtual-garment-trial-room
   ```

2. **Create a virtual environment** (recommended)

   ```bash
   python -m venv venv
   source venv/bin/activate   # for Linux/Mac
   venv\Scripts\activate      # for Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask server**

   ```bash
   python app.py
   ```

5. **Access the app**
   Open browser → `http://127.0.0.1:5000/`

---

## 💻 Hardware Requirements

* Processor: Intel i3 or above
* RAM: 8 GB+
* Disk: 160 GB+
* Webcam required

---

## 📈 Future Scope

* Integration with **advanced deep learning networks** (PAN, TRN).
* Expansion into **cosmetics, eyewear, furniture visualization**.
* Full **VR/AR immersive shopping experience**.

---

## 🤝 Contributing

Contributions are welcome! Please fork this repo, create a new branch, and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

👉 Would you like me to also generate a **requirements.txt** file (with correct versions of all libraries from your document) so your repo is plug-and-play?
