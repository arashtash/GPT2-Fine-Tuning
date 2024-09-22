# GPT2-Fine-Tuning
Applying Lightweight Fine-Tuning to a Foundation GPT-2 Model

# Description

This project tests the accuracy and fine-tunes a GPT-2 model for sequence classification using Hugging Face's PEFT (Parameter-Efficient Fine-Tuning) library. It includes training and evaluating the model on the climatebert/climate_sentiment dataset to classify text into categories of "risk," "neutral," or "opportunity." Initially, I conducted an evaluation of the pre-trained GPT-2 model, achieving an accuracy of 36.5%. After applying PEFT using LoRA (Low-Rank Adaptation), I fine-tuned the model, significantly improving its accuracy to 52% over only four epochs.

It implements and trains both traditional and PEFT models using Python libraries such as NumPy, PyTorch, PEFT and Pandas. This project shows the effectiveness of lightweight fine-tuning for improving model performance while reducing computational complexity.


# Author
Arash Tashakori


[Website and Contact information](https://arashtash.github.io/)


# License

Copyright (c) 2024 arashtash - Arash Tashakori

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
