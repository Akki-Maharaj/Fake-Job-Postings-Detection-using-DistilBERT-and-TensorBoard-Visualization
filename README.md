🚫 Fake Job Postings Detection using DistilBERT & TensorBoard
This project detects fake job postings using DistilBERT, a lightweight transformer model, with interactive training visualizations in TensorBoard.

📊 Project Overview
Online job scams are a real threat. This project aims to:

✅ Identify and classify suspicious job postings.

✅ Fine-tune a pre-trained transformer (DistilBERT) on a real dataset.

✅ Visualize training performance and metrics in TensorBoard.

📂 Dataset
Source: Fake Job Postings Dataset on Kaggle

Description: Contains real vs. fake job listings with multiple attributes.

⚙️ Main Features
🧩 DistilBERT: Efficient, distilled version of BERT for faster training & inference.

📈 TensorBoard: Tracks loss, accuracy, and fine-tuning progress.

📊 Clean Data Pipeline: Text preprocessing & tokenization with Hugging Face Transformers.

✅ How to Run
1️⃣ Clone this Repo
bash
Copy
Edit
git clone https://github.com/Akki-Maharaj/Fake-Job-Postings-Detection-using-DistilBERT-and-TensorBoard-Visualization.git
cd Fake-Job-Postings-Detection-using-DistilBERT-and-TensorBoard-Visualization
2️⃣ Create a Virtual Environment
bash
Copy
Edit
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
3️⃣ Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
4️⃣ Download & Prepare Data
Place the Kaggle dataset CSV in your working directory.

Adjust paths in the notebook or Python script if needed.

5️⃣ Run Training
Use the provided Jupyter Notebook or Python script:

bash
Copy
Edit
# Example: Jupyter Notebook
jupyter notebook FakeJobPostingsDetection.ipynb

# Or Python script
python train.py
6️⃣ Visualize with TensorBoard
bash
Copy
Edit
tensorboard --logdir=runs
Open http://localhost:6006 to explore training graphs.

🏗️ Project Structure
bash
Copy
Edit
📁 data/                 # Place your dataset here
📜 FakeJobPostingsDetection.ipynb   # Main notebook
📜 train.py              # Optional: Script version
📜 requirements.txt      # Dependencies
runs/                    # TensorBoard logs
🛡️ Model Details
Base Model: DistilBERT (distilbert-base-uncased)

Frameworks: PyTorch, Hugging Face Transformers

Tasks: Binary classification (Real or Fake)

📌 Future Improvements
Expand dataset with more sources.

Deploy as a web app with an input form.

Experiment with other transformer variants.

🙌 Credits
Dataset: Fake Job Postings Dataset on Kaggle

Model: Hugging Face Transformers

Visualization: TensorBoard

Feel free to fork, star ⭐, and contribute!
