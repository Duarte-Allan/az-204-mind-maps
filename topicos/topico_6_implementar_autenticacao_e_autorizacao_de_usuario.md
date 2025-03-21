<!-- markmap -->
<div style="text-align: center; width:100%; padding-bottom:20px;">
  <a href="topico_5_implementar_solucoes_conteinerizadas.md" style="padding:50px;"><img src="../img/anterior.png" alt="Anterior" style="width:20px;height:20px;"></a>
  <a href="../az-204_markmap.md" style="padding:50px;"><img src="../img/inicio.png" alt="Início" style="width:20px;height:20px;"></a>
  <a href="topico_7_implementar_solucoes_seguras_do_azure.md" style="padding:50px;"><img src="../img/proximo.png" alt="Próximo" style="width:20px;height:20px;"></a>
</div>

# <div style="text-align: center; width:100%;"><img src="https://learn.microsoft.com/pt-br/training/achievements/authentication-authorization.svg" alt="Autenticação e Autorização" width="50" height="50"> <br /> **Tópico 6: Implementar Autenticação e Autorização de Usuário**</div>

## **6.1 Conceitos Básicos**

* São os pilares fundamentais para garantir que apenas usuários autorizados acessem os recursos de um sistema.
* **Autenticação:** Processo de verificar a identidade de um usuário.
* **Autorização:** Processo de determinar quais recursos um usuário autenticado pode acessar.
* **Identidade:** Representação digital de um usuário, geralmente associada a um conjunto de credenciais (nome de usuário e senha, token, etc.).
* **Provedor de identidade:** Serviço que gerencia identidades e autenticação (ex: Azure Active Directory).

## **6.2 Métodos de Autenticação**

* **Baseado em senha:** O método mais comum, mas vulnerável a ataques.
* **Multi-fator:** Combina algo que o usuário sabe (senha) com algo que ele possui (token) ou é (biometria).
* **Baseado em token:** Utiliza tokens JWT (JSON Web Token) para representar a identidade do usuário.
* **Autenticação social:** Permite que os usuários se autentiquem usando contas de redes sociais.

## **6.3 Métodos de Autorização**

* **Baseado em papéis:** Atribui papéis aos usuários, definindo as permissões de cada papel.
* **Baseado em atributos:** Avalia atributos do usuário ou do recurso para determinar o acesso.
* **Baseado em listas de controle de acesso (ACLs):** Define explicitamente quais usuários têm acesso a quais recursos.

## **6.4 Implementando Autenticação e Autorização no Azure**

* **Azure Active Directory (Azure AD):** O serviço de identidade da Microsoft, ideal para gerenciar identidades e controlar o acesso a aplicativos e recursos.
* **Azure App Service:** Integração com Azure AD para autenticação e autorização de aplicativos web e API.
* **Azure Functions:** Utilizar Azure AD para proteger o acesso a funções.
* **Azure API Management:** Gerenciar a segurança de APIs, incluindo autenticação e autorização.

## **6.5 Cenários de Uso**

* **Aplicativos web:** Proteger o acesso a áreas restritas do aplicativo.
* **APIs:** Controlar o acesso a dados e funcionalidades da API.
* **Serviços em nuvem:** Garantir que apenas usuários autorizados acessem os serviços.

## **6.6 Considerações**

* **Escolha do método de autenticação e autorização:** Avaliar os requisitos de segurança e usabilidade.
* **Gerenciamento de identidades:** Criar e gerenciar identidades de usuários e grupos.
* **Gerenciamento de acesso:** Definir as permissões de cada usuário ou grupo.
* **Segurança:** Implementar medidas de segurança para proteger as credenciais dos usuários.
