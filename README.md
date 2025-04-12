
#  BNS Legal Assistant – Interactive Tool for Young Legal Professionals ⚖

##  Problem Statement

Young legal professionals, interns, and junior associates often face the challenge of navigating large and complex legal codes, especially when they're still gaining experience. With the introduction of the **Bharatiya Nyaya Sanhita, 2023 (BNS)**, there's a pressing need for:

- Quick access to specific legal sections
- Easy-to-understand explanations of dense legal text
- Practical examples and effects of each law
- A way to identify relevant laws from keywords or legal situations

Traditional PDFs or static books don't offer searchability, keyword mapping, or intuitive navigation, leading to inefficiencies and missed insights in daily practice.

---

##  Solution: Interactive Legal Reference Tool (Jupyter Notebook)

This project introduces a **Python-based Legal Assistant** built on a structured dataset of the BNS 2023. It runs in a Jupyter Notebook environment and provides:

-  **Search by Section or Keyword**: Instantly find sections using either their number (e.g., `S. 3`) or by typing related legal terms (e.g., `punishment`, `commutation`, `counterfeiting`).
-  **Plain-Language Summaries**: View simplified explanations of each section, perfect for quick understanding or courtroom prep.
-  **Real-World Illustrations**: See hypothetical examples to understand how the law applies.
-  **Practical Legal Effects**: Know the real-world outcomes of each legal provision.
-  **Built for Daily Use**: Acts like a junior associate—ready to assist you in research, drafting, or client consultation.

---

##  How to Use

1. **Launch Jupyter Notebook**.
2. **Load the Dataset**:
   Ensure `BNS-Dataset.csv` is in the same directory as your notebook.
3. **Run the Provided Python Code**:
   The notebook will define a search tool.
4. **Call the Function**:

```python
search_bns("S. 3")         # For specific section
search_bns("commutation")  # For keyword-based search
