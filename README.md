# Artificial-Intelligence-Final-Project-Handwriting-Recognition

This repository now includes an end-to-end handwriting processing pipeline that:

1. Takes an input image of handwritten text.
2. Runs OCR to extract letter/word sequences.
3. Applies word prediction/correction for noisy OCR output.
4. Exports the predicted text to both `.txt` and `.docx`.

## Quick start

Create and activate/install with your virtualenv (or use `.venv/bin/...` commands directly):

to do this     
Open the Command Palette (Ctrl+Shift+P / Cmd+Shift+P) and type "Python: Select Interpreter".
Choose the one labeled "(.venv): venv" or browse to the executable path manually:
        Windows: .venv\Scripts\python.exe
        macOS/Linux: .venv/bin/python

Activate in Terminal:

    Open a new terminal in VS Code (Ctrl+Shift+``). It should now automatically show (.venv)` at the start of your prompt.


Use the command to execute:
python handwriting_pipeline.py --image ".\demo_assets\demo_handwritten.png" --output-stem "outputs\predicted_words"

This creates:
- `sample_handwriting.png`
- `demo_output/predicted_words.txt`
- `demo_output/predicted_words.docx`
