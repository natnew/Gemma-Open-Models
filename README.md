# Gemma-models
Gemma is a family of lightweight, state-of-the-art open models built from the same research and technology used to create the Gemini models.

---

## Setup

### Get access to Gemma

To complete this tutorial, you will first need to complete the setup instructions at [Gemma setup](https://ai.google.dev/gemma/docs/setup). The Gemma setup instructions show you how to do the following:

* Get access to Gemma on [kaggle.com](https://kaggle.com){:.external}.
* Select a Colab runtime with sufficient resources to run
  the Gemma 2B model.
* Generate and configure a Kaggle username and API key.

After you've completed the Gemma setup, move on to the next section, where you'll set environment variables for your Colab environment.


### Select the runtime

To complete this tutorial, you'll need to have a Colab runtime with sufficient resources to run the Gemma model. In this case, you can use a T4 GPU:

1. In the upper-right of the Colab window, select &#9662; (**Additional connection options**).
2. Select **Change runtime type**.
3. Under **Hardware accelerator**, select **T4 GPU**.


### Configure your API key

To use Gemma, you must provide your Kaggle username and a Kaggle API key.

To generate a Kaggle API key, go to the **Account** tab of your Kaggle user profile and select **Create New Token**. This will trigger the download of a `kaggle.json` file containing your API credentials.

In Colab, select **Secrets** (🔑) in the left pane and add your Kaggle username and Kaggle API key. Store your username under the name `KAGGLE_USERNAME` and your API key under the name `KAGGLE_KEY`.



---
## Links
- [Model Card](https://ai.google.dev/gemma/docs/model_card)
- [Technical Resport](https://storage.googleapis.com/deepmind-media/gemma/gemma-report.pdf)
- [Guides](https://ai.google.dev/gemma/docs/?utm_source=agd&utm_medium=referral&utm_campaign=quickstart-docu&utm_content)
- [News](https://blog.google/technology/developers/gemma-open-models/)
- [Responsible Generative AI Toolkit](https://ai.google.dev/responsible?utm_source=agd&utm_medium=referral&utm_campaign=explore-responsible&utm_content)
- [Competition](https://www.kaggle.com/competitions/data-assistants-with-gemma/?utm_source=agd&utm_medium=referral&utm_campaign=join-competition&utm_content=)

---
## Partner quick-start guides

- [Hugging Face](https://huggingface.co/blog/gemma/?utm_source=agd&utm_medium=referral&utm_campaign=view-on-huggingface&utm_content=)
- [NVIDIA](https://github.com/NVIDIA/GenerativeAIExamples/tree/main/models/Gemma/?utm_source=agd&utm_medium=referral&utm_campaign=view-on-github&utm_content=)
