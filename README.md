# Application of deep learning methods for noise reduction in audio data in automatic speech recognition systems

This repository contains the code and models developed as part of my thesis on applying neural network methods for noise suppression in audio data, with a focus on improving automatic speech recognition (ASR). This work was completed as part of my degree at the Faculty of Computational Mathematics and Cybernetics, Lomonosov Moscow State University.

## Project Overview

The primary goal of this project was to explore and improve neural network-based approaches for noise suppression in audio data, particularly for enhancing the performance of ASR systems. The project involved the implementation and evaluation of several advanced models, including both existing techniques and proposed improvements.

### Implemented Methods

- **Listening to Sound of Silence for Speech Denoising (LSSSD)**: A neural network approach for noise suppression that leverages silent intervals in audio to improve speech quality.
- **Dense Convolutional Recurrent Network (DCRN)**: A deep learning model combining convolutional and recurrent layers to effectively suppress noise in audio signals.

### Modifications and Improvements
- **LSSSD Frozen**: A modification of LSSSD where each component is trained independently to improve overall performance.
- **LSSSD + DCRN**: A combined model that integrates DCRN into the LSSSD architecture for enhanced noise suppression.

### Data Used

- **VoiceBank**: English-language dataset with clean and noisy speech recordings.
- **DEMAND**: Dataset containing various environmental noise recordings.
- **LibriSpeech**: A large corpus of read English speech.
- **OpenSTT**: A comprehensive Russian-language dataset with both clean speech and transcriptions.

### Key Improvements

- **Loss Function Modifications**: Improved the LSSSD model by decoupling the loss calculations for different components, resulting in more stable and effective training.
- **Hybrid Model Architecture**: Combined LSSSD with DCRN to leverage the strengths of both models, particularly for challenging noise environments.

### Results

- The modified models demonstrated superior performance in terms of noise suppression, as measured by PESQ, STOI, and other standard metrics.
- The enhanced noise suppression led to significant improvements in ASR accuracy, with WER reductions observed across multiple datasets.

## Thesis Text and Results

The full thesis text, including detailed descriptions of the methods, experiments, and results, can be found in the file `text.pdf`. The document is written in Russian.

## Acknowledgements

This project was completed under the supervision of Dr. V.V. Glazkova at the Faculty of Computational Mathematics and Cybernetics, Lomonosov Moscow State University. I would like to thank my advisor and the research group for their support and guidance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

