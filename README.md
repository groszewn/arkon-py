# Arkon Message-Driven Execution Framework

The Arkon project aims to simplify message-driven execution by abstracting user code from how messages are received.
By providing configuration-driven options for different execution patterns (i.e. producer/consumer, request/response, request/stream, etc.), processing logic can be decoupled from the actual communication patterns.
This allows for easier portability of user code to be applied in different situations, without the overhead of rewriting orchestration logic.

## Installation

The `arkon` library can be installed directly from [PyPI](https://pypi.org/project/arkon/).

```bash
pip install arkon
python -c "import arkon; print(arkon.hello_arkon())"
```

## Support Communication Patterns

* gRPC
* REST
* Kafka
* NATS
* WebSockets
