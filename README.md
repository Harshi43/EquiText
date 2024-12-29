# Gender Bias Detector Tool

## Project Overview
This tool analyzes and detects gender bias in NCERT textbook texts, aiming to promote equitable representation in educational content. It uses Python-based NLP and machine learning methods to assess:
- **Gender Visibility**: Analyzing the frequency of male and female terms.
- **Contextual Tone**: Extracting sentences to understand how genders are portrayed.
- **Role Diversity**: Categorizing professions or roles linked to each gender.
- **Sentiment Analysis**: Measuring the tone (positive, negative, neutral) associated with gendered mentions.

### Why It Matters
This tool empowers educators and policymakers to identify and address unconscious biases in educational materials, fostering a more inclusive learning environment. It provides data-driven insights to challenge stereotypes and ensure balanced gender representation in textbooks.

---

## Setup Instructions

### Prerequisites
Ensure the following tools and libraries are installed:
- Python 3.8+
- pip (Python package manager)
- Basic familiarity with **Google Colab** (if using for execution).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/harshi43/gender-bias-tool.git
   cd gender-bias-tool

2. Install dependencies:
   pip install -r requirements.txt

3. Download SpaCy's language model:
   python -m spacy download en_core_web_sm

## Dependencies

The following python libraries aare required:
- nltk
- spacy
- pandas
- matplotlib
- transformers
- pdfplumber

Install them using:
pip install -r requirements.txt

## Usage Examples

1. Run the full script
   Use the following command to execute the hackathon.py file:
   python hackathon.py
   Expected Input:
   - Upload NCERT PDF files via the script's file upload functionality.
   Expected Output:
   - Extracted text saved in categorized .txt files
   - Gendered word analysis printed to the console.
   - Sentiment analysis and role categorization results stored or displayed.

2. Key Features in Action
   - Extract texts from PDFs:
   The script automatically processes uploaded PDFs to extract meaningful content.
   Expected Output: Categorized text blocks such as main content, side notes, and miscellaneous sections.
   - Preprocess Extracted Text:
   The script cleans and standardizes the text for further analysis.
   Expected Output: Preprocessed text, both with and without punctuation.
   - Analyze Gendered Words:
   The script counts occurrences of male and female gendered words and displays the results in the terminal.
   Expected Output:
   Male words: 45
   Female words: 30
   Examples of Male Words: ['he', 'man', 'father']
   Examples of Female Words: ['she', 'woman', 'mother']
   - Perform Sentiment Anakysis:
   The script evaluates the sentiment of sentences containing gendered words.
   Expected Output: Sentiment (Positive, Negative, Neutral) with confidence scores printed to the console.

## Team Members

   - Shubham Sharma: Developed the code for text extraction, preprocessing, and analysis.
   - Harshini Akana: Assisted with coding and data collection.
   - Shakti Kumar Roy 
   - Nabin Pandey 
   - Shravan





