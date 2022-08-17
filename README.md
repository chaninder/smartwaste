# SmartWaste
A deep learning application to help you decide whether your household products belong in the trash, recycle, compost or e-waste. 

## How it Works

Confused if that egg-carton belongs in the trash or recycle? Not sure what to do with your dead batteries? Classify all you household waste by simply taking or uploading a picture of it on my website/app.

Under the hood, predictions are being made by a classification model that builds upon the classic MobileNetV2 model.

## Demo-Preview

See the model in production on HuggingFace Spaces: https://huggingface.co/spaces/chaninder/SmartWaste

Here is the model itself to be used for open-source purposes: https://huggingface.co/chaninder/waste-sorting-model

Here's how the app looks:

HOME:

Take a picture or upload one!

![Simulator Screen Shot - iPhone SE (3rd generation) - 2022-08-15 at 16 56 28](https://user-images.githubusercontent.com/110851085/185211307-d78af3ee-2de1-45fd-a32a-cd95811c6068.png)

After you've given the app a picture, it predicts the category of waste!

![Simulator Screen Shot - iPhone SE (3rd generation) - 2022-08-15 at 16 22 27](https://user-images.githubusercontent.com/110851085/185212375-907e9af2-1698-49a6-90a9-72cb43595645.png)


## Main tools and libraries used

- TensorFlow
- TensorFlow Lite
- Transfer Learning
- Flutter
- Gradio
- Google Collab
- Jupyter Notebook
- Visual Studio Code
