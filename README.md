# Converse-Messaging-App

Converse is an instant messaging chat application, developed using Python, HTML, JavaScript and Shell. The project mostly leverages socket programming and multi-thread processing techniques.

## Setup

Ensure you have python 3.9.0+ installed.

```bash
pip install -r requirements.txt
```

## Running the Server

```bash
cd website
python main.py
```

## Clearing Message History

To clear the message history simply delete the `messages.db` file.

## Old Message Server

I created a custom message server using Python sockets, before implementing socketio for this project. 'old_msg_server/' has the necessary code.
