# WhatsApp FastAPI Webhook

## Description

A simple webhook for WhatsApp API using FastAPI.

## Dependencies

- [FastAPI](https://github.com/tiangolo/fastapi)
- [uvicorn](https://github.com/encode/uvicorn)

## How to Use

1. Export your own token as an env var
1. Host the app on any server or serve the app using [ngrok](https://ngrok.com/) or any other tool
1. Verify your token on "Meta Developers" page

## How to Run Locally

> You have to install [ngrok](https://ngrok.com/) or any other similar tool.

1. Install the dependencies

    ```shell
    pip install -r requirements.txt
    ```
1. Run the server

    ```shell
    python main.py
    ```
1. Run ngrok

    > If you changed the port in `main.py` file, you have to change it here as well.

    ```shell
    ngrok http 8000
    ```

1. Use [ngrok](https://ngrok.com/) link as your Webhook link
