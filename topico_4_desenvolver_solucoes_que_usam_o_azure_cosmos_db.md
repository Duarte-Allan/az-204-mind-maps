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
  <a href="topico_3_desenvolver_solucoes_que_usam_o_armazenamento_de_blobs.md" class="button">Anterior</a>
  <a href="az-204_markmap.md" class="button">Início</a>
  <a href="topico_5_implementar_solucoes_conteinerizadas.md" class="button">Próximo</a>
</div>

<div class="divider"></div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/az-204-develop-solutions-that-use-azure-cosmos-db.svg" alt="Azure Cosmos DB" width="50" height="50"> <br /> **Tópico 4: Desenvolver soluções que usam o Azure Cosmos DB**</div>

## **4.1 Conceitos Básicos**

* É um serviço de banco de dados multi-modelo distribuído globalmente
* Oferece alta disponibilidade e desempenho para aplicações modernas.
* Suporta diversos modelos de dados, incluindo:
  * Documentos
  * Tabelas
  * Chave-valor e grafos
  * Entre outros
* **Conta:** A instância do serviço Azure Cosmos DB.
* **Banco de dados:** Uma coleção de contêineres.
* **Contêiner:** Um conjunto de itens (documentos, tabelas, chaves ou grafos).
* **Item:** A unidade básica de dados armazenada em um contêiner.
* **Partições lógicas:** Fragmentação de dados para escalabilidade horizontal.
* **SLA (Service Level Agreement):** Garantias de latência, disponibilidade e consistência.

## **4.2 Modelos de Dados Suportados**

* **Documentos:** Armazenamento de dados JSON flexíveis e sem esquema rígido.
* **Tabelas:** Modelos de dados relacionais com linhas e colunas.
* **Chave-valor:** Armazenamento de pares chave-valor.
* **Grafos:** Representação de dados conectados através de nós e relacionamentos.

## **4.3 Características-chave**

* **Distribuição global:** Replicação de dados em múltiplas regiões para alta disponibilidade e baixa latência.
* **Escalabilidade automática:** Ajuste automático do provisionamento para atender à demanda.
* **Alta disponibilidade:** Garantia de 99,999% de disponibilidade.
* **Baixa latência:** Leitura e escrita com latência de milissegundos.
* **Consistência ajustável:** Escolha entre diferentes níveis de consistência para equilibrar desempenho e disponibilidade.

## **4.4 Cenários de Uso**

* **Aplicações móveis e web:** Armazenamento de dados de usuários, preferências e configurações.
* **Internet das Coisas (IoT):** Armazenamento e análise de dados de dispositivos conectados.
* **Análise de dados:** Armazenamento de dados para análise em tempo real e batch.
* **Games:** Armazenamento de dados de jogos, como pontuações e progressos dos jogadores.
* **Catálogos:** Criação de catálogos de produtos e serviços.

## **4.5 Integração com Outros Serviços**

* **Azure Functions:** Trigger para eventos do Cosmos DB e bindings para interagir com dados.
* **Azure Data Factory:** Mover e transformar dados entre diferentes fontes de dados.
* **Azure Stream Analytics:** Processamento de dados em tempo real.
* **Power BI:** Visualização e análise de dados.

## **4.6 Considerações de Desempenho e Custo**

* **Provisionamento de capacidade:** Escolher o nível de throughput e armazenamento adequado.
* **Partições lógicas:** Dividir os dados em partições para melhorar o desempenho de consultas.
* **Índices:** Criar índices para acelerar consultas.
* **SLA:** Escolher o SLA que melhor se adapta às suas necessidades.




