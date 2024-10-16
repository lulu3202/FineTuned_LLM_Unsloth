# FineTuned_LLM_Unsloth
This community notebook demonstrates fine-tuning a large language model for text completion using the Unsloth library and Hugging Face Transformer libraary. It covers model loading, LoRA setup, data preparation, training, and inference, enabling the generation of creative and engaging text. 

## Usage
1. Load the pre-trained LLM and tokenizer using `FastLanguageModel`.
2. Add LoRA adapters for efficient fine-tuning.
3. Load and format the Tiny Stories dataset.
4. Fine-tune the model using `UnslothTrainer`.
5. Enable inference mode with `FastLanguageModel.for_inference(model)`.
6. Generate text using `model.generate` with a given prompt.

## Example
The notebook provides a complete example of fine-tuning Mistral 7B on the Tiny Stories dataset. You can run also run this in Google Colab to see the results.

## Notes
- This notebook focuses on text completion tasks, but Unsloth can be used for other applications as well.

## Acknowledgments
- Unsloth library and its developers - https://github.com/unslothai/unsloth
- Hugging Face Transformers and TRL libraries - 
- Tiny Stories dataset creators

## Inference Screenshots
![image](https://github.com/user-attachments/assets/8c04c47c-9e24-4604-930f-2d75420c3bb3)
![image](https://github.com/user-attachments/assets/73046e6f-b2e4-413f-ba1f-98b61e40bef1)


