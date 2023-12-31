# English to Hindi Neural Machine Translation

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)
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

**Refrences**
-  [Learning Phrase Representations using RNN Encoder-Decoder for
   Statistical Machine Translation](https://arxiv.org/abs/1406.1078)_
-  [Sequence to Sequence Learning with Neural
   Networks](https://arxiv.org/abs/1409.3215)_
-  [Neural Machine Translation by Jointly Learning to Align and
   Translate](https://arxiv.org/abs/1409.0473)_
-  [A Neural Conversational Model](https://arxiv.org/abs/1506.05869)_


## Author
- <ins><b>©2023 Tushar Aggarwal. All rights reserved</b></ins>
- <b>[LinkedIn](https://www.linkedin.com/in/tusharaggarwalinseec/)</b>
- <b>[Medium](https://medium.com/@tushar_aggarwal)</b> 
- <b>[Tushar-Aggarwal.com](https://www.tushar-aggarwal.com/)</b>
- <b>[New Kaggle](https://www.kaggle.com/tagg27)</b> 

## Contact me!
If you have any questions, suggestions, or just want to say hello, you can reach out to us at [Tushar Aggarwal](mailto:info@tushar-aggarwal.com). We would love to hear from you!

