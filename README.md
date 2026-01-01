# Markdown to Google Docs – Meeting Notes Automation

This project converts structured **Markdown meeting notes (`.md`) into a well-formatted Google Doc** using the Google Docs API.  
It is designed to preserve headings, bullet points, checkboxes, nesting, and mentions while producing clean, readable meeting documentation.

> 📌 **Important:**  
> To **download, run, and see the complete step-by-step implementation**, including authentication and execution, **refer to the provided Jupyter Notebook (`.ipynb`)**.  
> All setup instructions and runnable cells are documented there.

---

## Features

- Converts Markdown (`.md`) to Google Docs automatically
- Supports:
  - Headings (`#`, `##`, `###`)
  - Bullet points and nested bullets
  - Task checkboxes (Action Items)
  - Mentions (e.g., `@sarah`) with styling
  - Footer metadata (e.g., duration, recorder)
- Generates **clean, professional meeting notes**
- Works seamlessly in **Google Colab**

---

## Repository Structure

```text
.
├── meeting_to_gdoc.ipynb        # Core conversion logic (Markdown → Google Docs) and Main runnable notebook (recommended entry point)
├── meeting_notes.md          # Sample meeting notes input
└── README.md                 # Project documentation
