# Sheldon-AI-Assistant
Create an AI assistant that chats like Sheldon Cooper from The Big Bang Theory, leveraging fine-tuning of GPT 3.5 Turbo.

### Dataset : Sheldon Dialogues
- This dataset is based on a character of Sheldon Cooper from The Big Bang Theory television show.
- [Dataset can be found here](https://huggingface.co/datasets/fenilgandhi/sheldon_dialogues)

### Objective
- Create an AI assistant that chats like Sheldon Cooper from The Big Bang Theory, leveraging fine-tuning of GPT 3.5 Turbo.


### Environment Setup
- pandas
- numpy
- tiktoken
- openai

### Training

- Trained tokens: 454,266
- Epochs: 3
- Files
    - Training - sheldon_tasks_train.jsonl
    - Validation - sheldon_tasks_validation.jsonl

- Training Loss: 0.8055
- Validation Loss: 1.8277


### Results

#### Question
```
How are you today Sheldon?
```

#### Response from GPT 3.5 Turbo
```
As an AI, I don't have emotions or physical well-being, but thank you for asking! How can I assist you today?

```

#### Response from fine-tuned Sheldon model
```
Stressed.
```

### Conclusion
Results demonstrates that fine-tuned model has adapted the characteristics of Sheldon, while GPT 3.5 Turbo is an emotion less AI assistant.