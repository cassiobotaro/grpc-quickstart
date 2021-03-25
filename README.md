# grpc-quickstart
🐕 This guide gets you started with gRPC in Python with a simple working example.

# Install

Use [poetry](https://python-poetry.org/) to create environment and install dependencies.

`poetry install`

# Usage

Compile proto: `poetry run python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. helloworld.proto`

Run server: `poetry run python greeter_server.py`

Run client: `poetry run python greeter_client.py`

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)
