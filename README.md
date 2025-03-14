# Meeting_Minutes_Generator
a meeting minutes generator from Audio file

## Overview

This project uses **Hugging Face's audio models** to transcribe city council meeting recordings and generate structured **meeting minutes in Markdown format**. The goal is to automate the documentation process, making meetings more accessible and easier to review.

## Features

- **Automatic Speech-to-Text Transcription**: Converts audio from city council meetings into text using Hugging Face models.
- **Structured Markdown Output**: Generates well-formatted meeting minutes in Markdown.
- **Customizable Formatting**: Users can modify templates to fit their needs.
- **Easy Integration**: Works within a Jupyter Notebook for flexibility.

## Installation

Ensure you have Python installed along with the required dependencies. Install the necessary libraries:

```bash
pip install -q requests torch bitsandbytes transformers sentencepiece accelerate openai httpx==0.27.2
```

## Usage

1. **Load the Jupyter Notebook**: Open `meeting_minutes_generator.ipynb`.
2. **Upload an Audio File**: Place your `.mp3` or `.wav` file in the designated location.
3. **Run the Notebook**: Execute the cells to transcribe the meeting and generate Markdown-formatted minutes.
4. **Export the Minutes**: Copy or save the output Markdown file.

## Example Output

```markdown
# City Council Meeting - March 10, 2025

## Attendees
- Mayor John Doe
- Council Member Jane Smith
- Public Representative Alice Brown

## Agenda
1. Budget discussion
2. Public safety updates
3. New city projects

## Key Decisions
- Approved funding for road repairs.
- Launched new community outreach program.

## Action Items
- John to draft the new policy proposal.
- Alice to coordinate with the safety department.
```

## Customization

- Modify the Markdown template in the notebook to fit your meeting format.
- Adjust the Hugging Face model used for better transcription accuracy.

## Author

**Pouria Ebrahimnezhad**\
Created on **14-03-2025**

## Contributing

Feel free to open issues or submit pull requests if you’d like to improve the project!

