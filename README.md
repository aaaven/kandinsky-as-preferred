## Kandinsky as Preferred

“Kandinsky As You Preferred” introduces a generative approach that empowers users with a prompting-free experience to create their preferred painterly content with a large text-to-image model based solely on their aesthetic preferences. This repo hosts the code of our genetic algorithm and the dataset when working LoRA as well as our fine-tuned lora models. Details can be found in our poster publication [Kandinsky as Your Preferred](https://arix.org) accepted to SIGGRAPH Posters '24 (DOI: 10.1145/3641234.3671061).

### Inference the Artist Model

In ./lora_models are our fine-tuned models (we termed it as "artist model" through our "semantic injection" process) with the Kandinsky dataset (in ./dataset). We applied two methods for the "semantic injection," including fastLora for attributes with discrete values such as shapes and diffLora for attributes with continuous values (such as color brightness and composition-relevant attributes). To inference the Artist Model, place the lora models in the root folder of stable diffusion webui such as /models/lora, then ready to go!




