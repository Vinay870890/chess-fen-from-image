# chess-fen-from-image

This project converts a top-down image of a chessboard into a valid **FEN (Forsyth–Edwards Notation)** using a pre-trained CNN model (`.h5`) and optional preprocessor (`.pkl`). The model detects pieces on each square, generates the FEN string, and optionally suggests the best move using **Stockfish**.

---

## 🚀 Features

- 🧠 Recognizes 13 classes: 12 chess pieces + empty square
- 📸 Works on chessboard images (e.g., screenshots, camera photos)
- 🧾 Outputs standard FEN strings
- ♟️ Uses Stockfish to suggest the best move from the position
- 💡 Built for Google Colab / Jupyter Notebook

---

## 🛠️ Tech Stack

- Python 3
- TensorFlow / Keras
- OpenCV
- Pillow (PIL)
- python-chess
- Stockfish Engine

---

---

## ✅ How to Use

1. Open the notebook `Chess_FEN_Generator_from_Image.ipynb`
2. Upload the following files:
   - Your chessboard image (`.png`/`.jpg`)
   - The `.h5` model file
   - The `.pkl` preprocessor (if used)
3. Run the notebook to:
   - Split the board into 64 squares
   - Predict each piece
   - Generate the FEN string
   - (Optional) Use Stockfish to recommend the best move

---

## 📦 Example Output

**Input Image:** `sample_board.png`  
**FEN Output:**  


