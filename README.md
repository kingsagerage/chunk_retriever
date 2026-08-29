# chunk_retriever
Simple Jupyter Notebook which uses Tesseract to read a set of pdf files and retrieve relevant text based on whatever information you'd be interested in


It works by reading in the pdf files, extracting as much text from it as possible and then writing into an ungodly large txt file. You'll be prompted after running the notebook through to "ask a question" when you can then offer related words to whatever information you're interested in, it'll retrieve the relevant chunks in a typical RAG style and leave them to you in "retrieved_chunks.txt". The original idea for this is to then feed it to an LLM to summarize, but you can also just look through it yourself.
