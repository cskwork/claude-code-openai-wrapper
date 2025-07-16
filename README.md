# Claude Code OpenAI Wrapper

This project is an OpenAI API-compatible wrapper for Claude Code.

## Installation

1.  Install the project dependencies using Poetry:
    ```bash
    poetry install
    ```

## Running the application

1.  Run the application using the following command:
    ```bash
    poetry run claude-wrapper
    ```

2. Test
    ```bash
    curl -X POST http://localhost:8000/v1/chat/completions \
      -H "Content-Type: application/json" \
      -d '{
            "model": "claude-3-5-haiku-20241022",
            "messages": [
              {"role": "user", "content": "Hello, Wrapper! 🎉"}
            ]
          }'
    ```