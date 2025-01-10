# 🐣🌱 FineTuning SmolLM2-135M for Medical Dataset
Fine-tuning a lightweight language model using **unsloth** to enhance its performance on medical instructions and knowledge-based tasks.

## 💼 Resources

- FineTuned model on HuggingFace - https://huggingface.co/mayura25/SmolLM2-135M-medical-dataset-finetuned
- Base model used for finetuning - https://huggingface.co/unsloth/SmolLM2-135M-bnb-4bit
- dataset used for finetuning - https://huggingface.co/datasets/Shekswess/medical_llama3_instruct_dataset_short
  
## 📊 Comparison between the results of FineTuned and original model

| Sr. NO | Input | Original Model | FineTuned Model |
|---------|-------------|------|---------|
|1. |	What are the causes of hypertension?|### Input: What are the causes of hypertension? ### Input: What are the causes of hypertension? ### Input: What are the causes of hypertension? ### Input: What are the causes of hypertension? ### Input: What are the causes of hypertension? |Hypertension is a common condition that affects millions of people worldwide. It is characterized by high blood pressure (hypertensive) and is often associated with other medical conditions, such as kidney disease, heart disease, or stroke. In this course, we will focus on the causes of hypertension, which include genetic factors, lifestyle|
|2. |How is asthma diagnosed?|### Input: |The diagnosis of asthma is made by a thorough history of the patient's symptoms, a physical examination, and a thorough medical history. The physical examination includes a history of the patient's symptoms, a physical examination, and a thorough medical history. The physical examination includes a history of the patient's symptoms, a physical examination, |
|3. |	Can you provide a brief summary of Hashimoto's thyroiditis?|### Input: Can you provide a brief summary of Hashimoto's thyroid |Hashimoto's thyroiditis is an autoimmune disorder that affects the thyroid gland. It is characterized by hypothyroidism (low thyroid function) and hyperthyroidism (overactive thyroid function). The thyroid gland is a small gland located in the neck that produces hormones that regulate metabolism. The thyroid gland is located in the neck and is attached to the |
|4. |What is the difference between Type 1 and Type 2 diabetes?|Type 1 diabetes is characterized by hyperglycemia (high blood sugar) and hyperlipidemia (high blood fat). Type 2 diabetes is characterized by hyperglycemia (high blood sugar) and hyperlipidemia (high blood fat). ### Example: Type 1 diabetes is characterized|Type 1 diabetes is an autoimmune disorder that occurs when the body's immune system attacks and destroys the beta cells in the pancreas. Type 1 diabetes is usually diagnosed in children and young adults. Type 1 diabetes is usually treated with insulin injections. Type 2 diabetes is a condition that occurs when the body does not|
|5. |What are the early signs of Alzheimer's disease?|### Input: ### Input: ### Input: ### Input: ### Input: ### Input: ### Input: ### Input: ### Input: ### Input: ### Input: ### Input: ### Inpu |Early signs of Alzheimer's disease include: 1. Memory loss 2. Difficulty in performing familiar tasks 3. Problems with language 4. Problems with thinking 5. Problems with judgment 6. Problems with judgment 7. Problems with walking 8. Problems with swallowing 9. Problems with judgment |

## 📈 Key Improvements
- 🩺 Domain-Specific Knowledge: Enhanced understanding of medical terminologies and context.
- 💬 Natural Responses: Generated answers are more detailed and conversational.
- ⚡ Efficiency: Achieved fine-tuning with minimal computational resources using a compact model.

## 🌟 Why It Matters
- 👩‍⚕️ Healthcare Applications: Enables better patient interaction and medical query handling.
- 📦 Lightweight Solution: Ideal for deployment on resource-constrained devices.
- 🔬 Research Advancements: Contributes to the development of domain-specific language models.

## 🎉 Outcome 
The FineTuned SmolLM2-135M **outperforms** its base model in medical scenarios, making it a valuable tool for healthcare AI!
