# Week 01 Questions
## Q1 - [AI → ML → Deep Learning → Generative AI → Agents]
### A - Answer
- Artificial Intelligence (AI): It is a field of computer science that aims to build systems that is capable of performing tasks as humans Intelligence, Ex : Thinking, reasoning , learning, image recognition etc.
- Ex: Google maps planning route
- Machine Learning(ML): It is a subset of AI which learns patterns from raw data to make decisions or predictions. Ex :Spam detection, fraud detection.
- Deep learning : Subset of ML that uses neural networks with multiple layers to learn complex patterns from data.
  ex: Face recognition
-  Generative AI : Its creates new contents based on the patterns learned from training data.
  ex:chatgpt can  write an email, explain technical concept.
-  AI agent : It is sytem that uses an AI Model to work towards a goal by deciding what to do.         Ex:chatbot repsonds to prompts.
 <img width="1211" height="652" alt="image" src="https://github.com/user-attachments/assets/a8a9dd12-5dd0-4ae1-a068-4948160a2f2c" />

    
### E - Evidence
- https://iwtlp.com/blog/ai-ml-dl-genai-llms-rag-agentic-ai-explained
- https://towardsdatascience.com/artificial-intelligence-machine-learning-deep-learning-and-generative-ai-clearly-explained/
### V - Verification
Google search
### R - Reflection

## Q2 - [Is Everything That Looks Intelligent Actually AI?]
### A - Answer
  - AI performs well on tasks it has learned but it can struggles when new situations are introduced. 
  - AI doesnot have human like feelings ,self awareness or personal experiences . It generates responses based on patterns and information.
  - AI can make mistakes when it encounters information or situations that are different from what it learned during training.
  - AI may not always understand wht is right or wrong in complex situations. It's answers can reflect the biases present in its training data.
  - Ai relies on data to learn patterns . If the data is insufficient , incorrect or biased the results may also be incorrect or biased.
### E - Evidence
  -https://aiagentmemory.org/articles/is-ai-really-that-intelligent/
### V - Verification
Google search
### R - Reflection
 The AI seems around us,it somewhat intelligent but not all fully intelligent. It requires human intervension when something goes wrong.
 
## Q3 - [What Happens When You Ask an LLM a Question?]
### A - Answer
  - Step 1 : Tokenization
     First of all the bigger sentence that we wrote is cut into small chunks called tokens.
  - Step 2 : Embeddings
    The tokens are converted in to numbers. The tokens that are close to each other get clustered together based on semantical meaning.
    -Step 3 : Attention
        LLM mechanism that allows the model to focus on the most relevant words in a sentence when processong a specific word.
    -Step 4 : Generation (Guessing)
     The model predicts the next token as a probability over all possible tokens, picks one, adds it to the text, and repeats. This sequential guessing continues until the response is complete.
        
### E - Evidence
https://medium.com/@kakadaaryan10/what-happens-when-you-ask-an-llm-a-question-explained-like-you-are-15-b4bc13b1f2ff
### V - Verification
Google search
### R - Reflection

## Q4 - [Hallucination Experiment: Can AI Sound Confident and Still Be Wrong?]
### A - Answer
  AI haluccinations occur when AI models generate false, misleading answers but they present it as     factual.
### Haluciantion test
Question : Give me the information of Quantum computing book written by  Anjan krishna
 ### Chatgpt Experiment
  ##### Answer Anjan, I searched online for a book titled Quantum Computing written by Anjan Krishna, but I couldn't find a verifiable book listing matching that author and title.
The search returned other material about quantum computing, but nothing that confirmed a book by that exact name. I also found an online profile for Anjan Krishna associated with VLSI and electronics engineering, but it does not establish that he has published a quantum computing book.

#### Claude experiment
 I don't know of any quantum computing book by Anjan Krishna, and I can't confirm that one exists. I could easily write a convincing title, publisher, year, and summary, but it would be invented, which is exactly the hallucination your experiment is about.

What I can say:

Anjan Krishna is a fairly common name, so even if a book exists, I can't tell which author it is.
I have no reliable record of the book, so I can't give a title, publisher, ISBN, or summary
### E - Evidence
https://community.ibm.com/community/user/blogs/anjaly-radhakrishnan/2026/03/23/when-ai-sounds-right-but-is-wrong-understanding
### V - Verification
Claude,Chatgpt
### R - Reflection
 AI can use confident wording for both well-supported and uncertain claims . which seems to be convincing for us.
