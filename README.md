# Smart Contract Security Analysis
(Freelance Project)
This repository contains Jupyter notebooks that performs an analysis of various security measures on the specific chain

## Overview
### Aptos
- The `Aptos_smart_contract.ipynb` notebook includes the script to Finetune Llama3 8B on synthetic smart contract analysis data on `Move` for Aptos Chain.
- The `Aptos_SmartContract_Dataset.json` file includes the entire dataset used 
- The Model is stored here : [Huggingface Model](https://huggingface.co/SoumilB7/L3_8B_Aptos_Smart_Contract_Analyser)
- The dataset visualised is stored here : [Hugginface Dataset](https://huggingface.co/datasets/SoumilB7/AptosSC)


### Solana
- The `Solana_smart_contract.ipynb` notebook includes the script to Finetune Llama3 8B on synthetic smart contract analysis data on `Rust` for Solana Chain.
- The `Solana_SmartContract_Dataset.json` file includes the entire dataset used 
- The Model is stored here : [Huggingface Model](https://huggingface.co/SoumilB7/L3_8B_Solana_Smart_Contract_Analyser)
- The dataset visualised is stored here : [Hugginface Dataset](https://huggingface.co/datasets/SoumilB7/SolanaSC)


## Features

- **Data Analysis**: Detailed analysis of language-related vulnerabilities.
- **Fine-tuning**: Graphs and charts to help visualize the fine-tuning process.
- **Insights**: Key vulnerabilities and conclusions from the analysis.

## Installation

To run the notebook, you need to have the following packages installed:
Credits - Unsloth

```bash
pip install "unsloth[colab-new] @ git+https://github.com/unslothai/unsloth.git"
pip install --no-deps "xformers<0.0.27" "trl<0.9.0" peft accelerate bitsandbytes
