# Local Phi-3 HTML Chat Assistant & Image Router

A sleek, dark-mode ChatGPT-style web interface built to run local AI models on your own machine. Features smart markdown code segmentation, text-to-clipboard parsing, and an integrated external image query router.

## 🚀 Setup Requirements

To use this application, you must have **Ollama** running locally on your computer.

1. Download and install [Ollama](https://ollama.com).
2. Open your terminal/PowerShell and download the model:
   ```bash
   ollama run phi3:mini
   ```
3. Set your local server to allow browser traffic (CORS bypass):
   * **Windows Account Variables**: Add `OLLAMA_ORIGINS` with a value of `*` to your Environment Variables, then launch the Ollama app.
   * **Mac/Linux Terminal**: Start the service by running:
     ```bash
     OLLAMA_ORIGINS="*" ollama serve
     ```

## 🛠️ Tech Stack
* **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6 Fetch API)
* **Local Backend**: Ollama API Engine (`phi3:mini`)
