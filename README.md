# magicChest

This is a repo containing the code for a magic chest prop to be used at a local Renfaire.  The goal is to have a magic chest that players have to trick into opening.  On the software side this means having local models to perform TTS, STT, and to be an LLM to judge their answers.  

## Installation Instructions

To run everything, you will need to follow the installation instructions for three other projects.  

- Speech-To-Text is covered by [pywhispercpp](https://github.com/absadiki/pywhispercpp), which also needs ffmpeg installed
- Text-To-Speech is covered by [Piper-TTS](https://github.com/OHF-Voice/piper1-gpl), make sure to download the voice you want to use
- [Ollama](https://github.com/ollama/ollama) is used to host the LLM to make switching models easier.  

## TODO

- Need to add servo controls for raising and lowering the chest
- Need to add function for the LLM to call servos
- Need to add additional trigger controls


