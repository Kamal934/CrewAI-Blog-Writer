# CrewAI-Blog-Writer

## Overview
The CrewAI-Blog-Writer is a tool designed to generate blog posts using AI based on YouTube channel content. This tool utilizes the `YoutubeChannelSearchTool` to search and extract video information from specified YouTube channels.

## Features
- Extracts video information from YouTube channels.
- Generates blog content based on YouTube video data.
- Easy to set up and use with minimal configuration.

## Prerequisites
- Python 3.8 or higher
- An OpenAI API key

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/Kamal934/CrewAI-Blog-Writer.git
    cd CrewAI-Blog-Writer
    ```

2. Set up a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Configuration
1. Create an `.env` file in the root directory of the project and add your OpenAI API key :
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

2. Ensure you have update the `tools.py` configured with the desired YouTube channel handle in your script:
    ```python
    yt_tool = YoutubeChannelSearchTool(youtube_channel_handle='@campusx-official')
    ```

## Usage
To generate a blog post, run the main script:

```sh
python main.py
```

## Directory Structure


    CrewAI-Blog-Writer/
        ├── .env
        ├── README.md
        ├── requirements.txt
        ├── crew.py
        ├── agents.py
        ├── tools.py
        └── tasks.py
## Contact

If you have any questions, feel free to open an issue or contact the with me.
