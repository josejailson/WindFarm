# WindFarm
## A wind farm engineering data pipeline simulation

![pipeline](pipeline.png)

The objective of this project is to create a data engineering pipeline using AWS tools.

We will simulate a wind farm, where each of the wind turbines will periodically send information about its temperature, hydraulic pressure, and power.

Our application will receive this data through Kinesis, save it in an S3 bucket, and use Glue to infer its tabular structure, enabling the use of queries with Athena.
