## Docs

https://grpc.io/docs/languages/python/


## Commands

protoc build command

    python -m grpc_tools.protoc -I./protos --python_out=./src --pyi_out=./src --grpc_python_out=./src ./protos/route_guide.proto

run server

    python route_guide_server

run client

    python route_guide_client