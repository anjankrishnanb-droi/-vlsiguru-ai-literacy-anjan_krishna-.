
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
    
#### Verification Source : 
https://www.geeksforgeeks.org/deep-learning/loss-functions-in-deep-learning/

#### Result : 
Answers are matching
#### Lesson : 
AI Can make mistakes, but verification of answers are also important.

# Mission 6 - Chatbot or agent?
 ### LLM : 
 An LLM is the language-processing engine that understands your prompt and generates text.
 <img width="5504" height="3440" alt="image" src="https://github.com/user-attachments/assets/c4a04b5e-c8ac-477c-8f8d-93dc39a82dcd" />

 ### AI application : 
 An AI application is a complete software product that uses AI to perform a useful task.
 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7612a404-8830-47c8-919d-960eebb0a8fb" />

 ### RAG :
 RAG allows an LLM to answer questions using information retrieved from external documents or databases.
### Tool-using assistant :
A tool-using assistant can call external software or services to perform specific operations instead of only generating text.
### AI agent :
An AI agent goes beyond answering a single question. It can work toward a goal by planning steps, using tools, observing results, and adjusting its actions.
<img width="1400" height="933" alt="image" src="https://github.com/user-attachments/assets/17b60453-2f05-4612-808d-9ac332118cf6" />

# Mission 7 : What actually runs AI?
1. What is a CPU and what is it good at?

A CPU (Central Processing Unit) is the main general-purpose processor of a computer. It executes program instructions and controls many operations of the system.

What is it good at?

Executing sequential instructions.

Making decisions using conditions such as if-else.

Handling operating system tasks and application logic.

Managing different types of workloads.

Example: A CPU runs the operating system, opens applications, and controls the overall execution of a program.

2. What is a GPU and why is it useful for AI workloads?

A GPU (Graphics Processing Unit) is a processor designed to perform many calculations in parallel.

Unlike a CPU, which typically has a smaller number of powerful general-purpose cores, a GPU contains many processing units that can perform large numbers of similar operations simultaneously.

Why is it useful for AI?

AI models perform many matrix and vector calculations.

GPUs can execute many of these calculations in parallel.

They can significantly speed up neural network training and inference.

Example: A GPU can multiply large matrices used in neural network calculations much faster than a CPU in many suitable workloads.

3. What is an NPU / AI accelerator and why do modern systems use specialised hardware?

An NPU (Neural Processing Unit) is a processor designed specifically to accelerate neural network operations.

An AI accelerator is a broader term for specialised hardware designed to speed up AI calculations. An NPU is one type of AI accelerator.

Why do modern systems use specialised hardware?

To execute AI operations efficiently.

To reduce power consumption for suitable workloads.

To improve performance for neural network calculations.

To run AI features locally on phones, laptops, and other devices.

Example: A smartphone NPU can accelerate on-device features such as image enhancement, speech recognition, and background blur during video calls.

4. What does parallel computation mean?

Parallel computation means performing multiple calculations at the same time.

Consider adding four pairs of numbers:

A = 2 + 3
B = 4 + 5
C = 6 + 7
D = 8 + 9

A sequential approach might calculate them one after another.

A parallel approach can calculate all four pairs simultaneously, provided sufficient processing units are available.

Why is it useful for AI?

Neural networks perform large numbers of mathematical operations. Many of these operations can be performed in parallel, reducing computation time.

5. Why does AI depend so heavily on compute and memory?

AI models require both computation and memory.

Compute

Compute refers to the ability to perform mathematical operations.

AI models use operations such as matrix multiplication to process input data and update model parameters.

Memory

Memory stores:

Model parameters (weights).

Input data and intermediate results.

Activations and gradients during training.

The context and key-value cache used by many LLMs during inference.

If the model is too large for available memory, it may not fit on the device or may require slower data transfers.

Example: A large language model needs enough memory to hold its weights and enough computational power to generate responses efficiently.

Therefore, both computational performance and memory capacity and bandwidth are important for AI.

6. What is the difference between training and inference from a hardware/computation point of view?

Feature

Training

Inference

Purpose

Teach the model by adjusting its weights.

Use the trained model to make predictions.

Computation

Forward pass, loss calculation, backpropagation, and weight updates.

Forward pass to generate predictions or outputs.

Memory

Stores weights, activations, gradients, and often optimizer state.

Stores weights, inputs, intermediate results, and any required cache.

Hardware demand

Often very high compute and memory requirements.

Depends on model size, speed requirements, and workload.

Example

Training a model to recognise cats and dogs.

Using the trained model to classify a new image.

In simple terms:

Training: The model learns from data.

Inference: The model uses what it has learned.

Training often requires more computation and memory per model update. However, large-scale inference can also require substantial hardware, especially when serving many users or generating long responses.

7. Draw a simple picture showing the AI hardware workflow
  
<img width="1096" height="1435" alt="image" src="https://github.com/user-attachments/assets/a640f509-ed73-46c7-9ee1-6c1b5a804ed6" />


Explanation

AI Application: Receives the user's input and manages the interaction.

AI Model: Defines the learned neural network used to produce an output.

Software / Framework: Prepares and schedules model operations for the available hardware.

CPU / GPU / NPU: Executes the required computations.

Memory: Holds model parameters, input data, and intermediate results.

Note: This is a simplified conceptual diagram. In a real system, data moves repeatedly between compute units and different levels of memory. The CPU may also coordinate the GPU or NPU, and the framework may select different processors for different operations.

8. Pick one real AI workload and explain which type of compute hardware would be useful and why

Workload: Running a local LLM chatbot

Imagine running a language model locally on a laptop to answer questions and summarise documents.

Useful hardware: GPU

A GPU is useful because:

LLMs perform many matrix and vector operations.

GPUs can perform many calculations in parallel.

GPU memory can hold model weights and intermediate data.

Sufficient memory bandwidth helps supply data to the compute units efficiently.

Role of other hardware:

CPU: Runs the operating system, manages application logic, and coordinates tasks.

GPU: Accelerates the neural network calculations.

NPU: May accelerate supported AI operations efficiently, depending on the laptop, model, and software.

RAM and accelerator memory: Hold the model and the data required for execution.

For a small, quantised model, a CPU may also be sufficient, although generation can be slower. The best hardware depends on model size, memory capacity, performance requirements, and power consumption.

Conclusion

Different types of processors are designed for different tasks. CPUs provide flexible general-purpose processing, GPUs accelerate parallel computations, and NPUs specialise in supported neural network operations.

AI systems need both compute and memory to process data and run models efficiently. Training adjusts model weights, while inference uses those trained weights to produce predictions and responses.

# Mission 8 — Where Could AI Help in My VLSI Track?

## Selected Area: Design Verification (DV)

| Item | Description |
|---|---|
| **VLSI Area** | Design Verification (DV) |
| **Task** | Debugging SystemVerilog testbenches and analysing simulation failures. |
| **How AI can help** | AI can analyse error messages, suggest possible bugs in SystemVerilog code, generate test scenarios, and help identify the cause of simulation failures. |
| **Why human knowledge still matters** | A verification engineer must understand the design specification, hardware protocols, timing behaviour, and verification requirements to validate AI suggestions and ensure the design works correctly. |

## Conclusion

AI is a capability that can improve the efficiency of Design Verification, but it cannot replace the domain knowledge of a verification engineer. Human expertise is still necessary to determine whether the generated test cases are meaningful and whether the verification results are correct.

**Anchor:** AI is not the domain. AI is a capability applied to the domain.
