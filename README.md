# byteplus-python-ark

[![License: MIT](https://shields.io)](https://opensource.org)
[![License: Apache 2.0](https://shields.io)](https://opensource.org)

A lightweight, zero-configuration Python Command Line Interface (CLI) to interact with Doubao AI models via the official international BytePlus Ark API. Built entirely without complex overhead.

## Features
* **Streaming Responses:** Watch the AI text generate live in your terminal.
* **Official SDK Integration:** Powered directly by the official `byteplus-python-sdk-v2` runtime.
* **Dual Licensed:** Open-source software available under both the MIT and Apache-2.0 licenses.

## Installation

Install the official international BytePlus platform architecture package via pip:

```bash
pip install -r requirements.txt
```

## Setup & Configuration

Before running the tool, you must configure your secure developer keys inside your environment variables. 

### On Linux / macOS:
```bash
export BYTEPLUS_ARK_API_KEY="your_actual_api_key_here"
export BYTEPLUS_ARK_ENDPOINT_ID="your_model_endpoint_id_here"
```

### On Windows (Command Prompt):
```cmd
set BYTEPLUS_ARK_API_KEY=your_actual_api_key_here
set BYTEPLUS_ARK_ENDPOINT_ID=your_model_endpoint_id_here
```

### On Windows (PowerShell):
```powershell
\$env:BYTEPLUS_ARK_API_KEY="your_actual_api_key_here"
\$env:BYTEPLUS_ARK_ENDPOINT_ID="your_model_endpoint_id_here"
```

## How to Run

Execute the tool directly from your terminal by passing your question inside quotation marks:

```bash
python ark_cli.py "Explain quantum computing in three short sentences."
```

## License

This project is dual-licensed under both the **MIT License** and the **Apache License 2.0**. You may choose either license for your distribution and modifications. See the `LICENSE` file for full statutory text.
