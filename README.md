# L00187609_Dissertation_September_2025
# Cyberbullying Detection with XLNet and HateBERT  

This project explores the use of **deep learning models** for detecting cyberbullying on social media. It compares two transformer-based models, **XLNet** and **HateBERT**, trained on a binary-labelled Twitter dataset (*cyberbullying* vs *not cyberbullying*).  

---

## Dataset  

- `cleaned(1).csv` (included in this repository)  
- Derived from Twitter posts, reformatted into binary labels.  

---

## Quick Start  

1. Clone or download this repository.  
2. Place the dataset file (`cleaned(1).csv`) in the working directory.  
3. Open the notebooks:  
   - `HateBERT_Model.ipynb`  
   - `XLNet_Model.ipynb`  
4. Run the cells step by step to preprocess data, train models, and evaluate results.  

Dependencies:  
```bash
pip install torch transformers pandas numpy matplotlib scikit-learn
```

---

## Results  

- **HateBERT**: Better at detecting toxic and offensive language.  
- **XLNet**: Strong at capturing context and subtle language use.  

---

## Author  

Sathwik Reddy Salibindla 
L00187609
M.Sc. in Computing (Big Data Analytics and AI)  
Atlantic Technological University (ATU), Ireland  

