# chat-with-ollama

A simple example of how to connect with a large language model (LLM) running on Ollama.

This example demonstrates running Ollama on your local machine and accessing it from your browser. Once it's running, you can edit the HTML file and experiment with different prompts, responses, and behaviors.

## Running the Example

### 1. Start Ollama
In a shell, start Ollama with a model (e.g., a Llama 3.1 model):

```bash
ollama run llama3.1
```

### 2. Serve the HTML File
Serve the `index.html` file with any HTTP server. For example, using `http-server`:

```bash
npx http-server
```

### 3. Access the Web Page
Open a browser and navigate to:

```
http://127.0.0.1:8080/index.html
```

## Idea Behind the Checked-in Prompt

**Q: Why use a kindergarten teacher as a persona?**

**A:** A kindergarten teacher explains concepts in very simple terms. This approach makes it easier to detect when the LLM model deviates from its initial prompt or intended behavior.
