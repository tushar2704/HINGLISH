# English to Hindi Neural Machine Translation

![Translation Example](translation_example.png)

## Overview

This project focuses on building a Neural Machine Translation (NMT) system to translate English sentences to Hindi. NMT has revolutionized the field of language translation by leveraging deep learning techniques to produce more accurate and natural-sounding translations.

## Features

- **Encoder-Decoder Architecture**: The NMT system employs an encoder-decoder architecture, where the encoder encodes the input English sentence into a fixed-size context vector, and the decoder generates the corresponding Hindi translation from the context vector.
  
- **Attention Mechanism**: To handle longer sentences and capture relevant information effectively, an attention mechanism is integrated. This allows the model to focus on different parts of the input sentence while generating the output.

- **Data Preprocessing**: The project includes data preprocessing steps to clean and normalize input sentences, ensuring better alignment and accuracy in translation.

- **Training and Evaluation**: The model is trained on a parallel corpus of English-Hindi sentence pairs. During training, the model learns to minimize the translation loss. The evaluation process demonstrates the model's translation quality with selected input sentences.

- **Visualization of Attention**: The project offers a visualization of attention weights, showing how the model attends to different parts of the input during translation.

## Usage

1. **Data Preparation**: Prepare your parallel corpus of English-Hindi sentence pairs. Ensure that your data is properly formatted and cleaned.

2. **Model Configuration**: Set up the encoder and attention-based decoder architecture in the code. Define the hyperparameters, such as hidden size, learning rate, and dropout rate.

3. **Training**: Train the model using the provided training functions. Adjust the number of training iterations, print intervals, and other parameters as needed.

4. **Evaluation and Visualization**: Evaluate the model's translation quality using the `evaluateAndShowAttention` function. Provide your English input sentences and observe both the translated output and attention visualization.

## Dependencies

- Python 3.x
- PyTorch
- Matplotlib

## Contributing

Contributions to this project are welcome! Whether it's improving the model's performance, enhancing the visualization, or extending the features, your contributions can make a significant impact.

## License

This project is licensed under the [MIT License](LICENSE).

