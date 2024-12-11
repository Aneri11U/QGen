# QGen

# Question Generator System

The **Question Generator System** is an advanced tool designed to generate questions based on provided context. Leveraging state-of-the-art NLP techniques and models, this system aims to automate the creation of high-quality questions for various applications like assessments, e-learning, and content review.

## Key Functionalities

1. **Keyword Extraction**:
   - Combines **RAKE**, **TF-IDF**, and **spaCy** for comprehensive and accurate keyword extraction from the given context.

2. **Question Generation**:
   - Utilizes a pre-trained **T5 model** to generate contextually relevant questions from extracted keywords and mapped sentences.

3. **Options Generation**:
   - Creates multiple-choice options that are contextually relevant to the generated questions.

4. **Question Assessment**:
   - Scores generated questions based on **relevance**, **complexity**, and **spelling correctness** to ensure high-quality outputs.

5. **Feedback Collection**:
   - Allows users to provide feedback on the quality of questions, tracks the feedback, and provides detailed statistics for future improvements.

## Key Features

- **Comprehensive Keyword Extraction**: Leverages multiple keyword extraction methods for enhanced accuracy.
- **T5-Based Question Generation**: Uses a pre-trained T5 model for precise question formation.
- **Context-Aware Options Generation**: Provides multiple-choice options relevant to the context.
- **Question Quality Assessment**: Automatically scores questions based on key quality metrics.
- **User Feedback Integration**: Collects and incorporates feedback for continuous improvement.

## Flow diagram of the application:
![architecture](https://github.com/user-attachments/assets/c7e7b6f1-b121-47c1-b1fc-70e75baf36d3)

## Customization Options

The system allows users to customize several key aspects to suit their specific requirements:

- **Number of beams** for question generation (to control the diversity of generated questions).
- **Context window size** for mapping keywords to sentences.
- **Number of questions** to generate from the input context.
- **Display preferences** for elements such as context, answer, options, entity links, and QA scores.

## Outputs

The system provides the following outputs for user convenience:

- **Generated questions**: Questions generated from the input context, along with their multiple-choice options.
- **Export options**: Download the output in **CSV** and **PDF** formats for easy sharing and review.
- **Performance visualization**: Graphical representation of the overall **question quality scores**, including relevance, complexity, and spelling correctness.

This system is designed for flexibility, scalability, and ease of use, making it an ideal choice for educational institutions, e-learning platforms, and content creators seeking to automate the process of question generation.

