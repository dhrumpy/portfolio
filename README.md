# Abhishek Parida - Portfolio

Data science and machine learning work by Abhishek Parida, Data Science faculty at the International College of Liberal Arts, Yamanashi Gakuin University, Japan. PhD in gravitational wave data science.

## Projects

### [RAG - student handbook](RAG%20-%20student%20handbook/)
Question answering over a student handbook PDF, built with LangChain and a FAISS index.
- Runs with OpenAI models, or with local models (mistral and mxbai-embed-large) through Ollama.
- Tested on 41 questions. The questions and both sets of answers are included.
- Includes a small chat app with saved conversation history.
- To run the OpenAI version, add your own API key to a `.env` file.

### [Embeddings from scratch](Embeddings%20from%20scratch/)
Language-model basics written from first principles.
- `tokenization_and_bpe.ipynb`: byte-pair encoding from scratch, and tokenizer comparisons (tiktoken, BERT).
- `train_next_word_embeddings.ipynb`: a next-word embedding model trained in PyTorch.
- `embedding_spaces_gpt2_bert.ipynb`: exploring GloVe, GPT-2 and BERT embeddings.

### [Kepler's Laws from Data](Kepler%27s%20Laws%20from%20Data/)
Rediscovering Kepler's three laws of planetary motion from NASA JPL Horizons data, using regression.
- Law 1: the fitted eccentricity of Mars matches the one computed from its distances (0.0934).
- Law 2: the area swept per day varies by about 0.002%.
- Law 3: the slope of log period against log distance is 1.5003 for the four inner planets.
- Includes the notebook, the data and the slides.
- Talk: [Machine Learning Use in Physics (YouTube)](https://www.youtube.com/live/FKhN9M6sKyc)

### [Selected Teaching Notebooks](Selected%20Teaching%20Notebooks/)
Notebooks from the courses I teach: data visualization, introduction to Python, machine learning, mathematics for data science, and a Python coding bootcamp.

## Running the notebooks
Open a notebook in Google Colab, or run it locally with Jupyter. The Kepler notebook reads its data from the folder next to it, so download the whole `Kepler's Laws from Data` folder before running it.
