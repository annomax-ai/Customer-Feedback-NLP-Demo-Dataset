# Customer Feedback NLP Demo Dataset

A Natural Language Processing (NLP) demo project focused on customer feedback annotation, sentiment classification, intent identification and data quality analysis.

This project demonstrates how unstructured customer feedback can be transformed into structured, labeled data and presented through an interactive analytics dashboard.

Developed as part of the **Annomax AI** data annotation portfolio.

## Project Overview

The project focuses on two primary NLP annotation tasks:

- **Sentiment Classification:** Identifying the sentiment expressed in customer feedback.
- **Intent Classification:** Identifying the primary purpose or reason behind a customer's message.

In addition to annotation, the project includes a dashboard that summarizes sentiment distribution, intent categories and annotation quality metrics.

## Dashboard Preview

![Customer Feedback NLP Dashboard](screenshots/dashboard%20preview.png)

## Dataset Overview

| Metric | Value |
|---|---:|
| Total Records | 50 |
| Sentiment Categories | 3 |
| Intent Categories | 7 |
| Annotators | 2 |
| QA Reviewers | 1 |
| QA Approved Records | 50 |
| QA Approval Rate | 100% |

## Sentiment Distribution

The dataset contains three sentiment categories.

| Sentiment | Records | Percentage |
|---|---:|---:|
| Negative | 29 | 58% |
| Neutral | 13 | 26% |
| Positive | 8 | 16% |
| **Total** | **50** | **100%** |

**Key Observation:**

Negative feedback represents the largest portion of the dataset, accounting for 58% of all records. Neutral feedback accounts for 26%, while positive feedback represents 16%.

## Intent Classification

Each customer review is assigned an intent label based on the primary purpose of the message.

| Intent Category | Records | Percentage |
|---|---:|---:|
| Complaint | 14 | 28% |
| Product Inquiry | 8 | 16% |
| Positive Review | 8 | 16% |
| Order Status | 6 | 12% |
| Cancellation | 5 | 10% |
| Technical Support | 5 | 10% |
| Refund Request | 4 | 8% |
| **Total** | **50** | **100%** |

## Dashboard & Data Visualization

The project includes an analytics dashboard designed to provide a visual overview of customer feedback and annotation results.

The dashboard presents:

- **Total Feedback Records:** Overall number of annotated customer reviews.
- **Sentiment Summary:** Number and percentage of Positive, Negative and Neutral reviews.
- **Sentiment Pie Chart:** Visual representation of sentiment proportions.
- **Sentiment Bar Chart:** Comparison of records across sentiment categories.
- **Intent Distribution:** Number of records assigned to each intent category.
- **Intent Bar Chart:** Comparison of different customer intent categories.
- **Annotation Summary:** Overview of annotator contributions.
- **QA Summary:** Approved records and overall QA approval rate.

### Dashboard Preview

![Customer Feedback NLP Dashboard](screenshots/customer_feedback_dashboard.png)

*Dashboard screenshot showing sentiment distribution, category summaries, percentages and visual comparisons.*

## Annotation Guidelines

### Sentiment Classification

| Label | Description |
|---|---|
| Positive | Expresses satisfaction or a favorable opinion. |
| Negative | Expresses dissatisfaction or an unfavorable opinion. |
| Neutral | Contains factual information without clear positive or negative sentiment. |

### Intent Classification

| Label | Description |
|---|---|
| Complaint | Reports a problem or expresses dissatisfaction. |
| Product Inquiry | Asks about product features or availability. |
| Positive Review | Shares a positive customer experience. |
| Order Status | Asks about order progress or delivery. |
| Cancellation | Requests cancellation of an order or service. |
| Technical Support | Requests assistance with a technical issue. |
| Refund Request | Requests a refund or reimbursement. |

## Annotation & Quality Assurance Workflow

The project follows a structured annotation and review process.

1. Prepare and organize raw customer feedback.
2. Assign unique identifiers to each record.
3. Annotate sentiment and customer intent.
4. Maintain annotator identification for tracking.
5. Conduct independent quality assurance reviews.
6. Record QA verdicts and reviewer comments.
7. Summarize annotation results through the dashboard.

### QA Summary

| QA Metric | Result |
|---|---:|
| Total Reviewed Records | 50 |
| Approved Records | 50 |
| Rejected Records | 0 |
| Approval Rate | 100% |

All 50 records in the provided dataset are marked as Approved.

## Dataset Structure

| Column | Description |
|---|---|
| Record_ID | Unique identifier for each review. |
| Review_Text | Original customer feedback. |
| Sentiment | Assigned sentiment category. |
| Intent | Assigned intent category. |
| Annotator | Identifier of the assigned annotator. |
| QA_Reviewer | Identifier of the quality reviewer. |
| QA_Verdict | Final QA review decision. |
| QA_Remarks | Reviewer comments and observations. |

## Sample Records

| Record ID | Review Text | Sentiment | Intent |
|---|---|---|---|
| REV001 | Best purchase I made this year, my family loves it. | Positive | Positive Review |
| REV002 | Can I change my order to a different colour or should I cancel it? | Neutral | Cancellation |
| REV003 | Can I get this in black? I only see white on the site. | Neutral | Product Inquiry |
| REV005 | Can someone please tell me where my package is? Nobody is replying. | Negative | Order Status |
| REV006 | Colour looks nothing like the pic on your site. | Negative | Complaint |

## Tools & Technologies

- **Google Sheets:** Data annotation, organization and validation.
- **Data Validation:** Controlled selection of annotation labels.
- **Conditional Formatting:** Visual identification of sentiment categories.
- **Dashboard & Charts:** Sentiment and intent analysis.
- **CSV:** Structured dataset storage and export.
- **JSONL:** Machine-readable dataset format.

## Repository Structure

```text
customer-feedback-nlp-demo-dataset/
│
├── data/
│   └── customer_feedback_annotated.csv
│
├── screenshots/
│   └── customer_feedback_dashboard.png
│
├── guidelines/
│   └── annotation_guidelines.md
│
├── README.md
└── LICENSE
```

## Potential Applications

This demo dataset can support experimentation and demonstrations involving:

- Customer sentiment analysis.
- Customer intent classification.
- Customer experience analytics.
- Customer service automation.
- Conversational AI systems.
- NLP model training and evaluation.

## Project Limitations

This is a small demonstration dataset containing 50 annotated customer feedback records. It is intended to showcase annotation workflows, classification methods, quality assurance and data visualization.

Further dataset expansion and validation would be required before using it for production-level machine learning applications.

## About Annomax AI

**Annomax AI** provides AI data annotation and quality assurance services to support machine learning and AI development.

Our focus includes structured data annotation, dataset preparation and quality validation for AI-driven applications.

**Website:** https://www.annomaxai.com/

---

*Part of the Annomax AI data annotation portfolio.*

---

*Note: This is a sample dataset for demonstration purposes. Please verify the image usage rights and licensing before redistributing the images or using them commercially.*
