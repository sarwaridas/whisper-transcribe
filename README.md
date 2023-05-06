To install Whisper CLI, run:

```sh
pip install whisper-cli
```

## Setup
To get started with Whisper CLI, you'll need to set your OpenAI API key. You can do this using the following command:

```sh
whisper key set <openai_api_key>
```

This will set the API key for the default environment. If you want to use a different API key, you can set up an alternative environment by running:

```sh
whisper key set <openai_api_key> --env <env_name>
```

To activate an alternative environment, run:

```sh
whisper env activate <env_name>
```

## Usage

Whisper CLI supports two main functionalities: translation and transcription.

### Translation
To translate an audio file, simply run:

```sh
whisper translate <file_name>
```

### Transcription
To transcribe an audio file, run:

```sh
whisper transcribe <file_name>
```

