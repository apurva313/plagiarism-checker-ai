# Plagiarism Detection using LSTM  
A deep learning project to identify plagiarized text pairs using Natural Language Processing (NLP) and LSTM-based neural networks.



## 📌 Objective  
To develop an LSTM-based model that can detect plagiarism by analyzing semantic similarity between pairs of sentences using NLP techniques and deep learning.


## 🗃️ Dataset  
- **Name:** SNLI-based Sentence Pair Dataset  
- **Source:** Provided in project (`train_snli.txt`)  
- **Format:** Tab-separated `.txt` file with structure: `sentence1 \t sentence2 \t label`  
- **Classes:**  
  - `0` – Not Plagiarized  
  - `1` – Plagiarized  

---

## 🛠️ Tools and Libraries  
- Python  
- pandas, numpy  
- seaborn, matplotlib  
- scikit-learn  
- TensorFlow / Keras  


## 🧠 Workflow  
1. Load and explore the dataset  
2. Preprocess text: Tokenization and Padding  
3. Build LSTM-based neural network  
4. Train and validate the model  
5. Evaluate accuracy on test data  
6. Visualize training metrics  


## ✅ Results  
- Achieved ~90–95% accuracy (varies with epochs and configuration)  
- Effective binary classification of text similarity  
- Model generalizes well on unseen sentence pairs  


## 📦 Files Included  
- `Updated_Plagiarism_Detector_LSTM.ipynb` – Complete Jupyter notebook  
- `train_snli.txt` – Training dataset  
- `README.md` – Project description and instructions  

## 🖥️ Run Instructions  
1. Open the `Updated_Plagiarism_Detector_LSTM.ipynb` notebook  
2. Ensure `train_snli.txt` is in the appropriate directory (`/mnt/data/` or local project folder)  
3. Run all cells to train and evaluate the LSTM model  
4. Modify or test with custom text pairs as needed  

## 👨‍💻 Author  
**Apurva Kumar**  
 
