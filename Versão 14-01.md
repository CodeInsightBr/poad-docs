
# 📝 Changelog

## 📅 Versão 14/01

### 🚀 **Novidades e Ajustes**

### 📢 **Central de Notificação**

-   Criado módulo de configuração de notificação para departamentos/módulos.
    
-   Novo menu de configurações para gerenciamento de notificações: **Menu -> Configurações/Notificações**.
    
-   Implementado serviço de envio de notificações no backend.
    
    -   Permite selecionar usuários para disparo de notificações segmentadas por módulo.
        
    -   Suporte a alertas direcionados.
        

> O módulo de notificação tem como objetivo facilitar o direcionamento dos alertas dentro do sistema.

### 🏢 **Módulo: Locação**

#### **Locação - Intranet**

-   Ajustado o fluxo de anexação de documentos para assinatura:
    
    1.  **Gerar Documento**.
        
    2.  **Preparar para Assinatura**.
        
    3.  **Solicitar Assinatura**.
        

#### **Locação - Meu Clube**

-   Ajustada visualização de espaço, eliminando a necessidade de abas adicionais.
    
-   Melhorada validação de reserva para garantir consistência dos dados.
    
-   Implementada assinatura **embedded** do clisign, agora disponível no menu de visualização da assinatura da locação.
    
-   Disparo de e-mails para administradores conforme configuração no **módulo de notificação** e também para os próprios usuários.
    
-   Criados templates de e-mails:
    
    -   **Notificação de solicitação para administração**.
        
    -   **Confirmação de solicitação para o usuário**.

* É possivel visualizar documento para assinatura logando na conta: email: maiconphpnet@gmail.com senha: Teste.123
* Para realizar o processo em outra reserva basta solicitar uma reserva, anexar um docx na intranet, e seguir os passos, lembrando que é preciso preencher as variaveis depois de anexado o docx
