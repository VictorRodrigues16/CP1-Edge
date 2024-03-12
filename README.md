# Projeto com os Sensores DHT11, Ultrassônico e LDR 🎛️🌡️

## Descrição do Projeto

Este protótipo apresenta o primeiro checkpoint do projeto desenvolvido na disciplina de Edge Computing. Optamos por utilizar três componentes principais neste projeto: DHT11, Ultrassônico (Módulo Sensor de Distância) e LDR (Light Dependent Resistor).

## Funcionalidades

1. *DHT11:*
   - Utilizamos para monitorar a umidade do ambiente.

2. *Ultrassônico:*
   - Utilizamos para medir a distância em centimentros entre o dispositivel e a qualquer objeto.

3. *LDR:*
   - Utilizamos para monitorar o nível luminosidade do ambiente.

## Hardware Utilizado

- Arduino Uno
- Sensor de Umidade
- Sensor de Distância
- Sensor de Luminosidade

## Instruções de Montagem

1. *Conexão dos Sensores:*
   - Conectar o sensor de Umidade à porta digital do Arduino.
   - Conectar o sensor de distância à porta digital correspondente.
   - Conectar o sensor de Luminosidade à protoboard.

2. *Configuração do Código:*
   - Certificar-se de ajustar as configurações de calibração dos sensores de umidade e lumninosidade conforme requisitos solicitados.
   - Configurar o tempo de intervalo de 4000ms para acionamento de todos os sensores.

3. *Upload do Código:*
   - Carregar o código fornecido no Arduino IDE para o Arduino Uno.
   - Configurar o Node-Red e carregar o codigo fornecido com as informações solicitadas.
   - Verificar se todas as bibliotecas necessárias estão instaladas no Arduino IDE e no Node-Red.
     * (DHT.h, ArduinoJSON, Library)

4. *Testes:*
   - Realizar testes para garantir que o monitoramento de umidade, luminosidade e distância estão funcionando corretamente.
   - Analisar o DashBoard e ver se todos os parametros estão sendo aprensentados com clareza.

## Contribuições e Melhorias

Este projeto está em constante desenvolvimento, e contribuições são bem-vindas. Se você identificar melhorias ou tiver sugestões para novas funcionalidades, sinta-se à vontade para contribuir.

’’’
