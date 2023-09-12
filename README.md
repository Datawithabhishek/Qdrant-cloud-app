# App Boilerplate with GUI for Qdrant Managed Cloud Service





This repository contains an app boilerplate with a graphical user interface (GUI) that connects to a remote database hosted in Qdrant's Managed Cloud Service. The purpose of this boilerplate is to provide a starting point for building applications that interact with a Qdrant vector database.

## Features

- Graphical user interface (GUI) for easy interaction with the Qdrant vector database.
- Seamless integration with Qdrant's Managed Cloud Service.
- Simple setup process by cloning the repository and adding your credentials to the `.env` file.
- Comes with a comprehensive set of requirements specified in the `requirements.txt` file.

## Prerequisites

Before using this app boilerplate, make sure you have the following:

- Python installed on your system.
- An active Qdrant Managed Cloud Service account.
- Your Qdrant Managed Cloud Service credentials.


## Configuration

To configure the app boilerplate to work with your Qdrant Managed Cloud Service account, you need to add your credentials to the `.env` file. Follow these steps:

1. Copy the `.env.example` file and rename it to `.env`:

```shell
cp .env.example .env
```

2. Open the `.env` file in a text editor and provide your Qdrant Managed Cloud Service and OpenAI   credentials:

```plaintext
OPENAI_API_KEY=

QDRANT_HOST=
QDRANT_API_KEY=
QDRANT_COLLECTION_NAME=
```

## Usage

Once you have completed the installation and configuration steps, you can run the app boilerplate using the following command:

```shell
streamlit run app.py
```

This command will start the application.





![image](https://github.com/Datawithabhishek/langchain-project--1/assets/98747222/2d33b713-466d-45b8-9d59-67f8d7751542)






## License

The code in this repository is available under the [MIT License](LICENSE). Feel free to modify and use it for your own projects.


