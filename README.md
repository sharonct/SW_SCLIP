# Fine-Tuning CLIP for Swahili Semantic Video Search

## Introduction

The growing adoption of artificial intelligence (AI) in language processing has largely focused on high-resource languages, leaving underrepresented languages like Swahili with limited support. This research addresses this gap by fine-tuning the pre-trained Contrastive Language-Image Pretraining (CLIP) model to handle Swahili queries effectively. Leveraging transfer learning, the study adapts the model to understand and generate meaningful responses to Swahili text. By utilizing a specialized dataset of Swahili text-image pairs, the fine-tuned model is trained to capture the contextual and semantic intricacies of the Swahili language.

The primary objective is to develop a robust system capable of performing semantic video searches based on Swahili queries. This advancement aims to enhance accessibility and usability for Swahili-speaking users, fostering inclusivity in AI technologies. Beyond semantic search, this research contributes to the broader field of low-resource language AI applications.

## Features

- **Fine-tuned CLIP model:** Adapts the pre-trained CLIP architecture to understand Swahili text.
- **Swahili text-image dataset:** Utilizes a curated dataset of Swahili text-image pairs to improve model performance.
- **Semantic video search:** Enables users to search videos based on Swahili queries.
- **Transfer learning approach:** Leverages existing AI models to minimize training costs and improve accuracy.

## Dataset

The dataset comprises Swahili text paired with relevant images and video frames. This data is structured to enhance the CLIP model's ability to associate Swahili text with visual content effectively.

## Model and Training

The project employs:

- **Transformers Library:** Utilizing `CLIPProcessor`, `CLIPModel`, and multilingual models such as `XLM-Roberta`.
- **PyTorch Framework:** Implements the training pipeline using PyTorch and its dataset handling capabilities.
- **Fine-Tuning Strategy:** Trains the CLIP model with Swahili text inputs, refining embeddings for better multilingual understanding.

### Training Pipeline

1. **Data Preprocessing:** Cleans and tokenizes Swahili text, aligns it with image data.
2. **Model Fine-Tuning:** Optimizes CLIP embeddings using contrastive loss.
3. **Evaluation:** Tests performance using Swahili queries and measures semantic retrieval accuracy.


