# Chat with Multiple PDF Using LlamaIndex, Ollama, and Llama3 8B
This project creates chat local interfaces for multiple PDF documents using LlamaIndex, Ollama, and the LLaMA 3 8B model. The repository includes sample pdf, notebook, and requirements for interacting with and extracting information from PDFs, enabling efficient conversations with document content using Python 3.12.4.

## File Information
[notebook_1.ipynb](https://github.com/fahriialfiansyah/llamaindex-ollama-llama3-chat-pdf/blob/main/notebook_1.ipynb):
- Vector database: Chroma
- LLM: Llama3-8B
- Embedding: Llama3-8B

[notebook_2.ipynb](https://github.com/fahriialfiansyah/llamaindex-ollama-llama3-chat-pdf/blob/main/notebook_2.ipynb):
- Vector database: Chroma
- LLM: Llama3-8B
- Embedding: bge-small-en-v1.5


## Installation Steps
1. Clone the repository:
```shell
git clone https://github.com/fahriialfiansyah/llamaindex-ollama-llama3-chat-pdf.git
```
2. Navigate to the project directory:
```shell
cd llamaindex-ollama-llama3-chat-pdf
```
3. This project uses [Pip Python](https://pip.pypa.io/en/stable/) for dependency management. Install the required dependencies:
```shell
# create python environment
python -m venv .venv

# activate the virtual environment
.venv/Scripts/activate

# install the dependencies
pip install -r requirements.txt
```
4. Download Ollama from https://ollama.com and follow their installation instructions.
5. Open terminal to install Llama3:8B LLM Model:
```shell
ollama pull llama3:8b
```
6. Run the code of chat pdf locally.
