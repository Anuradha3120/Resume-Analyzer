# Resume-Analyzer
Resume Job Match Scorer is a Streamlit-based web app that analyzes how well a resume matches a job description. It extracts text from PDF resumes and uses NLP techniques (TF-IDF and Cosine Similarity) to compute a match score. The app provides visual feedback and suggestions to help users tailor resumes for specific roles. 📄🚀

🚀 Features
📥 Upload resume in PDF format
📝 Paste job description
📊 Calculates match percentage between resume and job requirements
🧠 Uses NLP for text processing
⚡ Real-time analysis with Streamlit UI
📉 Visual score representation with chart
💡 Suggestions based on match quality

🛠️ Technologies Used
Python
Streamlit (Web Interface)
Scikit-learn (TF-IDF & Cosine Similarity)
NLTK (Text preprocessing)
PyPDF2 (PDF text extraction)
Matplotlib (Visualization)

⚙️ How It Works
Upload your resume (PDF)
Paste the job description
The system cleans and processes the text
Important words are extracted after removing stopwords
TF-IDF vectors are created for both texts
Cosine similarity is calculated to determine the match score
Results are displayed with visual feedback

📈 Output
The application provides:
Match score (percentage)
Visual progress bar chart
Match quality feedback:

⚠️ Low Match
ℹ️ Good Match
✅ Excellent Match

🎯 Use Cases
Job seekers optimizing resumes
Students preparing for placements
Recruiters screening resumes
Career guidance tools                                                                                        

## How to Run the Project
Use the following command to run application:
1] python -m streamlit run app.py
