# WindFarm
## A wind farm engineering data pipeline simulation

![pipeline](pipeline.png)

O objetivo desse projeto é criar uma pipeline de engenharia de dados usando as ferramentas da AWS. 

Vamos simular um parque eólico. Cada um dos aerogeradores irá enviar, periodicamente, informações sobre sua temperatura, pressão hidráulica e potência. 

Nossa aplicação irá receber esses dados por meio do Kinesis, salvá-los em um bucket S3 e inferir sua estrutura tabular com Glue para permitir o uso de queries com Athena.
