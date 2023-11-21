# aiexperiments

Evaluating AI Capabilities in Language, Speech, and Vision
This repo contains code and details for preliminary hands-on experiments evaluating the latest AI models across key areas:

Experiments

Speech Transcription
dkwhisper.py
Assessed Whisper by Anthropic for automated transcription of a 70-min audio recording
Tested speed, accuracy, and cost on local hardware

Text Translation
dkspeechtotranslate.py
Combined Whisper + Llama2 by Meta for offline speech-to-text to text-to-text translation
Evaluated preservation of meaning from English to Spanish

Text-to-Speech
tts-demo.py
conversation.json
Example Conversation Here's an example of a conversation in JSON format that you can use as a template: { "conversation": [ { "speaker": "alloy", "text": "How are you today?" }, { "speaker": "fable", "text": "I'm doing well, thanks!" }, { "speaker": "alloy", "text": "That's nice to hear." } ] }
Leveraged OpenAI API to synthesize voice samples from generated text
Qualitatively assessed realism, clarity, and cost of neural voices

Object Recognition
Photofinderparm.py
storephoto.jpeg
Photofinderparm.py [image_file_path] '[custom_text_message]' Replace [image_file_path] with the path to your image file and [custom_text_message] with your desired text message for the API request.
Utilized GPT-Turbo Vision model to locate a specific product in a complex grocery store image
Measured accuracy and explored enhancement via segmentation

This project leverages APIs and resources from:
OpenAI: The OpenAI API is used for text-to-speech synthesis and object recognition via the Whisper models.Code snippets and guidance from OpenAI documentation were instrumental.
ChatGPT-3 was used for cost-effective script development, providing an efficient way to prototype and iterate. 
Meta: The Llama2 model from Meta is used for neural text translation. Documentation and resources informed integration.
Anthropic: We employed Claude from Anthropic for detailed script development and reporting. 
ollama.ai: For enabling the local hosting of AI models, particularly on a laptop setup. This facilitated efficient model deployment and testing directly within the project's development environment.
OpenCV: For image manipulation and analysis. The OpenCV library provided efficient capabilities.

Note: This code is experimental and may require modifications for production use cases.
