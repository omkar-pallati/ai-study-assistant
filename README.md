# PDF Study Assistant

Website (GitHub Pages) + AI backend (Google Colab).

- `index.html`: the website. Visitors upload a PDF or paste text, then take a quiz or make MCQs, 2-mark and long answers, blanks and summaries.
- `backend_server.ipynb`: run in Colab (T4 GPU). It runs the AI model and gives the website a public address.
- `config.json`: holds that public address. The website reads it on load. Colab can update it for you.
- `study_assistant.ipynb`: the standalone Colab version (also reads scanned PDFs).

Website: https://omkar-pallati.github.io/ai-study-assistant/
