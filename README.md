# AI Validation Toolkit

This repository contains Python scripts for AI-driven validation of citations using OpenAI's GPT-3.5 model. It includes a basic citation validator and an advanced, context-aware citation validator.

## Description

The AI Validation Toolkit offers two main scripts:

- `basic_citation_validator.py`: A script that demonstrates basic AI-driven citation validation.
- `advanced_contextual_validator.py`: An enhanced script that employs context-aware validation, leveraging the 'chain of thought' reasoning approach.

These scripts are designed to interact with OpenAI's API to validate citations within given texts, making them useful tools for projects requiring automated content verification.

## Getting Started

### Dependencies

- Python 3.8+
- openai
- pydantic
- python-dotenv

### Installing

- Clone this repository to your local machine.
- Ensure Python 3.8+ is installed on your system.
- Install the required packages:

pip install openai pydantic python-dotenv


### Setting Up

1. Create an `.env` file in the root directory of the project.
2. Add your OpenAI API key to the `.env` file:

OPENAI_API_KEY=your-api-key

3. Replace `your-api-key` with your actual OpenAI API key.

### Executing the scripts

- Run either script from the command line. For example:

python basic_citation_validator.py

or

python advanced_contextual_validator.py


## Help

Any issues or problems with running the scripts can be addressed by opening an issue in the repository.

## Authors

Contributors names and contact info

Aryan Mahindra 


## Version History

* 0.1
  * Initial Release

## License

This project is licensed under the [MIT License](LICENSE).