## Q5 - [AI Assistant vs Search vs Authoritative Reference]
### A - Answer
#### Generative AI works
Generative AI search relies on three main systems:
  - Step 1:  LLM (Large Language Model) : An LLM is trained on massive amounts of textual data to learn a langauge patterns,structure and nuances.LLMs doesnot understand language in the human sense, but they provide a statistical model that mimics understanding.
  - Step 2 Embedding Model: Generative AI turns words into numerical format, known as vector.
  - Step 3 RAG (Retrieval Augmented generation ): RAG Is a technique for enhancing the accuracy and reliability of generative AI models with information fetched from specific and relevant data sources.
#### Search Engine 
  Step 1: Crawling : Google uses Automated programs called crawlers , The main crawler is Googlebot. Googlebot discovers web pages by following links from other pages. it adds the discovered pages to a queue and visits them to collect information.
  Step2: Rendering : After downloading the page , google processes its HTMl ,CSS and javascript to understand how the page appears and what content it displays.
  Step 3: Indexing : Google analyzes the pages contents and decides whether it should  be added to its search index , which is a huge database of information about webpages.Google tries to understand the page's topic and usefulness. Not every page is included in the index.
  Step 4: Ranking :When search on google , it looks through its index and uses ranking systems to decide which pages are most relevant to your query and in what order to display them.
  The results may include titles , descriptions and images.
### E - Evidence
https://www.matthewedgar.net/generative-ai-vs-traditional-search-technical-differences/
### V - Verification
Google search
### R - Reflection

## Q6 - [What Is an AI Agent?]
### A - Answer
AI agent uses Artificial intelligence and take actions towards a goal. AI Agent 
- Perceives : Collects and analyzes inormation from its environment
- Reasons : interprets the information and determines what needs to be done.
- Plans / decides : selects an appropriate action based on its goal.
- Acts : executes the action using tools or systems
- Evaluates: Observes the resul and adjusts its next action when necessary.
- Escalates : asks for human intervention when  it is unsafe and effectively complete the task.
<img width="724" height="358" alt="image" src="https://github.com/user-attachments/assets/a0f63300-63de-4ee0-9ddf-3a9361888bf3" />


### E - Evidence
https://www.geeksforgeeks.org/artificial-intelligence/agents-artificial-intelligence/
### V - Verification
Google search
### R - Reflection

## Q7 - [Where Should Humans Still Make the Decision?]
### A - Answer
# Where Should Humans Still Make the Decision?

## Why Does This Matter?

AI can help with reading documents, summarizing information, generating text, and suggesting actions. However, humans must remain responsible for checking important outputs before acting on them.

## Five Situations Requiring Human Verification


# Where Should Humans Still Make the Decision?

## Why Does This Matter?

AI can help with reading documents, summarizing information, generating text, and suggesting actions. However, humans must remain responsible for checking important outputs before acting on them.

## Five Situations Requiring Human Verification

| No. | Situation | Possible Failure if AI Is Not Verified | Required Verification / Evidence | Who or What Approves the Result? |
|---|---|---|---|---|
| 1 | AI generates SystemVerilog code for a testbench. | The code may contain syntax errors, incorrect logic, or fail to detect design bugs. | Compile the code, run simulations, check test results, and review functional coverage. | Design Verification Engineer |
| 2 | AI summarizes a technical document or specification. | It may omit important requirements or misunderstand a technical detail. | Compare the summary against the original specification and verify key requirements. | Engineer responsible for the specification |
| 3 | AI recommends a solution to a hardware safety issue. | An incorrect recommendation could cause hardware malfunction or unsafe behavior. | Check the relevant safety requirements, technical standards, simulation results, and test evidence. | Responsible safety engineer or authorized reviewer |
| 4 | AI analyzes financial information and recommends an investment. | It may use outdated information, make incorrect assumptions, or overlook financial risks. | Check current financial data, reliable sources, fees, risks, and personal financial circumstances. | Individual investor, with advice from a qualified financial professional when needed |
| 5 | AI drafts an important professional email or report. | It may include false information, disclose confidential data, or use inappropriate wording. | Verify names, dates, facts, recipient details, confidentiality, and the intended message. | The person sending or submitting the email or report |

## My Rule for Responsible AI-Assisted Work

I will use AI to support my work, not replace my judgment. Before acting on important AI-generated information, I will verify it using reliable evidence and obtain approval from the responsible person whenever necessary.
### E - Evidence
https://www.toolsgroup.com/blog/why-human-decision-making-matters-in-the-ai-age/
### V - Verification
Google search
### R - Reflection
Human + AI Smarter ,faster,Better decisions 
## Q8 - [Find AI Around You]
### A - Answer

# AI in Everyday Life

