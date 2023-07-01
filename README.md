# Fine-Tuning Falcon-7B With QLoRA for Indian Law (WIP)

This repository contains code and resources for fine-tuning the Falcon-7B model on Indian legal questions and answers dataset leveraging the PEFT library from the Hugging Face ecosystem and QLoRA for more memory-efficient fine-tuning.

## Overview

Falcon-7B, a causal decoder-only model trained on a causal language modeling task, serves as the core of this project. It incorporates design elements from the GPT-3 model, augmented with several performance and memory efficiency enhancements.

The main aim of this project is to fine-tune this large language model to understand and generate texts related to Indian law. A specially curated dataset of 150 Q&As on diverse aspects of Indian law, such as constitutional law, civil rights, criminal justice, property law, etc., is used for this purpose.

We employ PEFT, a library developed by Hugging Face, which enables highly efficient fine-tuning of large language models like Falcon-7B.

To minimize the memory footprint of transformer models during fine-tuning, we utilize QLoRA - an innovative technique for memory-efficient model training.

Thus, the project unifies these advanced technologies to efficiently and effectively fine-tune the Falcon-7B model on a specialized dataset.

In this project, we combine these technologies to fine-tune the Falcon-7B model on a specialized dataset in a memory-friendly and efficient way.

![Training](https://github.com/NisaarAgharia/Fine-Tuning-Falcon-7B-LLM-Model/assets/22457544/60f1a52d-6e30-42b2-a0dd-d264ab97b97d)

![Screenshot 2023-06-16 004036](https://github.com/NisaarAgharia/Fine-Tuning-Falcon-7B-LLM-Model/assets/22457544/ff584f7f-9961-48d4-8cb5-8f674563e163)


## Results

You can visualize the training progress using TensorBoard. After starting the training process, launch TensorBoard and navigate to the localhost link it provides:

```bash
tensorboard --logdir=./runs
```

You will be able to see various metrics such as training loss, validation loss, etc.

## Contributing

Contributions are welcome! Please read the contributing guide to learn how you can contribute to this project.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

We would like to thank OpenAI for releasing the Falcon-7B model, Hugging Face for providing the infrastructure and libraries necessary for fine-tuning large transformer models, and the Hugging Face Datasets community for providing the legal Q&A dataset.

## Contact

For questions or feedback about this project, please open an issue on this repository.
