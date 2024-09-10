# LLM-for-automated-news-articles-generation

This repository implements Large Language Models (LLMs), including GPT-2, GPT-3.5, LLaMA 3 and Gemini to automate the generation of news articles. The repository also includes examples of generated news articles in both English and Spanish, along with datasets used for model training.

## Prerequisites

Ensure you have the following before running the project:

- Python 3.x
- Required libraries: `transformers`, `torch`, `pandas`, `sklearn`, among others.

All the necessary dependencies are specififed in each notebook

## Project Structure

The repository consists of the following key files and directories:

### Models:
- **GPT-2**: Implementation of the GPT-2 model for news generation, which has been fine-tuned and is available for free use.
- **GPT-3.5**: Requires users to fine-tune the model themselves and utilize it with their own API keys from OpenAI. Be aware that using GPT-3.5 comes with associated API usage costs.
- **LLaMA3**: A fine-tuned version of this model is also available for free use in the project.
- **Gemini**: Like GPT-3.5, this model requires training and usage under the user’s own Google API key, and costs associated with its API usage may apply.

The repository includes the fine-tuning code for each of the models mentioned, along with examples that demonstrate how to use each model individually. Users can refer to these examples to either fine-tune or deploy the models in their own workflows.

### Similar News Retrieval

- **Similar News Retrieval**: Contains a notebook that demonstrates how to retrieve similar news articles. This notebook provides examples and code to help users integrate news retrieval functionalities into their workflows.

### CSV Files:
- `News_Dataset_Complete.csv`: The full dataset of news.
- `News_Dataset_For_FT.csv`: Dataset specifically prepared for fine-tuning the models.
- `News_Generated_In_English.csv` and `News_Generated_In_Spanish.csv`: Examples of news articles generated in English and Spanish respectively.

## How to Use the Code

Follow these steps to run the models:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/BrauuHdzM/LLM-for-automated-news-articles-generation.git
   cd LLM-for-automated-news-articles-generation
   
2. **Open the notebook in Jupyter or Colab** for the model you wish to test (e.g., `GPT-2.ipynb` or `GPT-3.5.ipynb`).

3. **Run the cells** in the notebook to load the model, train it if necessary, and generate news articles automatically.

## Contributing

To contribute to this project, you can:

1. **Fork the repository.**
2. **Create a new branch** with your changes.
3. **Submit a pull request** for review.

Suggestions for improvement include:

- Expanding to other LLMs
- Fixing bugs
- Enhancing the code structure
