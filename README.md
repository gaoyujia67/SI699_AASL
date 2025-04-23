# A Third-Party Analysis of the AASL Standards
**Partnered client**: American Association of School Librarians (AASL)

**Course**: University of Michigan, School of Information —— MSI Mastery Course (SI 699)

**Authors**: Yujia Gao, Jinren Yuan

## Introduction
This project was conducted in partnership with the American Association of School Librarians (AASL). Our primary goal was to analyze stakeholder feedback gathered through surveys and focus group interviews to support future revisions of the *National School Library Standards for Learners, School Librarians, and School Libraries* (referred to as the *Standards* hereafter). The project focused on responses from five key stakeholder groups: **School Librarians**, **Educators**, **Stakeholders** (containing Administrators and Collaborators), and **State Chapters**. We examined their feedback through four key lenses:
- Utilization – How the *Standards* are used in practice
- Strengths – What users value most
- Challenges – Common pain points and barriers
- Suggestions – Ideas for future revisions

## Running the Code
The codebase is located in the `src/` directory. Each Jupyter Notebook corresponds to the analysis and visualizations for one stakeholder group (except for State Chapter). Inside the `src/` directory, the `data/` folder contains `.csv` files with survey responses from all stakeholder groups, while the `themes/` folder includes manually labeled topics for school librarians’ open-ended responses.

For the School Librarians group, we used the `BERTopic` library to assist with topic modeling. Due to its dependencies, we recommend creating a new virtual environment before installing it. All other required libraries are listed in the `requirements.txt` file and can be installed with:

```
pip install -r requirements.txt
```

For the State Chapter group, we opted for a direct qualitative summary instead of code-based analysis due to the relatively small number of responses. This approach allowed for a close, detailed interpretation that aligned with the limited data available.

## Acknowledgments
We’d like to thank AASL for partnering with this course and providing us the opportunity to work on a project with real-world impact in the library and education space.
