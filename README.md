# Real-time-Chat-Application-Using-gRPC
## Prerequisites and Package Installation

### Python Version
- Python 3.8 or higher recommended

### Required Packages
Install the following packages using pip:


```bash
pip install grpcio
pip install grpcio-tools
pip install protobuf
```
Detailed Package Descriptions

grpcio: Core gRPC library for Python, enabling high-performance RPC framework
grpcio-tools: Provides protobuf compiler and gRPC service generator
protobuf: Google's data serialization library used for efficient data exchange

Optional but Recommended
bashCopypip install datetime  # For timestamp functionality
Installation Steps

Clone the repository
Create a virtual environment (recommended)
Install required packages
Generate gRPC code from .proto file
Run the server and client scripts

Generating gRPC Code
```bash
bashCopypython -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. chat.proto
```
