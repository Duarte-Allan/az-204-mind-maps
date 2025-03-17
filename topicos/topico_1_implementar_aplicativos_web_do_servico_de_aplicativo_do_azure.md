<!-- markmap -->
<div style="text-align: center; width:100%; padding-bottom:20px;">
  <a href="../az-204_markmap.md" style="padding:50px;"><img src="../img/anterior.png" alt="Anterior" style="width:20px;height:20px;"></a>
  <a href="../az-204_markmap.md" style="padding:50px;"><img src="../img/inicio.png" alt="Início" style="width:20px;height:20px;"></a>
  <a href="topico_2_implementar_o_azure_functions.md" style="padding:50px;"><img src="../img/proximo.png" alt="Próximo" style="width:20px;height:20px;"></a>
</div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/azure-app-service-create-web-apps.svg" alt="AZ-204" width="50" height="50"> <br /> **Tópico 1: Implementar aplicativos Web do Serviço de Aplicativo do Azure**</div>

## **1.1 Criação e Configuração**

* **Planos de Serviço:**
  * Free: Ideal para desenvolvimento e testes.
  * Standard: Para aplicações de produção com recursos adicionais.
  * Premium: Para aplicações com alta demanda e requisitos específicos.
* **Escalabilidade:**
  * Manual: Ajustar manualmente os recursos.
  * Automática: Escalar com base em métricas (CPU, memória, etc.).
* **Slots de Implantação:**
  * Testar novas versões em um ambiente isolado.
  * Realizar rollbacks em caso de problemas.

## **1.2 Implantação de Código**

* **Métodos de Implantação:**
  * FTP: Upload de arquivos.
  * Git: Integração com repositórios Git (GitHub, Azure DevOps).
  * CI/CD: Automatização do processo de build e implantação.
* **Configuração de Ambiente:**
  * Variáveis de ambiente: Armazenar configurações específicas.
  * App Settings: Configurar valores personalizados.
  * Connection Strings: Configurar conexões com bancos de dados.

## **1.3 Autenticação e Autorização**

* **Azure Active Directory (Azure AD):**
  * Autenticação baseada em identidade.
  * Integração com OAuth 2.0 e OpenID Connect.
* **Funções de Aplicativo:**
  * Criar funções personalizadas para autenticar usuários.
* **Autorização baseada em papéis (RBAC):**
  * Controlar o acesso aos recursos do aplicativo.

## **1.4 Monitoramento e Diagnóstico**

* **Application Insights:**
  * Coletar telemetria (requisições, dependências, exceções).
  * Criar painéis personalizados.
* **Logs de Diagnóstico:**
  * Analisar logs para identificar problemas.
* **Alertas:**
  * Configurar alertas para eventos críticos.

## **1.5 Segurança**

* **SSL/TLS:**
  * Configurar certificados SSL para comunicação segura.
* **WAF (Web Application Firewall):**
  * Proteger contra ataques comuns (SQL injection, XSS).
* **Segurança de Aplicações:**
  * Validar entradas, evitar vulnerabilidades comuns.
* **Segurança de Rede:**
  * Utilizar Network Security Groups para controlar o tráfego.

## **1.6 Integração com Outros Serviços**

* **Azure Functions:**
  * Executar lógica personalizada em resposta a eventos.
* **Azure Event Hubs:**
  * Processar grandes volumes de eventos em tempo real.
* **Azure Service Bus:**
  * Enviar e receber mensagens assíncronas.
