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
  <a href="topico_2_implementar_o_azure_functions.md" class="button">Anterior</a>
  <a href="az-204_markmap.md" class="button">Início</a>
  <a href="topico_4_desenvolver_solucoes_que_usam_o_azure_cosmos_db.md" class="button">Próximo</a>
</div>

<div class="divider"></div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/develop-solutions-that-use-blob-storage.svg" alt="Blob-Storage" width="50" height="50"> <br /> **Tópico 3: Desenvolver soluções que usam o Armazenamento de Blobs**</div>

## **3.1 Conceitos Básicos**

* É um serviço de armazenamento de objetos altamente escalável e durável, ideal para armazenar grandes volumes de dados não estruturados.
* **Blob:** Unidade básica de armazenamento no Azure Blob Storage.
* **Container:** Contêiner lógico para organizar os blobs.
* **Tipos de Blob:** Blobs de bloco, blobs de página e blobs de append.
* **Níveis de Acesso:** Público, privado e com assinatura.
* **Versões:** Permite restaurar versões anteriores de um blob.
* **Geo-redundância:** Replicação dos dados em outra região para alta disponibilidade.

## **3.2 Operações com Blobs**

* **Criar, listar e excluir blobs:** Utilizando o portal do Azure, Azure CLI, PowerShell ou SDKs.
* **Carregar e baixar blobs:** Transferência de dados entre o armazenamento local e o Azure.
* **Atualizar propriedades de blobs:** Metadata, conteúdo, tags.
* **Gerenciar containers:** Criar, listar, excluir e configurar permissões.

## **3.3 Cenários de Uso**

* **Armazenamento de arquivos de mídia:** Imagens, vídeos, áudio.
* **Backups de máquinas virtuais:** Armazenar backups de máquinas virtuais do Azure.
* **Data Lakes:** Armazenar grandes volumes de dados para análise.
* **Conteúdo estático para sites:** Hospedar arquivos HTML, CSS e JavaScript.
* **Arquivos de configuração:** Armazenar configurações de aplicativos.

## **3.4 Integração com Outros Serviços**

* **Azure Functions:** Utilizar triggers e bindings para interagir com o armazenamento de blobs.
* **Azure Data Factory:** Mover e transformar dados entre diferentes fontes de dados.
* **Azure Machine Learning:** Armazenar dados para treinamento de modelos de machine learning.

## **3.5 Considerações de Desempenho e Custo**

* **Níveis de acesso:** Escolher o nível de acesso adequado para cada blob.
* **Geo-redundância:** Avaliar a necessidade de replicação dos dados em outra região.
* **Versões:** Definir a política de retenção de versões.
* **Tier de acesso:** Escolher o tier de acesso adequado (hot, cool, archive) com base na frequência de acesso.
