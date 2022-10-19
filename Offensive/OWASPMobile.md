# OWASP Top 10 Mobile 

A [Open Web Application Security Project (OWASP)](https://owasp.org/) é uma comunidade online que produz artigos, documentação, ferramentas, etc, de forma gratuita e liderado por uma organização sem fins lucrativos chamada The OWASP Foundation. Além desse Top 10 Mobile, tem a versão de vulnerabilidades Web, APIs... 

A última versão do Top 10 voltada para dispositivos móveis foi feita em 2016, e é usada desde então. A lista está presente na imagem a seguir e vamos entrar mais nos detalhes abaixo. 

![image](https://user-images.githubusercontent.com/37185061/196790493-78f1ab10-ef1a-4d10-ba91-286939b3776e.png)

## M1: Improper Platform Usage

[Essa vulnerabilidade](https://owasp.org/www-project-mobile-top-10/2016-risks/m1-improper-platform-usage) é referente ao **uso indevido de um recurso da plataforma ou a falha no uso de controles de segurança da plataforma**. Pode incluir permissões do próprio Android/iOS, permissões da aplicação, uso indevido de TouchID, Keychain ou algum outro controle de segurança que faça parte do sistema operacional.

Qualquer chamada de API exposta pode servir como vetor de ataque, o que faz com que seja uma falha potencialmente fácil de ser explorada.

### Como prevenir essa vulnerabilidade?

Práticas de Desenvolvimento Seguro, configurações e validações de segurança também devem ser realizadas do lado do servidor.

