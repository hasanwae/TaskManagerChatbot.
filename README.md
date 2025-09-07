# TaskBot

## Description
TaskBot is a Python-based chatbot for managing daily tasks, built using spaCy for natural language processing (NLP) and storing data in a CSV file on Google Drive. It allows users to add and view tasks with date and priority support (e.g., "add task meeting tomorrow urgent"). Developed on Google Colab, this project showcases AI and file handling skills. Updated: September 2025.

## Features
- Add tasks with natural language (e.g., "add task finish project tomorrow").
- View all tasks with their due dates and priorities.
- Stores data in `tasks.csv` on Google Drive for persistence.
- Supports priority levels (Medium by default, High with "urgent").

## Prerequisites
- Python 3.x
- Google Colab environment
- Internet connection for mounting Google Drive

## Installation
1. Open [Google Colab](https://colab.research.google.com).
2. Create a new notebook and copy the code from this repository.
3. Run the cell to install dependencies (`spacy` and `en_core_web_sm`).
4. Mount Google Drive by running the provided code and authenticating.

## Usage
- Start the chatbot by running the script.
- Use commands:
  - `add task [task description]`: Add a new task.
  - `show tasks`: View all tasks.
  - `exit`: End the conversation.
- Example: `add task meeting tomorrow urgent`

## File Structure
- `tasks.csv`: Stores all tasks in Google Drive (e.g., `/content/drive/My Drive/tasks.csv`).

## Contributing
Feel free to fork this repository, submit issues, or pull requests to improve the project!

## License
[Add a license here, e.g., MIT] - Optional, choose based on your preference.

## Contact
For questions, contact [Your Name or Email] or open an issue on this repository.
