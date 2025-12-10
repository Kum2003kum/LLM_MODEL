# LLM Fine-Tuning for Disease Suggestion Based on Symptoms

## Project Overview
This project demonstrates the fine-tuning of a small, open-source Large Language Model (LLM) to suggest the closest potential disease pattern based on a list of patient symptoms from a structured dataset.

The model is trained to output a structured response that includes the predicted condition, a brief explanation, and a mandatory medical safety disclaimer.

## Technical Details
* **Base Model:** `TinyLlama/TinyLlama-1.1B-Chat-v1.0`
* **Fine-Tuning Method:** QLoRA (Quantized Low-Rank Adaptation)
* **Training Epochs:** 2 epochs
* **Dataset Source:** Kaggle Disease and Symptoms dataset.

## Repository Contents
| File Name | Description |
| :--- | :--- |
| `llms.ipynb` | https://colab.research.google.com/drive/1qM2kiIjb8Erx4YWQytOthtnLdIiSupOJ?usp=sharing |
| `train.jsonl` / `test.jsonl` | https://drive.google.com/drive/folders/115vYK2Grr9ayv0_vk66Fa4rw4eBGnARH?usp=sharing |
| `confusion_matrix.png` | https://drive.google.com/drive/folders/115vYK2Grr9ayv0_vk66Fa4rw4eBGnARH?usp=sharing |
| `demo_query_output.txt` | https://drive.google.com/drive/folders/115vYK2Grr9ayv0_vk66Fa4rw4eBGnARH?usp=sharing |

## Demo Video (Mandatory Submission)
https://drive.google.com/file/d/1Ra9vqRcr479HBWHVOUWO4rq6jcRIogGM/view?usp=sharing
