readme_code = """cv = {
    "personal_information": {
        "name": "Nguyen Pham Minh Huy",
        "title": "Research Analyst / Consultant",
        "phone": "0394780329",
        "email": "nguyenhuy2601k@gmail.com",
        "location": "District 7, Ho Chi Minh City",
        "linkedin": "https://www.linkedin.com/in/nguyen-pham-minh-huy-64a850281/",
        "dob": "Jan 26th 2005"
    },
    "career_goal": (
        "Detail-oriented and motivated Investment Economics professional with proven experience "
        "in data analysis, market research, and consulting through multiple internships in finance, "
        "pharmaceuticals, and real estate, seeking to contribute analytical, research, and problem-solving "
        "skills in a junior-level role within finance, consulting, or research."
    ),
    "experience": [
        {
            "company": "Deltamv Knowledge Solutions",
            "period": "11/2023 - 10/2024",
            "position": "Operation Fresher - Data Analyst (Part-time)",
            "responsibilities": [
                "Conduct market research with top pharmaceutical companies and give strategies for new products.",
                "Work on data entry, cleaning, matching, visualization, and dashboard creation for internal use.",
                "Provide customer service support and execute taxation invoices.",
                "Write and update SOPs; control cash flow and make payments according to scope of work."
            ]
        },
        {
            "company": "VPBank Securities JSC",
            "period": "10/2024 - 03/2025",
            "position": "Investment Consultant Trainee",
            "responsibilities": [
                "Conduct corporate financial market research and update regular reports.",
                "Consult investors to understand their investment preferences and design personalized portfolios.",
                "Organize internal and external workshops to share market trends and promote media channels.",
                "Manage a 600-million VND portfolio and contribute to a 22% return in 3 months."
            ]
        },
        {
            "company": "Cushman & Wakefield",
            "period": "03/2025 - 09/2025",
            "position": "Research Analyst and Strategic Consultant",
            "responsibilities": [
                "Perform data analysis and modeling for real estate research (market entry, feasibility, development proposals).",
                "Conduct deep research in industrial and residential sectors; produce quarterly and client reports.",
                "Lead field trips to support F&B corporate relocation projects.",
                "Consulted for major developers in District 7 (residential, office, retail).",
                "Completed mixed-use and appraisal projects yielding IRR 15% and $25M capital recovery.",
                "Initiated data transformation from Excel to Python and Power BI.",
                "Participated in SEA data center research with the India team."
            ]
        }
    ],
    "personal_projects": [
        {
            "title": "Research on the Influence of Voting and Review System on User Psychology and Behavior",
            "period": "6/2024 - 8/2024",
            "role": "Project Leader",
            "details": {
                "respondents": "300+",
                "tools": ["SPSS", "SmartPLS", "Excel", "Power BI", "SQL", "Qualtrics"],
                "achievements": [
                    "Designed the research framework and sampling strategy.",
                    "Led data collection, analysis, and interpretation on user satisfaction.",
                    "Findings recognized by UEH and under review for publication."
                ]
            }
        },
        {
            "title": "The Influence of Financial Pressure on Student's Academic Performance",
            "period": "6/2024 - 12/2024",
            "role": "Project Leader",
            "details": {
                "respondents": "250+",
                "tools": ["SPSS", "Python", "Excel", "Power BI", "Google Forms"],
                "achievements": [
                    "Conducted structured study on the impact of financial constraints.",
                    "Performed literature review and statistical analysis using SPSS/R.",
                    "Proposed policy recommendations for student support."
                ]
            }
        }
    ],
    "education": {
        "program": "Investment Economics / International Program",
        "university": "University of Economics Ho Chi Minh City",
        "period": "2023 - 2026",
        "gpa": "3.88 / 4.0",
        "achievements": [
            "High distinction and early graduation by April 2026.",
            "Excellent ambassador of UEH for FIBBA recognition."
        ]
    },
    "skills": [
        "Python", "R", "Excel", "Power Query", "Power BI",
        "Critical thinking", "Communication", "Negotiation",
        "Time management", "Problem-solving",
        "Self-motivation", "Attention to detail", "Presentation", "Storytelling"
    ],
    "awards": [
        {"year": 2023, "detail": "Direct acceptance to UEH for high academic performance."},
        {"year": 2022, "detail": "Top 3 excellent student at high school and scholarship recipient."},
        {"year": "2018-2023", "detail": "Local ambassador for solidarity and patriotism program."}
    ],
    "certificates": [
        {"year": 2022, "title": "IELTS Academic Certificate"},
        {"year": 2023, "title": "Business Analysis (LinkedIn)"},
        {"year": 2023, "title": "Fundamentals of Digital Marketing"},
        {"year": 2023, "title": "Microsoft Office Specialist (Word, Excel, PowerPoint)"},
        {"year": 2024, "title": "SQL and Data Visualization Certificate"}
    ],
    "activities": [
        {
            "period": "2023 - Now",
            "organization": "Voluntary English Teaching Club",
            "role": "Regular Partner",
            "description": [
                "Teach free English for disadvantaged children in Ho Chi Minh City.",
                "Raise funds for orphanages and pagodas supporting homeless and disabled children.",
                "Contact sponsors and organize social networks to expand volunteer outreach."
            ]
        }
    ]
}
"""

with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_code)
