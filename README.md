# PCA-in-3D
![image](https://github.com/user-attachments/assets/e39581f6-bfe0-454e-89de-45926f040abf)


# 3D Visualization : 3D visualizations of Word2vector embeddings 🚀

Transform word embeddings into an **interactive 3D masterpiece**! This project takes the pretrained `word2vec-google-news-300` model, reduces its 300-dimensional vectors to 3D with PCA, and visualizes them using Plotly. Words like "king," "queen," "doctor," and "cat" dance in space with dynamic colors, direction vectors, and a semantic core—revealing the hidden structure of language in NLP.

## ✨ Features
- **Interactive 3D Plot**: Spin, zoom, and explore word vectors in a browser-based visualization.
- **Color Coding**: Markers shift from red to blue based on cosine similarity to "king."
- **Direction Vectors**: Dashed arrows trace each word’s path from the origin.
- **Semantic Core**: A red diamond marks the average vector position.
- **Dual Themes**: Choose between a dark cosmic look or a light blue modern vibe.

## 🛠️ Tech Stack
- **Python 3.x**
- **Gensim**: For loading Word2Vec.
- **Scikit-learn**: PCA dimensionality reduction.
- **Plotly**: Interactive 3D plotting.
- **NumPy**: Vector and array operations.

## 📦 Installation
1. **Clone the Repo**:
   ```bash
   git clone [https://github.com/ChandraPrakash-Bathula/PCA-in-3D.git]
   ```
2. **Install Requirements**:
   ```bash
   pip install gensim scikit-learn plotly numpy glove model
   ```
3. **Run the Script**:
   - Multiple themes available

## 🚀 Usage
- Run either script to launch the visualization.
- The Word2Vec model downloads on first run (~1.6 GB, so grab a coffee).
- A browser window opens with the 3D plot—click, drag, and scroll to explore.
- Edit the `words` list in the code to visualize your own terms.

## 🎨 Themes
- **Dark Cosmic**: Black background, white text, starry grid (`rgba(10, 10, 20, 0.9)`).
- **Light Blue**: Soft blue background, black text (`rgba(230, 240, 250, 0.9)`).

## 🔮 Future Enhancements
- Swap PCA for t-SNE for funkier clusters.
- Add clustering to group related words.
- Integrate into an NLP dashboard.

## 🤝 Contributing
Fork it, tweak it, PR it! Ideas welcome—let’s make this even wilder.

## 📄 License
[MIT License](LICENSE)—use it, share it, just give a nod back.

## 🙌 Acknowledgments
- Built by a student researcher hooked on ML and NLP.
- Thanks to Gensim, Scikit-learn, and Plotly for the open-source juice.

---
