# data-salaries-dataset

## Descripción
Este script genera un dataset sintético y realista de perfiles profesionales del ámbito de datos (Data Scientist, Data Engineer, Analyst, ML Engineer, etc.) con información coherente entre experiencia, edad y salario, además de campos operativos como:

created_at
updated_at
consent_accepted
consent_ts

El objetivo es proporcionar un dataset totalmente seguro, anonimizado y plausible para pruebas dentro de un proyecto en AWS que incluye:

Carga en S3
Catalogación con AWS Glue
Consulta en Amazon Athena
(Opcional) Inserción en bases transaccionales como Aurora MySQL mediante SQL generado

Este dataset no utiliza ningún dato personal real.
