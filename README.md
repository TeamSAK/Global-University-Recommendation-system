# Global-University-Recommendation-system
🎓 University Recommendation System
An intelligent, data-driven university recommendation engine that suggests the top matching institutions for students based on their academic profile, budget, region, language preferences, and more. This system uses machine learning and cosine similarity scoring to personalize suggestions, helping applicants make informed decisions for higher education worldwide.

🚀 Features
🔍 Custom User Input: Enter GPA, IELTS, preferred region, tuition budget, living cost, degree level, and specialization.

🤖 AI-Powered Matching: Uses cosine similarity over preprocessed and weighted features to suggest the best-fit universities.

🌎 Global Dataset: Trained on a cleaned dataset of over 2000+ universities with real-world attributes.

💸 Budget Filter: Filter results by tuition and living costs with fallback logic for broader recommendations.

🎓 Degree-Level Specific Matching: Ensures results align with user’s specified level — Bachelor, Master, or PhD.

🧠 Flexible Recommendation Logic: Provides fallback matches when strict filters yield no direct hits.

📊 Dataset Fields Used
University Name, Country, City

Field of Specialization

Tuition & Living Costs

IELTS & GPA Requirements

Degree Level, Region, Language of Instruction

Internship Opportunities, Intake Months, Scholarship Availability

Public or Private, Application Fees, Acceptance Rate, Job Placement Rate

🧪 Tech Stack
Python 3

Pandas for data processing

Scikit-learn for encoding, scaling, and similarity scoring

Jupyter Notebook for execution

Excel (.xlsx) as the input data source

🛠️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/university-recommendation-system.git
cd university-recommendation-system
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook in Jupyter or Google Colab.

📥 Example Input
plaintext
Copy
Edit
Field of Specialization: Artificial Intelligence
Degree Level: Master
GPA: 3.2
IELTS: 7.0
Max Tuition: 10000
Max Living Cost: 8000
Scholarship Available: Yes
Region: EU
🧠 Future Enhancements
Add university application deadlines and intake seasons

Integrate ranking APIs (QS, THE)

Add support for program-specific recommendations (e.g., MBA vs. MSc AI)

Web interface with streamlit or Flask

Fully funded program filter toggle

🤝 Contributing
Pull requests and improvements are welcome! Please ensure code is clean and documented before submission.

📄 License
This project is open-source under the MIT License.
