# SkillSync

SkillSync is a browser-based resume and career-role skill comparison prototype. It extracts text from an uploaded resume PDF, compares detected skills with a selected role profile, highlights matched and missing skills, and provides a 14-day learning roadmap for the top three gaps.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in Google Chrome or Microsoft Edge.
3. Upload a resume PDF.
4. Select a target career role and run the analysis.

Some PDF/OCR features load browser libraries from online CDNs, so an internet connection may be required.

## Project structure

```text
SkillSync/
├── index.html
├── README.md
└── sample-resumes/
    ├── Mechanical_Design_Engineer_Sample.pdf
    └── Data_Analyst_Sample.pdf
```

## Technology

- HTML for page structure
- CSS for styling and responsive layout
- JavaScript for PDF text processing, skill extraction, matching, and roadmap logic
- PDF.js for PDF text extraction
- Tesseract.js for OCR fallback where available

## Important limitations

This is a browser-only prototype and does not include a separate server-side backend. The selected career-role profiles are built-in reference profiles, not live employer vacancies. This role-profile workflow does not by itself demonstrate exact evidence from a specific employer job description or prove the M5 70% answer-key agreement target. Do not claim those requirements are met without implementing and testing them against labelled cases.

## Sample data

The PDFs in `sample-resumes/` are fictional test resumes provided only for software testing. Do not represent them as real candidates or submit them as actual applicants' resumes. Do not upload real personal resumes to a public repository without the owner's informed permission.
