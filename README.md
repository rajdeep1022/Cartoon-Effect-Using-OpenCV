# 🎨 Cartoon Effect on Image

## 📌 Overview
This project applies a **cartoon effect to images** using image processing techniques.  
By combining edge detection, smoothing, and color quantization, a normal image is transformed into a cartoon-style image.

This project is useful for learning **computer vision basics** and understanding how image filters work.

---

## 🎯 Objective
To convert a real image into a cartoon-like version using Python and image processing libraries.

---

## 🧠 How It Works
1. Load the input image  
2. Convert the image to grayscale  
3. Apply noise reduction (blurring)  
4. Detect edges in the image  
5. Reduce the number of colors (color quantization)  
6. Combine edges with the smoothened image to create a cartoon effect  

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**  
  - OpenCV  
  - NumPy  
  - Matplotlib  

---

## 📂 Project Structure
```commandline
Cartoon-Effect-on-Image/
│
├── Cartoon_Effect_on_Image.ipynb
├── input_image.jpg
├── output_cartoon_image.jpg
└── README.md
```

---

## 🚀 How to Run the Project
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/cartoon-effect-on-image.git

2. Install required libraries
   ```bash
   pip install opencv-python numpy matplotlib
   ```


3. Open and run the Jupyter Notebook

   ```bash
   jupyter notebook Cartoon_Effect_on_Image.ipynb
   ```

4. Upload an image and view the cartoon effect 🎉

---

## 📸 Sample Output

- **Input:** Original image
  - <img width="648" height="479" alt="image" src="https://github.com/user-attachments/assets/90cc99ec-5207-4d4d-90c9-86bf6c117fe3" />


- **Output:** Cartoon-style image with smooth colors and bold edges
  - <img width="654" height="478" alt="image" src="https://github.com/user-attachments/assets/78a42ea0-38fd-4a8b-a0a0-08909f5c05cf" />

---

## 🌱 Use Cases

- Image processing practice

- Computer vision learning

- Fun photo effects

- Beginner OpenCV projects

---

 ## 📌 Future Improvements

- Add real-time webcam cartoon effect

- Build a web app using Flask

- Add multiple cartoon styles

- Provide user-controlled filters

---

## ⭐ Acknowledgement

- This project uses OpenCV for image processing.
