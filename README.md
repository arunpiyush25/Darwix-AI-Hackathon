# 🚀 Mission 1: The Empathetic Code Reviewer  

## 📌 Project Overview  
This project was built as part of the **Darwix AI Hackathon** under the theme *"Freedom from Mundane: AI for a Smarter Life"*.  

The goal of Mission 1 is to create an **empathetic AI-powered code reviewer**.  
Instead of only pointing out mistakes, the reviewer provides feedback that is:  
- Encouraging (positive rephrasing of comments)  
- Clear (explains *why* a change is important)  
- Actionable (includes improved code examples)  

The program produces a **well-formatted Markdown report** that can be displayed inside Colab and also saved as a `.txt` file.  

---

## 📂 Project Files  
├── DarwixAI_Hackathon.ipynb # Main Jupyter Notebook (Google Colab code)
├── requirements.txt # Python dependencies
├── empathetic_code_review.txt # Example generated review report (output)
└── README.md # Project documentation (this file)


---

## ⚙️ Setup & Requirements  
This project was developed in **Google Colab**, so most dependencies are already available.  
For local use, install requirements with:  

```bash
pip install -r requirements.txt

## Dependencies:
1) IPython (for Markdown display inside notebooks)
2) markdown (to render markdown output outside of notebooks)

## How to Run:
1) Open DarwixAI_Hackathon.ipynb in Google Colab or Jupyter Notebook.
2) Run all cells in order.
3) The program will:
- Show the original code snippet.
- Analyze each review comment.
- Generate empathetic, principle-backed feedback.
- Save the final Markdown report as empathetic_code_review.txt.

## Example Output:
Example section from the generated report:
### Analysis of Comment: "This is inefficient. Don't loop twice conceptually."
- **Positive Rephrasing:** Nice work outlining the approach! There’s a meaningful optimization within reach. With a small refinement, we can make it more efficient and maintainable.
- **The 'Why':** Efficient iteration and comprehension-based constructs scale better with large inputs.
- **Suggested Improvement:**
```python
def get_active_users(users):
    return [user for user in users if user.is_active and user.profile_complete]


---

##  Features  
- Converts raw, blunt comments into **empathetic, supportive feedback**.  
- Links improvements to **software engineering principles** like readability, performance, and conventions.  
- Provides **direct code suggestions** (transformed code snippets).  
- Generates a **Markdown report** that is both human-readable and easy to share.  

---

##  Hackathon Relevance  
This solution addresses the evaluation criteria:  
- **Functionality & Correctness (25%)** → Produces the required Markdown report.  
- **Quality of AI Output & Prompt Engineering (45%)** → Feedback is contextual, nuanced, and empathetic.  
- **Code Quality & Documentation (20%)** → Well-structured functions with comments and a clean notebook format.  
- **Innovation & Stand-Out Features (10%)** → Goes beyond basic review by adding tone adaptation and concrete transformations.  

---

##  License  
This project is submitted for the **Darwix AI Hackathon** and is intended for educational and demonstration purposes.  
