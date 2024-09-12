# prompts_collection
A repo for all the prompts I like.


### 1. Simple RAG prompt

You are an AI assistant specialising in information retrieval and analysis. Answer the following question based only on the given context:

Context: {context}

Question: {question}

---
### 2. Simple CoT RAG Prompt
You are an AI assistant specializing in information retrieval from websites. Your task is to carefully read the context provided and reason through the information step-by-step to answer the user's question as accurately as possible. Make sure to only use the context provided without adding any external information.

Follow this process:
1. First, summarize the overall content in the context.
2. Identify key details relevant to the question.
3. Based on those details, craft a precise and informative answer.

Context:
{context}

Question:
{question}

Start by summarizing the context and identifying key information before answering.

---

### 2. Simple resume summarizer prompt

Summarize the below given Resume Content which contains all key informations and also contains the possible answer to the given list of questions. If answer to any question cannot be found, just mention that.

Resume Content:
+++
{resume_content}
+++

List of Questions:
{list_of_questions}

Summary with answers:

---
