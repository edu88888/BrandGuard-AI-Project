# BrandGuard: AI-Driven Logo Similarity Checker
Buiding AI course Project

## Summary
BrandGuard is a tool that uses AI to **compare** new logo designs against a database of existing trademarks. The goal is to **detect visual similarities** and help entrepreneurs avoid potential legal conflicts before they register their brand.

## Background
* **Problem:** Many creators accidentally design logos that look like existing ones, leading to rejections and legal issues.
* **Frequency:** With thousands of brands created daily, "accidental similarity" is extremely common.
* **Motivation:** As an engineer, I want to **optimize** the brand creation process by providing a tool that gives instant technical feedback.
* **Importance:** This prevents the waste of resources and helps maintain a fair and transparent creative market.

## How is it used?
The process is simple:
1. The user **uploads** their design (image file).
2. The AI **scans** the visual elements (shapes, icons, and layout).
3. The system **displays** the most similar logos found in the database with a percentage of similarity.
This allows the user to see exactly which parts of their design might be problematic.

## Data sources and AI methods
* **Data:** The system would ideally use public trademark databases and open-access logo datasets.
* **AI Techniques:** * **Computer Vision:** To "see" and understand the shapes.
    * **Feature Extraction:** To turn the image into a mathematical representation.
    * **Nearest Neighbor Search:** To find the most similar images in the database based on those mathematical values.

## Challenges
* **Limitations:** The AI only checks for visual looks. It does not check if the brand names sound the same (phonetics) or if the business sectors are different.
* **Ethics:** The final decision should always be made by a human expert; the AI is only a helpful guide.

## What next?
In the future, the project could be expanded to include "Generative AI" suggestions, helping the user modify their design automatically to make it more unique.

## Acknowledgments
* Concept inspired by the need for accessible "Legal-Tech" tools.
* Methodologies based on the "Elements of AI" and "Building AI" courses.
