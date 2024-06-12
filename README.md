# Quizify

Quizify is an app made to help students study for tests leveraging Google Gemini. 

## Usage:
### Start Screen: Step 1 - Upload any number of PDFs
![start screen](https://github.com/Json-To-String/mission-quizify/assets/55477390/911bbf80-4616-4e8c-ad51-3195f5a9eadb)

### Step 2 - Choose how many questions to generate from the slider
![slider step](https://github.com/Json-To-String/mission-quizify/assets/55477390/e5ed386d-718e-4f05-b774-141e730a5991)

### Step 3 - Type in the topic of the quiz to generate, then press ENTER
![Step 2](https://github.com/Json-To-String/mission-quizify/assets/55477390/d36740e2-ee6c-4758-8d97-b85fbe4b2c9b)

### Step 4 - After the confirmation messages, click "Generate Quiz"
![generate quiz button](https://github.com/Json-To-String/mission-quizify/assets/55477390/632bf449-68aa-4ab3-909c-23467eb5e23c)

### Step 5 - Take your quiz and enjoy instant feedback on each question!
![quiz demo 1](https://github.com/Json-To-String/mission-quizify/assets/55477390/e0f25143-74a4-4ed5-8cb9-0bdde9bcf7f8)


## Technical Breakdown
Quizify is made to ingest any number of PDFs, compare them using Vertex AI embeddings, and store them using the vector database method of ChromaDB.
These, coupled with LangChain, allow us to harness multiple LLMs such as Vertex and Gemini to return helpful responses to quiz-takers and students.

One important part of Quizify is the instant feedback with explanations in a user-friendly environment. We also ensure that the questions generated 
unique to help maximize studying efficiency.


