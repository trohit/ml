- Src Playlist: [https://www.youtube.com/playlist?list=PLTPXxbhUt-YWSR8wtILixhZLF9qB_1yZm | Src Playlist]
- [https://www.youtube.com/playlist?list=PLTPXxbhUt-YWjMCDahwdVye8HW69p5NYS| DataBricks LLM playlist]
- [https://www.edx.org/learn/computer-science/databricks-large-language-models-application-through-production]

# LLM Large Language Model


# What
- large lang model is a lang model trained on enourmous data
  - an avg human reads about 700 books in their lifetime : 1 book : 80k words : 110k tokens
  - ChatGPT trained on 10 mill books : trillions of tokens
- LLM are of two types
  - Generative: Creates a statistical model based on probability and determines the next most likely word
  - Classification: determine most likely classification or answer
- can generate songs, fill in the blanks, complete sentences, classify reviews as good | bad
- describe pics, add captions to text
- can reduce dev cost and reduce monotonous tasks
- Examples of tools using NLP / LLM : DALL-E, Stable Diffusion, Midjourney
## History
![image](https://github.com/trohit/ml/assets/466385/c4018d1e-3ffc-4b70-a78c-2f40a036258a)
- NLP superset of (Language Models which is a superset of (LLM) ) )
- whata a lang model : computational model that takes a seq of things like tokens and predicts the most likely word
	- types classification | generative
 	- classification: prediction is usually trying to uncover a masked word
    	- generative : predict the best word to come next
- large Lang models: when lang models grow from 10-50 mill params to billions of params   
![image](https://github.com/trohit/ml/assets/466385/1a400969-e4e8-476b-bf7a-7bc7ad01eb8c)

# Why
# How

## NLP Definitions
![image](https://github.com/trohit/ml/assets/466385/26bd797f-a614-47dc-a3a1-57fa676417cd)

- token: basic building block: can be composed of letters, words or short phrases
  - OOV : Out-of-vocab : meaning the word is not part of a token seen by the LLM. could also be due to mispelling
- sequence: sequential list of tokens
- vocab: complete list of tokens
- embedding
- hallucinations: a tendency to invent facts in moments of uncertainty
  - https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)
  - https://towardsdatascience.com/llm-hallucinations-ec831dcd7786
- agent
- vector DB
- temperature
- prompt


## Uses of NLP
NLP Uses
- Sentiment analysis: eg of seq-to-seq generation
- translation : seq -to-non-seq prediction
- FAQ answering like chatbots : seq-to-seq generation
- Other usecases
	- semantic similarity
		- literature search | DB query | QA matching
	- Summarization
		- clinical decision support | news article sentiments | legal proceeding summary
	- text classification
		- cust review sentiments | genre , topic classification
  	- speech generation and recognition
# Process
- Tokenization: Transforming text into word pieces
- 
## Uses


- Conversational
- Fill Mask
- Question Answering
- Sentence Similarity
- Summarization
- Table Q &A
- Text Classification
- Text Generation
- Token Classification
- Translation
- Zero Shot Classification

# Choosing the Right LLM
![image](https://github.com/trohit/ml/assets/466385/5b482318-9789-43ca-b011-b58f4aae8896)
- Model Quality
- Serving Cost
- Serving Latency
- Customizability

## Popular NLP Tools
- Hugging face transformers
  - Hosts Models |datasets |Spaces
  - Key libs: datasets |transformers | evaluate
  - Under the hood libs uses PyTorch | TensorFlow| Jax
- NLTK
- SpaCy
- Gensim
- OpenAI
- SparkNLP (John Snow Labs)
- Langchain
