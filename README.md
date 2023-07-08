# Podcast Summarizer

Podcast Summarizer is a powerful tool that enables users to download summaries of podcast episodes. It utilizes the AssemblyAI and Listen Notes APIs to transcribe podcast episodes and extract meaningful summaries.

## Features

- Transcribe podcast episodes and save the text as a downloadable file.
- Automatically generate chapter summaries for podcast episodes.
- Generates title, image, name of episode, different chapters with summaries and timestamps
- Streamlit-based user interface for easy interaction.

## Prerequisites

Before running the application, please ensure that you have the following requirements installed:

- Python 3.7 or above
- Required Python packages (install via `pip install -r requirements.txt`)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/AnmolGulati6/Podcast-Summarizer.git
```

2. Navigate to the project directory:

```bash
cd podcast-summarizer
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

To launch the Podcast Summarizer Plus application, run the following command:

```bash
streamlit run main.py
```

The application will start, and you can access it through your web browser at `http://localhost:8501`.

1. Enter the episode ID from https://www.listennotes.com/ in the sidebar input field.
2. Click the "Download Episode summary" button to initiate the summarization process.
3. The episode summary and chapter summaries (if available) will be displayed on the page.
4. You can download the episode summary as a text file.

## Configuration

The application requires API keys for both AssemblyAI and Listen Notes. To configure your API keys, follow these steps:

1. Open the `api_secrets.py` file.
2. Replace `API_KEY_ASSEMBLYAI` with your AssemblyAI API key.
3. Replace `API_KEY_LISTENNOTES` with your Listen Notes API key.


