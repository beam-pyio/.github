# Apache Beam Python I/O Connectors

This project aims to build [Apache Beam®](https://beam.apache.org/) I/O Connectors using the Python SDK. Visit the [project website](https://beam-pyio.github.io/) for more details.

We keep looking into adding new connectors. If you have a new idea, please add a comment to [this discussion](https://github.com/orgs/beam-pyio/discussions/4).

## AWS Services

I/O connectors for selective AWS services. They are developed by interfacing with the [boto3 package](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html).

|Connector name|Source Supported|Sink Supported|Batch Supported|Streaming Supported|
|:------|:-----:|:-----:|:-----:|:-----:|
|[firehose_pyio](https://github.com/beam-pyio/firehose_pyio)|❌|✔️|✔️|✔️|
|[sqs_pyio](https://github.com/beam-pyio/sqs_pyio)|📅|✔️|✔️|✔️|
|sns_pyio|❌|📅|📅|📅|
|[dynamodb_pyio](https://github.com/beam-pyio/dynamodb_pyio)|📅|✔️|✔️|✔️|
|eventbridge_pyio|❌|📅|📅|📅|

## SQL Sources

It connects to over 20 databases, data warehouses and query engines by integrating with the [Daft package](https://www.getdaft.io/). See the [SQL integration](https://www.getdaft.io/projects/docs/en/stable/user_guide/integrations/sql.html) page for details.

|Connector name|Source Supported|Sink Supported|Batch Supported|Streaming Supported|
|:------|:-----:|:-----:|:-----:|:-----:|
|sql_pyio|📅|📅|📅|❌|

## Open Table Format

These packages connect to popular open table formats including [Apache Iceberg](https://iceberg.apache.org/), [Apache Hudi](https://hudi.apache.org/) and [Delta Lake](https://delta.io/). They are implemented by integrating with the [Daft package](https://www.getdaft.io/). See the [integrations](https://www.getdaft.io/projects/docs/en/stable/user_guide/integrations.html) page for details.

|Connector name|Source Supported|Sink Supported|Batch Supported|Streaming Supported|
|:------|:-----:|:-----:|:-----:|:-----:|
|iceberg_pyio|📅|📅|📅|❌|
|hudi_pyio|📅|📅|📅|❌|
|deltalake_pyio|📅|📅|📅|❌|

## Code of Conduct

All *Apache Beam Python I/O Connectors* projects are governed by the project [Code of Conduct](./CONDUCT.md). Please review that and keep it in mind in all interactions.
