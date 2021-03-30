FROM ubuntu

ARG secret="this is a scret"

RUN echo "Secret: $secret"

ENV message="Hello world"

ENTRYPOINT echo hello ${message} This is a scret message for you: ${secret}

