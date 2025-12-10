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
| `llms.ipynb` | The fully executed Google Colab notebook. |
| `train.jsonl` / `test.jsonl` | The prepared training and testing data for the LLM. |
| `confusion_matrix.png` | Visual evaluation showing the model's performance on the test set. |
| `demo_query_output.txt` | The structured output for the required test query (`Fever, headache, body pain`). |

## Demo Video (Mandatory Submission)
https://drive.google.com/file/d/1Ra9vqRcr479HBWHVOUWO4rq6jcRIogGM/view?usp=sharing
