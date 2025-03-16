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
  <a href="topico_7_implementar_solucoes_seguras_do_azure.md" class="button">Anterior</a>
  <a href="az-204_markmap.md" class="button">Início</a>
  <a href="topico_9_desenvolver_solucoes_baseadas_em_eventos.md" class="button">Próximo</a>
</div>

<div class="divider"></div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/az-204-implement-api-management.svg" alt="Gerenciamento de API" width="50" height="50"> <br /> **Tópico 8: Implementar o Gerenciamento de API**</div>

## **8.1 Conceitos-chave**

* **Gateway de API:** O ponto de entrada para todas as solicitações de API. Ele roteia as solicitações para os backends apropriados e aplica políticas.
* **Produtos:** Um conjunto de APIs que são agrupadas e publicadas para um conjunto específico de desenvolvedores.
* **APIs:** Representam as operações que podem ser realizadas em um serviço.
* **Políticas:** Regras personalizadas que podem ser aplicadas a solicitações e respostas de API, como autenticação, transformação de dados e rate limiting.
* **Desenvolvedores:** Usuários que consomem as APIs.

## **8.2 Benefícios do Gerenciamento de API**

* **Gerenciamento Centralizado:** Publique, proteja e analise todas as suas APIs em um único local.
* **Segurança:** Aplique políticas de segurança como autenticação, autorização e criptografia.
* **Escalabilidade:** Aumente ou diminua a capacidade do gateway de API para atender à demanda.
* **Análise:** Obtenha insights sobre o uso das suas APIs, como frequência de chamadas e erros.
* **Desenvolvimento de Desenvolvedores:** Forneça um portal para desenvolvedores registrarem seus aplicativos e obterem chaves de API.

## **8.3 Cenários de Uso**

* **Microserviços:** Exponha os microserviços como APIs para serem consumidos por outros aplicativos.
* **Integração de sistemas:** Conecte diferentes sistemas e aplicativos.
* **Plataformas de aplicativos móveis:** Forneça APIs para aplicativos móveis.
* **Internet das Coisas (IoT):** Crie APIs para conectar dispositivos IoT à nuvem.

## **8.4 Funcionalidades Principais**

* **Publicação de APIs:** Importe APIs existentes ou crie novas.
* **Gerenciamento de Produtos:** Organize as APIs em produtos e publique-as para diferentes públicos.
* **Políticas:** Aplique políticas como transformação de dados, rate limiting, autenticação e muito mais.
* **Análise:** Monitore o uso das APIs e obtenha insights sobre o desempenho.
* **Portal do Desenvolvedor:** Forneça um portal para desenvolvedores registrarem seus aplicativos e obterem chaves de API.

## **8.5 Implementação**

1. **Criar uma instância do serviço de Gerenciamento de API:** No portal do Azure.
2. **Importar ou criar APIs:** Adicionar as APIs que você deseja gerenciar.
3. **Configurar produtos:** Agrupar as APIs em produtos e definir as políticas.
4. **Criar um portal do desenvolvedor:** Permitir que os desenvolvedores se registrem e obtenham chaves de API.
5. **Publicar as APIs:** Tornar as APIs disponíveis para os desenvolvedores.

## **8.6 Considerações**

* **Escolha do plano:** Selecionar o plano de serviço que melhor atende às suas necessidades.
* **Políticas personalizadas:** Criar políticas personalizadas para atender aos requisitos específicos da sua aplicação.
* **Integração com outros serviços:** Integrar o Gerenciamento de API com outros serviços do Azure, como Azure Active Directory e Azure Functions.
