# AI and ML Bot with OpenAI APIs and Fine-Tuning

## Project Overview
This project's objective is to develop a machine-learning-based bot specifically designed to assist data science educators by emulating the teaching style of our data science instructor, Drew. It leverages OpenAI's APIs and fine-tuning capabilities to learn from transcripts of recorded classes, enabling it to not only provide contextual assistance and answer frequently asked questions but also to interact and respond in a manner that closely resembles Drew's unique teaching approach, thereby offering a personalized and familiar learning experience to students.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How it Works](#how-it-works)
- [Getting Started](#getting-started)
	- [Research](#research)
- [Installation](#installation)
- [Cleaning](#cleaning)
- [Acknowledgements](#acknowledgements)

## Features
- **Advanced Contextual Understanding**: Uses OpenAI's models for deep contextual comprehension of data science topics.
- **FAQs and Resource Suggestions**: Answers common questions and recommends resources, leveraging fine-tuned models.
- **Transcript-Informed Learning**: Continuously learns and adapts from class transcripts.
- **Interactive Learning Experience**: Engages students with interactive and responsive discussions.

## Technologies Used
- Python 3.x
- OpenAI API
- Natural Language Processing Libraries (NLTK, spaCy)
- Machine Learning Frameworks (TensorFlow, PyTorch)
- Speech Recognition and Text-to-Speech

## How it Works

- **Data Preprocessing**: Transcripts are cleaned, preprocessed, and formatted according to OpenAI's requirements.
- **Fine-Tuning**: The bot is fine-tuned using the processed transcripts on OpenAI's models, enhancing its understanding of data science topics.
- **Inference**: Utilizes the fine-tuned model to interpret and respond to student queries effectively.

## Getting Started

### Research
- How would we create the model
- Where would we get the data
- Exploring AI technologies

### Installation
   ```sh
   pip install --upgrade openai
   ```

### Cleaning
- transcribing data
- manual test
- formatting for OpenAI
- connection to API


## Acknowledgements

- Your Data Science Teacher
- OpenAI Community
- Contributors and Open Source Enthusiasts

## Contributors

This project exists thanks to all the people who contribute. 

## Contributing

We encourage contributions. Please follow these steps to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.

