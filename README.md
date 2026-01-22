# ShikshaLokam
Offline generative AI for education using on-device LLMs (no cloud, no internet).

# PathShala AI: India's 100% Offline AI Teaching Assistant

PathShala AI is a revolutionary educational tool designed to bring advanced generative AI to the "last mile" of education. It works completely offline, ensuring that students and teachers in rural or low-connectivity areas have access to high-quality teaching strategies without needing an internet connection.

## Key Features

- **100% Offline**: Once initialized, the AI model runs locally on your device. No data leaves your machine.
- **Bilingual Support**: Full support for both **English** and **Hindi**.
- **Voice Response**: Integrated Text-to-Speech (TTS) for accessibility, supporting both languages.
- **High Performance**: Optimized using **Llama 3.2 1B**, balancing intelligence with low RAM usage (~900MB).
- **Privacy First**: No tracking, no cloud storage, and no data mining.

## Technology Stack

- **Frontend**: Vanilla HTML5, CSS3 (Glassmorphism design), and JavaScript.
- **AI Engine**: [WebLLM](https://webllm.mlc.ai/) (Apache TVM) for in-browser inference.
- **Large Language Model**: Llama-3.2-1B-Instruct (Quantized for the web).
- **Hardware Acceleration**: WebGPU API for native performance inside the browser.

## How to Run

For the hackathon demonstration, you only need one file:

1.  Open **`pathshala_ai_demo.html`** in a modern browser (**Google Chrome** or **Microsoft Edge** are recommended).
2.  Ensure your browser supports **WebGPU** (usually enabled by default in recent versions).
3.  Click **"Start AI Model"**.
    - *Note: On the first run, it will download the ~900MB model. This will be cached automatically.*
    - *Subsequent runs will load instantly and works 100% offline.*
