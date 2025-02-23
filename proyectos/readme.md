
# Adecuador de señal para sensor (MQX)

## Descripción
Este proyecto consiste en el diseño e implementación de un circuito adecuador de señal para un sensor de gas MQ circular SMD. El circuito permite acondicionar la señal del sensor para que pueda ser leída correctamente por un microcontrolador o sistema de adquisición de datos.

## Tecnologías utilizadas
- amoplificador operacional: LM 1117
- Sensor: MCX - MQX
- resistencias:
  * R1: 4.7K, R2: 4.7k.
- capacitores:
  * C1: 10uf, 22uf. (no polarizado)
- puertos HDR.

- Herramientas: EasyEDA std(para el diseño del circuito).

## Funcionalidades
- Medición de gases en voltaje segun la resolucion del sensor.
- Envío de datos a un modulo codificador o tarjeta de desarrollo.

## Resultados
El sistema logró construir a totalidad el adecuador de señal


## Aprendizajes
- Cómo utilizar sensores analógicos sin modulos decodificadores.
- Comunicación serial.

## Licencia
Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).
