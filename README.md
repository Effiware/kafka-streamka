# Kafka Streamka - Kafka Steams API for Python

[![PyPI](https://img.shields.io/pypi/v/kafka_streamka)](https://pypi.org/project/kafka-streamka/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/kafka_streamka)](https://pypi.org/project/kafka-streamka/)
[![PyPI - License](https://img.shields.io/pypi/l/kafka_streamka)](https://pypi.org/project/kafka-streamka/)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/kafka_streamka)](https://pypi.org/project/kafka-streamka/)
[![PyPI - Coverage](https://img.shields.io/badge/coverage-0%25-red)](https://pypi.org/project/kafka-streamka/)
[![PyPI - Wheel](https://img.shields.io/pypi/wheel/kafka_streamka)](https://pypi.org/project/kafka-streamka/)
[![PyPI - Implementation](https://img.shields.io/pypi/implementation/kafka_streamka)](https://pypi.org/project/kafka-streamka/)

**<u>Project is currently in the research phase.</u>**

Kafka Streamka is a Kafka Streams API implementation for Python, utilizing the `confluent-kafka` library. The Kafka Streams API,
originally developed for Java, is a powerful library for building real-time, scalable, and fault-tolerant stream processing
applications. It allows developers to process and analyze data stored in Kafka topics with ease.

One of the revolutionary features introduced by Kafka Streams is "exactly-once delivery" semantics, which ensures that each
record is processed exactly once, even in the presence of failures. This feature is crucial for maintaining data integrity
in distributed systems.

In Kafka, there are two types of producers: synchronous and asynchronous. A synchronous producer waits for an acknowledgment
from the Kafka broker before sending the next message, ensuring that messages are delivered in order. An asynchronous producer,
on the other hand, sends messages without waiting for acknowledgments, which can lead to higher throughput but may result
in out-of-order delivery. For critical applications where message order and delivery guarantees are important, the synchronous
approach is preferred.

Implementing a Kafka Streams API in Python presents several challenges. Python's Global Interpreter Lock (GIL) can limit
the performance of multi-threaded applications, making it difficult to achieve the same level of concurrency as in Java.
Additionally, integrating with the `confluent-kafka` library and ensuring compatibility with Kafka's features requires
careful design and testing.

This project is currently in the research phase, and we are exploring the best approaches to bring the power of Kafka Streams
to the Python ecosystem.

## License

This project is licensed under the GNU Affero General Public License v3.0. See the `LICENSE` file for more details.

## Contact

For any inquiries, please contact sales at [contact@effiware.com](mailto:contact@effiware.com).

## Links

- [Homepage](https://github.com/Effiware/kafka-streamka/wiki)
- [Repository](https://github.com/Effiware/kafka-streamka)