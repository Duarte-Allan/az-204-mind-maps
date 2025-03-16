<!-- markmap -->
<div style="text-align: center; width:100%; padding-bottom:20px;">
  <a href="topicos/topico_8_implementar_o_gerenciamento_de_api.md" style="padding:50px;"><img src="../img/anterior.png" alt="Anterior" style="width:20px;height:20px;"></a>
  <a href="az-204_markmap.md" style="padding:50px;"><img src="../img/inicio.png" alt="Início" style="width:20px;height:20px;"></a>
  <a href="topicos/topico_10_desenvolver_solucoes_baseadas_em_mensagens.md" style="padding:50px;"><img src="../img/proximo.png" alt="Próximo" style="width:20px;height:20px;"></a>
</div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/az-204-develop-event-based-solutions.svg" alt="Soluções Baseadas em Eventos" width="50" height="50"> <br /> **Tópico 9: Desenvolver Soluções Baseadas em Eventos**</div>

## **9.1 Conceitos Fundamentais**

* **Arquiteturas orientadas a eventos:** EDA
* **Evento:** Uma ocorrência significativa que ocorre em um sistema, como uma nova venda, uma mudança de status ou um erro.
* **Produtor de eventos:** O componente que gera e publica eventos.
* **Consumidor de eventos:** O componente que se inscreve para receber eventos e processá-los.
* **Broker de eventos:** Um serviço intermediário que recebe, armazena e encaminha eventos para os consumidores.

## **9.2 Serviços do Azure para Eventos**

* **Azure Event Hubs:** Um serviço de ingestão de eventos em alta escala, ideal para grandes volumes de dados em tempo real.
* **Azure Service Bus:** Um serviço de mensagens totalmente gerenciado, que pode ser usado para implementar cenários de pub/sub e filas.
* **Azure Functions:** Uma plataforma serverless para executar código em resposta a eventos, como mensagens do Event Hubs ou do Service Bus.
* **Azure Stream Analytics:** Um serviço de processamento de streaming que permite analisar dados em tempo real de várias fontes, incluindo o Event Hubs.

## **9.3 Cenários de Uso**

* **IoT:** Processamento de dados em tempo real de dispositivos IoT.
* **Análise de dados em tempo real:** Analisar dados de streaming para tomar decisões em tempo real.
* **Integração de sistemas:** Conectar diferentes sistemas e aplicativos de forma assíncrona.
* **Processamento de logs:** Analisar logs de aplicativos para identificar problemas e tendências.

## **9.4 Implementação**

1. **Identificar os eventos:** Definir os eventos que são relevantes para o seu sistema.
2. **Escolher o serviço de eventos:** Selecionar o serviço Azure mais adequado para o seu cenário (Event Hubs, Service Bus, etc.).
3. **Criar produtores e consumidores:** Implementar o código para gerar e consumir eventos.
4. **Configurar o broker de eventos:** Configurar o serviço de eventos para rotear os eventos para os consumidores corretos.
5. **Processar os eventos:** Implementar a lógica de negócio para processar os eventos.

## **9.5 Considerações**

* **Escala:** Escolher o serviço de eventos que pode escalar para atender à sua carga de trabalho.
* **Durabilidade:** Decidir se os eventos precisam ser armazenados de forma duradoura.
* **Ordem de entrega:** Determinar se a ordem dos eventos é importante.
* **Tolerância a falhas:** Implementar mecanismos de retransmissão e dead-letter para garantir a entrega dos eventos.
