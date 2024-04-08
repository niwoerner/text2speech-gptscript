# text2speech-gptscript

GPTScript tool to turn an input text into a speech using the OpenAI api. 

## Prerequisites
- OpenAI API key

## Usage
```
Tools: github.com/nw0rn/text2speech-gptscript

Create a speech:
- text: "hello world"
```

## Arguments 
```
Args: text: (required) The text to convert to speech.
Args: model: (optional) The name of the model to use. Default is "tts-1".
Args: voice: (optional) The voice to use. Default is "alloy".
Args: speed: (optional) The speed of the speech. Default is "1.0".
Args: response_format: (optional) The format of the response. Default is "mp3".
Args: output_file: (optional) The path to save the output file. Default is "speech".
```