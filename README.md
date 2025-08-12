**OVERVIEW:**
This project evaluates job candidates by analyzing their Resume, LinkedIn profile, and GitHub. It extracts relevant information, processes it, and uses AI to generate scores, feedback, and improvement suggestions tailored to a target job description.

**FEATURES:**
•	Resume Parsing – Extracts text from PDF resumes.
•	LinkedIn Scraper – Gathers headline, education, skills (removes duplicates).
•	GitHub Scraper – Collects repository and activity data.
**AI Evaluation – Uses Google Gemini AI to:**
•	Assess strengths and weaknesses.
•	Suggest improvements.
•	Generate a final candidate score.
•	Data Cleaning – Ensures unique skills and consistent formatting.

**TECH STACK:**
•	Python
•	Playwright – LinkedIn scraping
•	pdfminer.six – Resume text extraction
•	BeautifulSoup + requests – GitHub scraping
•	LangChain + Google Gemini API – AI-powered evaluation
•	dotenv – Environment variables handling

