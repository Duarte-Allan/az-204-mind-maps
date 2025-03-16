<!-- markmap -->
<style>
.button {
  padding: 5px 10px;
  font-size: 12px;
  font-weight: bold;
  text-align: center;
  text-decoration: none;
  background-color: #0078d4;
  color: white;
  border-radius: 3px;
  transition: background-color 0.3s;
}

.button:hover {
  background-color: #005a9e;
}

.button-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
}

.divider {
  border-top: 1px solid rgb(65, 66, 67); /* Tom de cinza das linhas do Markdown */
  margin: 20px 0;
}
</style>

<div class="button-container">
  <a href="topico_1_implementar_aplicativos_web_do_servico_de_aplicativo_do_azure.md" class="button">Anterior</a>
  <a href="az-204_markmap.md" class="button">Início</a>
  <a href="topico_3_desenvolver_solucoes_que_usam_o_armazenamento_de_blobs.md" class="button">Próximo</a>
</div>

<div class="divider"></div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/az-204-implement-azure-functions.svg" alt="Azure Functions" width="50" height="50"> <br /> **Tópico 2: Implementar o Azure Functions**</div>

## **2.1 Conceitos Básicos**

* **Triggers:** Eventos que iniciam a execução de uma função (HTTP, Timer, Queue, Blob Storage, Cosmos DB, etc.).
* **Bindings:** Conectam a função a outros serviços, permitindo a entrada e saída de dados.
* **Escalabilidade:** Automática ou manual, ajustando os recursos de acordo com a demanda.
* **Plano de Serviço:** Consumo, Plano ou Premium, cada um com suas características e custos.

## **2.2 Criando Funções**

* **Portal do Azure:** Interface visual para criar e configurar funções.
* **Azure CLI:** Utilizar comandos para criar e gerenciar funções.
* **Azure PowerShell:** Automação de tarefas através de scripts.
* **Visual Studio Code:** Desenvolvimento local com suporte a Azure Functions.

## **2.3 Linguagens Suportadas**

* **C#:** Linguagem padrão para desenvolvimento de Azure Functions.
* **JavaScript:** Popular para aplicações web e integrações.
* **Python:** Ideal para análise de dados e machine learning.
* **Java:** Para aplicações corporativas e integrações com sistemas legados.

## **2.4 Escalabilidade e Desempenho**

* **Escalabilidade Automática:** Ajusta o número de instâncias de função com base na carga de trabalho.
* **Escalabilidade Manual:** Configurar manualmente o número de instâncias.
* **Otimização de Desempenho:** Utilizar cache, minimizar alocações de memória e otimizar o código.

## **2.5 Integração com Outros Serviços**

* **Event Hubs:** Processar grandes volumes de eventos em tempo real.
* **Cosmos DB:** Armazenar e consultar dados NoSQL.
* **Service Bus:** Enviar e receber mensagens assíncronas.
* **Logic Apps:** Orquestrar workflows complexos.

## **2.6 Cenários de Uso**

* **Processamento de dados:** Analisar dados de IoT, logs e arquivos.
* **Integrações:** Conectar sistemas diferentes (SaaS, on-premises).
* **Automação:** Agendar tarefas, responder a eventos.
* **API:** Criar APIs RESTful para aplicativos móveis e web.
