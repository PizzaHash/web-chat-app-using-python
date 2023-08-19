## Installation

Make sure you have installed Node.js, npm, Python3, and pip.
After installation please follow the instructions below to download the repo.

- Within the terminal window, create a folder in your local drive.
- Navigate to the folder created.
- Run the following command:

```

- Navigate into the new sub-folder created called **WebSocket-App**.
- Run the following commands to create an environment and install the dependencies:

```bash
  python3 -m venv env
  source env/bin/activate
  pip install -r requirements.txt
```

- Navigate into the /**front-end** folder and run the following command:

```bash
  npm i react-scripts
```

## Run Locally

Open two terminal windows, one to be used by the Flask server and the other
to be used by the React client.
Make sure the server is initialized before the client to avoid any issues.

Terminal **window 1** - start the server:

```bash
  cd webSocket-App
  source env/bin/activate
  python3 server.py
```

Terminal **window 2** - start the client:

```bash
  cd webSocket-App/front-end
  npm start
```
