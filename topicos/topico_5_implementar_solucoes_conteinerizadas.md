<!-- markmap -->
<div style="text-align: center; width:100%; padding-bottom:20px;">
  <a href="topicos/topico_4_desenvolver_solucoes_que_usam_o_azure_cosmos_db.md" style="padding:50px;"><img src="../img/anterior.png" alt="Anterior" style="width:20px;height:20px;"></a>
  <a href="az-204_markmap.md" style="padding:50px;"><img src="../img/inicio.png" alt="Início" style="width:20px;height:20px;"></a>
  <a href="topicos/topico_6_implementar_autenticacao_e_autorizacao_de_usuario.md" style="padding:50px;"><img src="../img/proximo.png" alt="Próximo" style="width:20px;height:20px;"></a>
</div>

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
