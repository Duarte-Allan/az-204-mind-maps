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
  <a href="topico_4_desenvolver_solucoes_que_usam_o_azure_cosmos_db.md" class="button">Anterior</a>
  <a href="az-204_markmap.md" class="button">Início</a>
  <a href="topico_6_implementar_autenticacao_e_autorizacao_de_usuario.md" class="button">Próximo</a>
</div>

<div class="divider"></div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/iaas-implement-solutions.svg" alt="Soluções Conteinerizadas" width="50" height="50"> <br /> **Tópico 5: Implementar Soluções Conteinerizadas**</div>

## **5.1 Conceitos Básicos**

* Processo de empacotar um aplicativo e suas dependências em um contêiner isolado
* Garante o funcionamento de forma consistente em diferentes ambientes. 
* O **Docker** é a plataforma mais popular para criar e gerenciar containers.
* **Container:** Um pacote leve e independente que contém um aplicativo e todas as suas dependências.
* **Imagem de container:** Um modelo a partir do qual os containers são criados.
* **Orquestrador de containers:** Ferramenta para gerenciar e escalar um conjunto de containers (por exemplo, Kubernetes).

## **5.2 Serviços do Azure para Containers**

* **Azure Container Instances (ACI):** Ideal para executar containers isolados de forma rápida e fácil.
* **Azure Kubernetes Service (AKS):** Plataforma gerenciada para orquestrar clusters Kubernetes.
* **Azure Container Registry:** Armazenamento privado para imagens de container.

## **5.3 Processo de Conteinerização**

1. **Criar uma Dockerfile:** Um arquivo de texto que contém as instruções para construir a imagem do container.
2. **Construir a imagem:** Utilizar o comando `docker build` para criar a imagem a partir do Dockerfile.
3. **Executar o container:** Utilizar o comando `docker run` para iniciar um container a partir da imagem.
4. **Empurrar a imagem para um registro:** Utilizar o comando `docker push` para enviar a imagem para um registro de containers (como o Azure Container Registry).
5. **Implantar a imagem em um ambiente:** Utilizar um orquestrador de containers para implantar a imagem em um cluster.

## **5.4 Benefícios da Conteinerização**

* **Portabilidade:** Rodar o mesmo aplicativo em qualquer ambiente que suporte containers.
* **Escalabilidade:** Escalar horizontalmente para atender à demanda.
* **Isolamento:** Isolar aplicativos em containers separados para evitar conflitos.
* **Agilidade:** Facilitar o desenvolvimento e a implantação de aplicativos.

## **5.5 Cenários de Uso**

* **Microsserviços:** Dividir aplicações monolíticas em pequenos serviços independentes.
* **Desenvolvimento e testes:** Criar ambientes de desenvolvimento isolados.
* **CI/CD:** Automatizar o processo de build, teste e implantação.

## **5.6 Considerações**

* **Escolha do serviço:** Escolher o serviço Azure adequado com base nas suas necessidades (ACI, AKS, etc.).
* **Gerenciamento de estado:** Decidir como persistir os dados dos containers (volumes, bancos de dados).
* **Rede:** Configurar a rede para permitir a comunicação entre os containers.
* **Segurança:** Implementar medidas de segurança para proteger os containers.
