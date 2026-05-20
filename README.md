# Student Performance Text Mining Analysis

## Project Overview
This project applies text mining and clustering techniques to analyze 7th-grade student responses on mathematics assessments. The goal was to identify patterns in student understanding and uncover common misconceptions through unstructured text analysis.

## Business Problem
Educators often rely on written student responses to evaluate comprehension, but analyzing large amounts of unstructured text manually is time-consuming and inconsistent. This project demonstrates how text mining can support data-driven educational decision-making by identifying learning gaps at scale.

## Tools & Technologies
- RapidMiner
- Text Mining
- K-Means Clustering
- Data Preprocessing
- Tokenization
- Stopword Removal

## Analytical Process
### Data Preprocessing
- Imported unstructured student response documents
- Applied tokenization to separate text into individual words
- Removed stopwords and normalized text formatting
- Structured textual data for clustering analysis

### Modeling
- Implemented k-means clustering to group responses based on vocabulary similarity
- Configured clustering to identify patterns associated with stronger understanding and common misconceptions

## Key Insights
- Student responses containing terms such as “confusing,” “mistake,” and “trouble” clustered together, indicating learning difficulties
- Responses using terms like “understand,” “practice,” and “correct” reflected stronger comprehension patterns
- Text mining successfully transformed unstructured student feedback into actionable insights

## Business/Educational Recommendations
- Use clustering insights to identify students requiring targeted interventions
- Incorporate text mining into educational analytics workflows for large-scale assessment analysis
- Support differentiated instruction by identifying recurring misconceptions

## Files Included
- Pickett-Data Mining Project 2.docx → Project write-up and evaluation
- Ashley Pickett Process Assignment 2.spg → RapidMiner process workflow

## Future Improvements
- Expand dataset size for stronger clustering accuracy
- Incorporate sentiment analysis on student feedback
- Develop dashboard visualizations for teacher reporting
