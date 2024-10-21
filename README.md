# Análisis de Datos con Spark y Kafka

## Descripción

Este repositorio contiene un proyecto de análisis de datos en el que se realiza un procesamiento de datos utilizando Apache Spark y Apache Kafka. El trabajo se divide en dos partes:

1. **Procesamiento de Datos con Spark**: En esta sección, se realizan diversas preguntas sobre el conjunto de datos utilizando operaciones de Spark SQL y DataFrame. Se analizan estadísticas
2. **Procesamiento en Tiempo Real con Spark y Kafka**: Aquí se implementa un sistema de procesamiento de flujos en tiempo real utilizando Kafka para la ingesta de datos y Spark Streaming para el análisis. Se generan estadísticas de sensores en tiempo real, como temperatura y humedad.

## Estructura del Proyecto

## Requisitos

Para ejecutar este proyecto, asegúrate de tener instalado lo siguiente:

- Python 3.x
- Apache Spark
- Apache Kafka

## Instalación

1. Clona este repositorio:

2. Inicia Servidor ZeoKepper
sudo /opt/Kafka/bin/zookeeper-server-start.sh /opt/Kafka/config/zookeeper.properties &

Servidor Kafka
sudo /opt/Kafka/bin/kafka-server-start.sh /opt/Kafka/config/server.properties &

