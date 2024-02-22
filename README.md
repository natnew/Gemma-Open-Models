# Gemma-Open-Models
Gemma is a family of lightweight, state-of-the-art open models built from the same research and technology used to create the Gemini models.

![](https://github.com/natnew/Gemma-Open-Models/blob/main/Gemma.png)


| Preview                                                                                                                                                                                                                                     | Description                                                                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [<img src="https://www.nvidia.com/content/nvidiaGDC/us/en_US/glossary/generative-ai/_jcr_content/root/responsivegrid/nv_container_684078787/nv_image.coreimg.svg/1685574370254/evaluate.svg" width="150" />](https://www.nvidia.com/content/nvidiaGDC/us/en_US/glossary/generative-ai/_jcr_content/root/responsivegrid/nv_container_684078787/nv_image.coreimg.svg/1685574370254/evaluate.svg)    | [ The three requirements of a successful generative AI model.](https://www.nvidia.com/en-us/glossary/generative-ai/) |
| [<img src="https://www.nvidia.com/content/nvidiaGDC/us/en_US/glossary/generative-ai/_jcr_content/root/responsivegrid/nv_container_871136465/nv_image.coreimg.svg/1685574370784/usecases.svg" width="150" />](https://www.nvidia.com/content/nvidiaGDC/us/en_US/glossary/generative-ai/_jcr_content/root/responsivegrid/nv_container_871136465/nv_image.coreimg.svg/1685574370784/usecases.svg)    | [The diagram shows possible generative AI use cases within each category.](https://www.nvidia.com/en-us/glossary/generative-ai/) |
| [<img src="https://news.mit.edu/sites/default/files/styles/news_article__image_gallery/public/images/202310/MIT-AI-Shift-01-press.jpg?itok=gDETOcEM" width="150" />](https://news.mit.edu/sites/default/files/styles/news_article__image_gallery/public/images/202310/MIT-AI-Shift-01-press.jpg?itok=gDETOcEM)    | [AI models that prioritize similarity falter when asked to design something completely new.](https://news.mit.edu/2023/generative-ai-must-innovate-engineering-design-1019) |
| [<img src="https://developer-blogs.nvidia.com/wp-content/uploads/2022/04/GANs_Diffusion_Autoencoders.png" width="150" />](https://developer-blogs.nvidia.com/wp-content/uploads/2022/04/GANs_Diffusion_Autoencoders.png)    |  [Generative learning trilemma](https://developer.nvidia.com/blog/improving-diffusion-models-as-an-alternative-to-gans-part-1/) |
| [<img src="https://blogs.nvidia.com/wp-content/uploads/2022/03/Transformer-apps-1280x875.jpg.webp" width="150" />](https://blogs.nvidia.com/wp-content/uploads/2022/03/Transformer-apps-1280x875.jpg.webp)    | [What Can Transformer Models Do?](https://blogs.nvidia.com/blog/what-is-a-transformer-model/) |
| [<img src="https://blogs.nvidia.com/wp-content/uploads/2022/03/Switch-Transformer-842x440.jpg.webp" width="150" />](https://blogs.nvidia.com/wp-content/uploads/2022/03/Switch-Transformer-842x440.jpg.webp)    |  [MoE Means More for Transformers](https://blogs.nvidia.com/blog/what-is-a-transformer-model/) |

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

---
## Contributing
Contributions welcome! See the Contributing Guide.

---

## Getting help
Please use the issues page to provide suggestions, feedback or submit a bug report.

---

## Disclaimer
This repository itself is not an officially supported Google product. The code in this repository is for demonstrative purposes only.
