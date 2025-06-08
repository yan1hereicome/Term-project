# Term-project
Style_transfer

# 🎨 Neural Style Transfer with TensorFlow

This project applies **Neural Style Transfer** to blend the *style* of one image (like a painting) with the *content* of another image (like a photo). It uses a pre-trained **VGG19** model in TensorFlow to extract and recombine image features.

---

## 🧠 What is Neural Style Transfer?

Neural Style Transfer is a deep learning technique that blends two images:
- **Content Image**: The structure (e.g., a person, city, or landscape)
- **Style Image**: The artistic style (e.g., brushstrokes, colors, patterns)

The model optimizes a new image that preserves the content of the first and the style of the second.

---

## 📁 Project Structure

style-transfer/
│
├── style_transfer.ipynb # Jupyter Notebook with full code
├── content.jpg # Content image (e.g., a photo of a landscape)
├── style.jpg # Style image (e.g., a painting like Starry Night)
├── output.jpg # Output image after style transfer
├── requirements.txt # List of dependencies
└── README.md # Project documentation


---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/style-transfer.git
cd style-transfer
pip install tensorflow numpy matplotlib pillow

🚀 How to Run

Launch the notebook:
jupyter notebook style_transfer.ipynb
Choose your own content.jpg and style.jpg.
Run each cell in order to generate the stylized output.
Output is saved as output.jpg.

🧾 Requirements

Python 3.8–3.10
TensorFlow 2.x
NumPy
Matplotlib
Pillow

You can install everything using:

pip install -r requirements.txt


📚 References

A Neural Algorithm of Artistic Style — Original paper
TensorFlow documentation on tf.keras.applications.vgg19

📌 License

This project is open-source and available under the MIT License.

Name -나잉 ID-23101170
