
# Mission 1 — Find AI Around You

## Objective

The goal of this mission is to identify AI/ML systems that I interact with in everyday life and understand what they are used for.

##  AI Systems Around Me

| System / Feature | What I Think It Does | AI/ML Function |
|---|---|---|
| **YouTube Recommendations** | Suggests videos based on my viewing history, searches, likes, and other interactions. | Recommends and predicts |
| **Google Maps** | Suggests routes and estimates travel times based on traffic and road conditions. | Predicts and recommends |
| **Smartphone Keyboard** | Predicts the next word and automatically corrects typing mistakes. | Predicts and recognises |

##  Evidence of AI/ML Involvement

### YouTube Recommendation System

I selected YouTube's recommendation system for further investigation.

YouTube uses machine-learning models in its recommendation system. The system uses different signals from users, including:

- Clicks
- Watch time
- Likes and dislikes
- Sharing
- Search and viewing behaviour

These signals are used to learn user preferences and predict which videos a user is likely to find interesting.

**Official source:**

[YouTube — On YouTube's Recommendation System](https://blog.youtube/inside-youtube/on-youtubes-recommendation-system/)

## Conclusion

AI and machine learning are already part of many technologies that I use every day. They are commonly used to recognise patterns, make predictions, and provide personalised recommendations. YouTube is a clear example because its recommendation system uses machine-learning models to predict what content users may be interested in.


# Mission 2-AI,ML,GenAI

##
- AI:- It is a part of computer science that tht build systems to mimic human intelligence like reasoning , thinking etc.
- ML :-It is a subset of AI which which learns patterns from raw data to make decisions or predictions. Ex :Spam detection, fraud detection 
- Deep Learning :- It is  subset of ML which uses neural networks with multiple layers to learn complex patterns from data. ex: Face recognition
- Generative AI :Its creates new contents based on the patterns learned from training data. ex:chatgpt can write an email, explain technical concept
<img width="1211" height="652" alt="image" src="https://github.com/user-attachments/assets/eeee7631-55cb-4b40-9044-19e1fa02a773" />

## ASK AI Agent(chatGPT) assistant to explain the diagram

AI: Make machines intelligent.

ML: Make machines learn from data.

Deep Learning: Use deep neural networks to learn from data.

Generative AI: Use learned models to generate new content.

# Mission 3- Is it really AI?
## Classification

| System | Classification | Reason |
|---|---|---|
| Calculator | Rule-based / Traditional Software | It follows explicitly programmed mathematical rules to calculate the result. |
| Temperature warning rule | Rule-based / Traditional Software | It checks a predefined condition, such as `if temperature > 40°C`, and gives a warning. |
| Spam filter | ML-based AI | It can learn patterns from previous spam and non-spam emails to classify new messages. |
| Document summariser | Generative AI | Modern summarizers can use language models to understand a document and generate a new shorter version. |
| Traffic ETA prediction | ML-based AI | It can learn from historical traffic, road conditions, time, and other data to predict travel time. |

## Short Explanations

### 1. Easy classification
The **calculator** was easy to classify because its behavior is explicitly programmed. 
For example, when we enter `5 + 3`, the calculator follows mathematical rules and produces `8`. 
It does not need to learn from data.

### 2. Difficult classification
The **spam filter** was more difficult to classify because some spam filters use simple rules, while modern spam filters can use machine learning. 
A rule-based filter might block an email containing a specific word, while an ML-based filter learns patterns from many examples of spam and legitimate emails.

### 3. My own example
**Face unlock on a smartphone** is mainly **ML-based AI**. 
It learns or recognizes patterns in facial features and compares them with the registered user's face. 
Unlike a simple rule-based system, it does not rely only on explicitly written rules for every possible face.

## Anchor Question

**Are explicitly written rules the same as a model learning a pattern?**

No. Explicit rules and learned patterns are different.

- **Rule-based software:** A human explicitly defines the rules.
- **Machine learning:** The system learns patterns from data.
- **Generative AI:** A trained model learns complex patterns from large amounts of data and generates new content.

For example:


Rule-based:
IF temperature > 40°C
THEN show "High Temperature"

Machine Learning:
Given thousands of temperature and sensor examples,
learn a pattern that predicts whether a situation is dangerous.

# 4. Make AI explain itself,then test it
  ## AI (chatgpt) answer 1: 
 An LLM takes your prompt, converts it into tokens and numerical representations, processes their relationships using a Transformer, and repeatedly predicts the most appropriate next token until it forms a complete response.
## Explain to me as a beginner using a simple example?
  A very large neural network that has learned patterns from enormous amounts of data and generates text by repeatedly predicting what token should come next given the context.

# Mission 5 - Can AI be confidently wrong? 
## Prompt : Can you explain what a loss function is and how it impacts the training of machine learning models?
## AI answer : What is a loss function?
#### A loss function tells a machine-learning model how wrong its prediction is.
    Think of it as a score for the model's mistake.
    Small loss = good prediction 
    Large loss = bad prediction
    
#### Verification Source : https://www.geeksforgeeks.org/deep-learning/loss-functions-in-deep-learning/

#### Result : Answers are matching
#### Lesson : AI Can make mistakes, but verification of answers are also important.

# Mission 6 - Chatbot or agent?
 ### LLM : An LLM is the language-processing engine that understands your prompt and generates text.
 <img width="5504" height="3440" alt="image" src="https://github.com/user-attachments/assets/c4a04b5e-c8ac-477c-8f8d-93dc39a82dcd" />

 ### AI application : An AI application is a complete software product that uses AI to perform a useful task.
 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7612a404-8830-47c8-919d-960eebb0a8fb" />

 ### RAG : RAG allows an LLM to answer questions using information retrieved from external documents or databases.
### Tool-using assistant : A tool-using assistant can call external software or services to perform specific operations instead of only generating text.
### AI agent : An AI agent goes beyond answering a single question. It can work toward a goal by planning steps, using tools, observing results, and adjusting its actions.
<img width="1400" height="933" alt="image" src="https://github.com/user-attachments/assets/17b60453-2f05-4612-808d-9ac332118cf6" />
