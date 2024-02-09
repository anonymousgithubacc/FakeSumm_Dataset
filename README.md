# Fakesumm Dataset 📚

Fakesumm Dataset repository contains dataset generated using the method proposed in the paper titled `Creating a Dataset by Controlled Generation of MisInformation via Adversarial Prompting on LLMs.`

## Overview ℹ️

The Fakesumm Dataset comprises data focused on four categories of misinformation:

- Fabrication 
- Misrepresentation 
- False Attribution 
- Inaccurate Quantities 

Each JSON file in this repository contains a JSON object with the following fields:

- `article`: The original article used for generating summaries.
- `correct_summary`: The correct summary of the article generated using Large Language Models (LLMs).
- `incorrect_summary`: An incorrect summary of the article generated using LLMs.
- `explanation`: This field provides an explanation of the incorrectness present in the incorrect summary.
- `incorrectness_type`: Type of incorrectness present in the incorrect summary.

## Files 📁

1. `fakesumm_dataset.json`: Contains the entire generated dataset, covering all four categories of misinformation.
2. `fabrication_dataset.json`: Dataset specifically focused on fabrication misinformation.
3. `misrepresentation_dataset.json`: Dataset specifically focused on misrepresentation misinformation.
4. `false_attribution_dataset.json`: Dataset specifically focused on false attribution misinformation.
5. `inaccurate_quantities_dataset.json`: Dataset specifically focused on inaccurate quantities misinformation.

## Usage 🖥️

Researchers and practitioners can utilize the Fakesumm Dataset for various purposes, including:

- Evaluating the robustness of language models against misinformation.
- Training and benchmarking models for misinformation detection and summarization tasks.
