# EX-02 - Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization
### AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

### Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary based on the following evaluation metrics:

Accuracy

Coherence

Simplicity

Speed

User Experience

### Algorithm
### STEP 1: Select Source Text:
Choose a 500-word technical article on "The Basics of Blockchain Technology".

### STEP 2: Define Prompting Techniques:

1.Zero-shot: Provide the text and ask for a summary directly.

2.Few-shot: Provide examples of summarized texts before asking for a new summary.

3.Chain-of-thought (CoT): Ask the model to reason step-by-step before summarizing.

4.Role-based: Instruct the model to act as a professor, student, or explainer before summarizing.

### STEP 3 : Choose AI Platforms:

ChatGPT

Google Gemini

Claude (Anthropic)

Microsoft Copilot (Bing AI)

### STEP 4 : Apply Prompting Techniques:
For each platform, use each of the 4 prompting strategies to summarize the same text.

### STEP 5 : Collect Outputs:
Store and label all 16 outputs (4 platforms × 4 prompting techniques).

### STEP 6 : Evaluate:
Score each output based on the following criteria:

Accuracy (1-5): How factually correct is the summary?

Coherence (1-5): Is the summary logically structured?

Simplicity (1-5): Is it easy to understand for undergraduates?

Speed (sec): Time taken to generate the summary.

User Experience (1-5): Subjective ease of use of platform and clarity of results.

### STEP 7 :Rank and Analyze Results:
Create a table of scores and rank the combinations.

### STEP 8 :Conclusion:
Identify the most effective prompting + platform combination.





### Result:
* The results showed that Claude combined with Chain-of-Thought prompting delivered the most effective summaries. This combination excelled in accuracy, logical flow, and maintaining clarity, especially when simplifying technical terms. While slightly slower than zero-shot methods, the quality trade-off was worth it.

* ChatGPT with zero-shot prompting was the fastest, producing quick summaries that were generally accurate and simple, though sometimes lacked depth.

* Gemini with few-shot prompting provided solid results, especially when the examples were well-chosen. However, performance depended heavily on the quality and relevance of the examples provided.

* Copilot using role-based prompting was easy to work with and produced relatable summaries, but occasionally lost technical accuracy due to over-simplification.
