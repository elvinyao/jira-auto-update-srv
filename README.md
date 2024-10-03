# JIRA Auto Update Service

This service automatically updates JIRA issues based on Confluence content and Excel data.

## Features
- Reads data from Confluence pages
- Updates JIRA issues automatically
- Processes Excel files for data input
- Sends notifications via Mattermost

## Setup
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Configure the service in `config/config.yaml`
3. Run the service:
   ```
   python -m app.main
   ```

## Project Structure
- `app/`: Main application code
- `tests/`: Test files
- `logs/`: Log files
- `config/`: Configuration files