| No. | System / Application | AI/ML Involved? | Task Type | Evidence / Source | Conclusion |
|---|---|---|---|---|---|
| 1 | YouTube, TikTok and Instagram recommendations | Yes | Recommendation and prediction | [YouTube recommendations](https://support.google.com/youtube/answer/16089387) | Uses user activity and other signals to recommend relevant videos. A rule-based system could recommend popular videos by category but would provide less personalized results. |
| 2 | Google Photos – Face Groups | Yes | Facial recognition and classification | [Google Photos Help](https://support.google.com/photos/answer/6128838) | Uses face models and facial similarity to group photos that may contain the same person. It can sometimes group the wrong faces. |
| 3 | Google Lens, Circle to Search and OCR | Yes | Object recognition and text recognition | [Google Lens](https://lens.google/) | Uses AI-based visual recognition to identify objects and recognize text in images. Results may be inaccurate when images are blurry or unclear. |
| 4 | Gmail spam filter | Yes | Classification | [Google Workspace](https://workspace.google.com/blog/identity-and-security/an-overview-of-gmails-spam-filters) | Uses machine learning to identify spam emails. Legitimate emails may occasionally be marked as spam. |
| 5 | Netflix recommendations | Yes | Recommendation and ranking | [Netflix Help](https://help.netflix.com/en/node/100639) | Uses viewing activity and other information to personalize movie and TV recommendations. Suggestions may not always match the user's current interests. |

## Rule-Based Alternative

A simple rule-based recommendation system could recommend football videos whenever a user selects the football category. It could also recommend popular videos based on fixed rules.

This approach can work without machine learning, but it cannot learn complex user preferences as effectively as a personalized machine-learning system.

## Conclusion

AI and machine learning are used in many everyday applications for recognition, classification, prediction and recommendation. However, AI-generated results can be incorrect, so important results should be verified.

**Responsible AI rule:** Do not assume a product uses AI just because it appears intelligent. Look for reliable public evidence, and verify its output when accuracy matters.

### E - Evidence
https://beebom.com/examples-of-artificial-intelligence/
### V - Verification
google search
### R - Reflection

## Q9 - [Prediction, Classification, and Generation]
### A - Answer

# Prediction, Classification, and Generation

## 1. Classification of Examples

| No. | Example | Task Type | Reason |
|---|---|---|---|
| A | Predicting house prices | Prediction | The model estimates a continuous numerical value (the expected price of a house) using features such as location, size, and number of rooms. |
| B | Detecting whether an image contains a cat | Classification | The model assigns the image to a category, such as "cat present" or "cat absent." |
| C | Writing an email from a short instruction | Generation | The model creates new text based on the user's instruction. |
| D | Predicting whether a customer will cancel a subscription | Prediction | The model estimates the likelihood of a future event: whether a customer will cancel their subscription. |
| E | Summarizing a research paper | Generation | The model produces a shorter version of the original paper while preserving its main ideas. |
| F | Identifying whether a transaction is fraudulent | Classification | The model assigns the transaction to a category, such as "fraudulent" or "legitimate." |
| G | Generating an image from a text description | Generation | The model creates a new image based on the text prompt. |
| H | Predicting the next word/token in a sentence | Prediction | The model estimates which token is likely to come next based on the preceding context. |

## 2. Why Is Next-Token Prediction Fundamental to Modern Language Models?

Modern language models are trained to predict the next token based on the tokens that came before it. A token may be a complete word, part of a word, punctuation, or another text unit.

For example, given the input:

"The sky is"

The model may assign a high probability to the next token "blue."

The model generates text by repeatedly predicting and selecting the next token, then using the expanded text to predict another token. This process continues until the response is complete.

This basic ability supports many applications:

- **Writing:** Predicting successive tokens produces sentences and paragraphs.
- **Summarization:** Predicting tokens allows the model to create a shorter version of a document.
- **Coding:** Predicting tokens allows the model to generate programming statements and code.
- **Question answering:** Predicting tokens allows the model to construct an answer using the question and available context.

Although these applications look different, they can use the same underlying next-token prediction process.

Next-token prediction does not guarantee that the output is correct. A language model can produce fluent text that contains factual errors, so important answers and generated code still need verification.

## 3. Conclusion

Prediction estimates a value or likely outcome, classification assigns an input to a category, and generation creates new content.

Next-token prediction is a fundamental training and generation mechanism for many modern language models. By predicting tokens one after another, a model can produce text for many different tasks, including writing, summarization, coding, and question answering.

### E - Evidence
### V - Verification
### R - Reflection

## Q10 - [Design Your Personal AI Verification Protocol]
### A - Answer
### E - Evidence
### V - Verification
### R - Reflection



