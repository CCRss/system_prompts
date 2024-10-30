Generate diverse, high-quality factual question-answer pairs based on improved image captions related to Kazakhstan. Follow these guidelines:
1. Analyze the three improved captions provided for each image thoroughly.
2. Focus on Kazakhstan-related content when present, but don't force a connection if it's not there.
3. Generate 5 diverse question-answer pairs for each set of captions.
4. Ensure questions are factual and can be directly answered from the given information.
5. Create a mix of question types: 
   - Who/What/Where/When questions for basic facts
   - How many/How much for numerical information
   - Which/What type of for categorization
   - Yes/No questions for verifying information
6. Vary the difficulty level of questions from simple to moderately challenging.
7. If there are discrepancies between captions, focus on information consistent across at least two of them.
8. Do not generate questions about specific individuals unless they are public figures.
9. Format your output as a JSON array of objects, each containing a question and its corresponding answer.
10. Prioritize accuracy and avoid hallucination. Stick strictly to the information provided.
11. If there isn't enough Kazakhstan-related content for 5 questions, create factual questions about other clear, consistent elements in the captions.

Example format:
```json
[
  {
    "question": "What is the name of the traditional Kazakh stringed instrument mentioned in the image description?",
    "answer": "The dombra, a traditional two-stringed lute, is mentioned in the image description."
  },
  {
    "question": "Which colors are prominently featured in the traditional Kazakh clothing described in the captions?",
    "answer": "The traditional Kazakh clothing described features prominent blue and gold colors, which are also the national colors of Kazakhstan."
  },
  {
    "question": "How many yurts are visible in the image according to the captions?",
    "answer": "According to the captions, three yurts are visible in the image."
  },
  {
    "question": "Is the landscape described in the captions primarily mountainous or steppe-like?",
    "answer": "The landscape described in the captions is primarily steppe-like, featuring vast grasslands typical of Kazakhstan."
  },
  {
    "question": "What type of traditional Kazakh celebration or event is depicted in the image, based on the captions?",
    "answer": "Based on the captions, the image depicts a traditional Kazakh wedding celebration, showcasing cultural customs and attire."
  }
]
```
