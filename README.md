# face-sunglasses-detection-opencv
# Adding Sunglasses to a Passport Photo Using OpenCV

## Project Overview

This project demonstrates how to use **OpenCV** and **NumPy** to add sunglasses to a passport-style face image using image processing techniques.

The project loads a face image and a sunglasses PNG image with an alpha channel (transparent background), resizes the sunglasses, extracts the mask, and overlays the sunglasses onto the face image.

---

## Technologies Used

* Python
* OpenCV (`cv2`)
* NumPy
* Matplotlib

---

## Project Workflow

### 1. Import Libraries

* Import OpenCV, NumPy, and Matplotlib.

### 2. Load Face Image

* Read the passport/face image using OpenCV.

### 3. Load Sunglasses Image

* Read the sunglasses PNG image with the alpha channel.

### 4. Resize Sunglasses

* Resize the sunglasses image to fit the eye region.

### 5. Extract Alpha Mask

* Separate the color channels and transparency mask.

### 6. Overlay Sunglasses

* Place the sunglasses over the eye region using masking and image blending techniques.

### 7. Display Final Output

* Show the original image and the final image with sunglasses.

---

## 📸 Features

1. Load and process images using OpenCV

2. Resize overlay objects dynamically

3. Use alpha channel masking

4. Overlay sunglasses naturally on a face image

5. Display results using Matplotlib

---

## Project Structure

```text
├── main_sunglass-checkpoint.ipynb
├── myphoto.jpg
├── sunglass.png
└── README.md
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### 2. Open the Project Folder

```bash
cd your-repository-name
```

### 3. Install Required Libraries

```bash
pip install opencv-python numpy matplotlib
```

### 4. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
main_sunglass-checkpoint.ipynb
```

---
## Input Image:
<img width="520" height="677" alt="myphoto" src="https://github.com/user-attachments/assets/fbbc7ace-d218-40de-84bc-bf77c460c442" />

## Output Image:

The final output shows sunglasses accurately placed over the eye region of the face image.
<img width="575" height="728" alt="image" src="https://github.com/user-attachments/assets/412ee2e1-591d-40b3-8469-8dbe32707347" />


---

## Future Improvements

* Automatic face and eye detection
* Real-time webcam sunglasses filter
* Multiple accessory overlays
* Adjustable sunglasses scaling and positioning

---

## Author

**MATHESH S**

Artificial Intelligence and Data Science Learning Student

---

## License

This project is created for educational and learning purposes.
rephase the content
