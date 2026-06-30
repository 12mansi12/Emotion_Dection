# 🖼️ Image-Text Similarity using Sentence Transformers (CLIP)

> An AI-powered Computer Vision project that matches an image with the most relevant text description using SentenceTransformers (CLIP).

---

## 🚀 Project Overview

This project uses the **SentenceTransformer CLIP (ViT-B-32)** model to understand both images and text in the same semantic space.

Instead of traditional image classification, the model converts:

- 📷 Images → Vector Embeddings
- 📝 Text Descriptions → Vector Embeddings

The similarity between these embeddings is then calculated to determine which text best describes the image.

---

## ✨ Features

✅ Image Embedding Generation

✅ Text Embedding Generation

✅ Semantic Similarity Matching

✅ Automatic Best Caption Selection

✅ Image Visualization using Matplotlib

✅ Easy to Modify with Your Own Images

---

## 🧠 Technologies Used

- Python
- Sentence Transformers
- CLIP (ViT-B-32)
- NumPy
- Pillow (PIL)
- Matplotlib

---

## 📂 Project Structure

```
├── SentenceTransformer.ipynb
├── ITALY.jpg
├── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/image-text-similarity.git
```

Install dependencies

```bash
pip install sentence-transformers
pip install pillow
pip install matplotlib
pip install numpy
```

---

## ▶️ How it Works

### Step 1

Load the pretrained CLIP model

```python
model = SentenceTransformer("clip-ViT-B-32")
```

### Step 2

Load an image

```python
img = Image.open("ITALY.jpg")
```

### Step 3

Provide multiple text descriptions

Example:

- Two dogs in the snow
- Taj Mahal view
- Historical US place
- Place to visit
- A cat on the table

---

### Step 4

Generate embeddings for both image and text

The model converts both into numerical vectors.

---

### Step 5

Compute similarity scores

The project calculates the similarity score between the image embedding and every text embedding.

---

### Step 6

Display the Best Match

The description with the highest similarity score is selected as the predicted caption.

---

## 📊 Example Output

```
Best Match:
Place to visit

Similarity Score:
0.81
```

*(Score may vary depending on the image.)*

---

## 💡 Applications

- Image Search
- Image Caption Retrieval
- Semantic Image Understanding
- AI-powered Search Engines
- Content Recommendation
- Vision-Language AI Systems

---

## 🔮 Future Improvements

- Upload custom images
- Use cosine similarity
- Support multiple images
- Top-K matching results
- Web interface using Streamlit
- Real-time image search

---

## 📚 Learning Outcomes

This project demonstrates:

- Multimodal AI
- Sentence Transformers
- CLIP Architecture
- Image Embeddings
- Text Embeddings
- Semantic Search
- Computer Vision
- Artificial Intelligence

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork the repository, create a new branch, and submit a pull request.

---

## 📜 License

This project is intended for educational and learning purposes.

---

## ⭐ If you found this project helpful

Give this repository a ⭐ on GitHub!

Happy Coding 🚀
