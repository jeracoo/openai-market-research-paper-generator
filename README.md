# Market Research Report Generator

This Python script facilitates the creation of structured market research reports for products by using OpenAI's GPT-3.5 API. The script focuses on generating a report for glasses designed for neurodiverse children that block peripheral vision, aiming to decrease the chance of sensory overload.

## Features

- Interactive GUI prompt to capture user input for report generation.
- Integration with OpenAI's GPT-3.5 model to create detailed report sections.
- Automated generation of a Word document (.docx) with the report's content.
- Use of environment variables for enhanced security of API keys.

## Prerequisites

To run this script, you will need:
- Python 3.6 or higher.
- `tkinter` installed with Python (usually installed by default).
- `python-docx` library to create and update Word documents.
- `openai` library to interact with the OpenAI API.

## Installation

1. Clone the repository to your local machine.
2. Install the required Python libraries using the following command:

```bash
pip install python-docx openai
