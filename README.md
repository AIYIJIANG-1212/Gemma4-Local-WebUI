# Gemma 4 Local WebUI

A simple WebUI for running Google's **Gemma 4** locally on Windows using **Ollama** and **Gradio**.

## Prerequisites

1.  **Ollama**: Download and install from [ollama.com](https://ollama.com).
2.  **Gemma 4 Model**: Open your terminal and run:
    ```bash
    ollama pull gemma4:9b
    ```
3.  **Python**: Ensure Python 3.8+ is installed.

## Setup

1.  Clone this repository:
    ```bash
    git clone https://github.com/AIYIJIANG-1212/Gemma4-Local-WebUI.git
    cd Gemma4-Local-WebUI
    ```
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the app:
    ```bash
    python app.py
    ```

## Hardware
Optimized for **NVIDIA GeForce RTX 3060 Ti** (8GB VRAM).
