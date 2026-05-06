# Agent Design Document

## Agent 1 — Resume Analyzer

**Purpose:** Extracts structured information from 
student resume

**LLM Used:** Claude 3.5 Sonnet

**Input:** Plain text resume pasted by student

**Output:**
- Basic Info (Name, Degree, College, CGPA)
- Technical Skills
- Projects
- Certifications
- Internships
- Profile Strength Score out of 10

**Tools Used:** None (LLM only)

**Key Concept:** Prompt Engineering + 
Structured Information Extraction

**Status:** ✅ Built and tested

---

## Agent 2 — Web Search Agent

**Purpose:** Searches web in real time for current 
job market data

**LLM Used:** Claude 3.5 Sonnet

**Input:** Target role (e.g. Software Developer)

**Output:**
- Current skills required in 2026
- Top hiring companies and selection process
- Fresher salary range in India
- Market trend analysis

**Tools Used:** Google Search, Web Search, Perplexity

**Key Concept:** Tool Calling + Real Time Data Retrieval

**Status:** ✅ Built and tested

---

## Agent 3 — JD Match Agent

**Purpose:** Compares student resume against a real 
job description

**LLM Used:** Claude 3.5 Sonnet

**Input:** Resume text + Job Description text

**Output:**
- JD Summary
- Match Score out of 10
- Matched skills ✅
- Missing skills ❌ with learning time
- Resume improvement tips
- Final verdict

**Tools Used:** Web Search

**Key Concept:** Comparative Document Analysis + 
Semantic Matching

**Status:** ✅ Built and tested

---

## Agent 4 — Roadmap and Mock Interview Agent

**Purpose:** Generates personalized preparation plan 
and mock interview questions

**LLM Used:** Claude 3.5 Sonnet

**Input:** Student profile + Target role

**Output:**
- 4 week preparation roadmap with free resources
- 5 mock interview questions with hints
- 3 quick wins for today

**Tools Used:** Web Search

**Key Concept:** Personalized Content Generation

**Status:** ✅ Built and tested
