<!-- markmap -->
<div style="text-align: center; width:100%; padding-bottom:20px;">
  <a href="topico_10_desenvolver_solucoes_baseadas_em_mensagens.md" style="padding:50px;"><img src="../img/anterior.png" alt="Anterior" style="width:20px;height:20px;"></a>
  <a href="../az-204_markmap.md" style="padding:50px;"><img src="../img/inicio.png" alt="Início" style="width:20px;height:20px;"></a>
  <a href="topico_12_implementar_o_cache_para_solucoes.md" style="padding:50px;"><img src="../img/proximo.png" alt="Próximo" style="width:20px;height:20px;"></a>
</div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/monitoring-instrument-solutions.svg" alt="Application Insights" width="50" height="50"> <br /> **Tópico 11: Solucionar Problemas de Soluções usando o Application Insights**</div>

## **11.1 O que é o Application Insights?**

* O Application Insights é um serviço de monitoramento e análise da aplicação que fornece insights detalhados sobre o desempenho, a utilização e a confiabilidade de suas aplicações.
* Ele coleta dados de telemetria de sua aplicação, como solicitações, dependências, exceções e logs personalizados.
* Com ele, você pode identificar gargalos de desempenho, rastrear falhas e entender o comportamento dos usuários.

## **11.2 Funcionalidades Principais**

* **Monitoramento em tempo real:** Visualize o desempenho da sua aplicação em tempo real, incluindo métricas como tempo de resposta, taxa de erro e utilização de CPU.
* **Detecção de anomalias:** Identifique automaticamente anomalias no desempenho da sua aplicação.
* **Análise de falhas:** Investigue as causas de falhas e erros em sua aplicação, utilizando logs detalhados e telemetria.
* **Rastreamento de dependências:** Monitore o desempenho de suas dependências externas, como bancos de dados e serviços web.
* **Análise de uso:** Entenda como os usuários estão interagindo com sua aplicação.

## **11.3 Como o Application Insights Funciona?**

* Inserindo um SDK em sua aplicação. 
* Esse SDK coleta dados de telemetria e os envia para o Azure, onde são armazenados e analisados. 
* Você pode então visualizar esses dados através do portal do Azure ou utilizando a API do Application Insights.

## **11.4 Solucionando Problemas**

* **Diagnóstico de falhas:** Use os logs detalhados para identificar a causa raiz de falhas e exceções.
* **Análise de desempenho:** Identifique gargalos de desempenho, como consultas SQL lentas ou chamadas de API demoradas.
* **Rastreamento de dependências:** Verifique se as dependências externas estão respondendo de forma lenta ou falhando.
* **Análise de uso:** Entenda quais partes da sua aplicação estão sendo mais utilizadas e quais estão causando problemas.

## **11.5 Ferramentas e Recursos**

* **Painéis:** Crie painéis personalizados para visualizar as métricas mais importantes para sua aplicação.
* **Consultas Kusto:** Execute consultas Kusto para analisar os dados de telemetria com mais profundidade.
* **Alertas:** Configure alertas para notificá-lo quando ocorrem problemas na sua aplicação.
* **Integração com outras ferramentas:** Integre o Application Insights com outras ferramentas do Azure, como o Azure Monitor e o Azure Log Analytics.

## **11.6 Exemplo de Uso**

* **Identificar a operação mais lenta:** Analisar os tempos de resposta das diferentes operações para identificar a que está causando a lentidão.
* **Investigar a causa da lentidão:** Analisar os logs detalhados da operação lenta para identificar a causa raiz, como uma consulta SQL lenta ou uma chamada de API demorada.
* **Corrigir o problema:** Implementar as correções necessárias para melhorar o desempenho da aplicação.

## **11.7 Considerações**

* **Configuração:** Configure o Application Insights corretamente para coletar os dados de telemetria relevantes para sua aplicação.
* **Privacidade:** Seja cuidadoso ao coletar dados de usuários e garantir a conformidade com as leis de privacidade.
* **Custo:** O custo do Application Insights varia de acordo com o volume de dados coletados.
