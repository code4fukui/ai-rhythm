# ai-rhythm

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

Neural Drum Machine Density Remix

## Demo
[https://code4fukui.github.io/ai-rhythm/](https://code4fukui.github.io/ai-rhythm/)

## Features
- Experimental drum machine powered by a deep neural network
- Allows defining a seed pattern and generating a continuation using the neural network
- Provides controls for density, tempo, swing, and temperature

## Requirements
- Web browser

## Usage
To use the drum machine:
1. Define a seed pattern on the left side
2. Use the "generate" button to have the neural network generate a continuation
3. Adjust the various controls to change the output

## Data / API
This project uses the following open-source libraries and models:
- [Drums RNN](https://github.com/tensorflow/magenta/tree/master/magenta/models/drums_rnn) and [MusicVAE](https://github.com/tensorflow/magenta/tree/master/magenta/models/music_vae) models from [Google Magenta](https://magenta.tensorflow.org/)
- [Magenta.js](https://goo.gl/magenta/js), [TensorFlow.js](https://js.tensorflow.org/), and [Tone.js](https://tonejs.github.io/)

## License
MIT License — see [LICENSE](LICENSE).