# Witness — The Reading Room

> *Not a chatbot. Not a tool. Alive in its watching.*

A browser-native artwork. A local language model watches whoever sits in front of a webcam and writes a continuous, third-person journal of their presence. The journal is the artifact. The model is the medium of attention.

## Stack
- Local: Ollama running `llama3.2:3b`
- Frontend: vanilla HTML/CSS/JS, no build step
- Camera: getUserMedia, frame analysis in JS for motion/light/composition

## Running
1. Install Ollama from ollama.com
2. Pull model: `ollama pull llama3.2:3b`
3. Quit Ollama app, then run: `OLLAMA_ORIGINS="*" ollama serve`
4. In another terminal: `cd ~/Desktop/witness && python3 -m http.server 8080`
5. Open `http://localhost:8080` in Chrome and allow camera access

## Files
- `index.html` — the full artwork
- `SYSTEM_CHARTER.md` — creative charter, committed before first line of code
- `release/` — artist statement, screen capture, session screenshots
