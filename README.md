
##  Microsoft Entra ID (anteriormente Azure AD)
**Microsoft Entra ID** é o serviço de gerenciamento de identidades e acessos da Microsoft para ambientes em nuvem e locais. Ele oferece funcionalidades essenciais para gerenciar autenticação e autorizações de usuários e dispositivos.

### Principais Funcionalidades do Microsoft Entra ID:
- **Autenticação de Usuários**: Autentica usuários para aplicativos e serviços no Azure e Microsoft 365.
- **Gerenciamento de Identidades**: Permite criar, gerenciar e proteger identidades dentro da organização.
- **Integração com Aplicações**: Funciona com aplicativos SaaS, personalizados e de terceiros para fornecer Single Sign-On (SSO).
- **Políticas de Acesso**: Define regras de acesso baseadas em risco e contexto, como localização e dispositivos.

##  Microsoft Entra Domain Services
**Microsoft Entra Domain Services** oferece suporte para domínios gerenciados no Azure, semelhante a um **Active Directory** local. Ele permite que as organizações usem autenticação baseada em diretório sem precisar gerenciar controladores de domínio.

### Principais Funcionalidades:
- **Compatibilidade com Active Directory**: Proporciona serviços como **Group Policy**, autenticação LDAP e **Kerberos**.
- **Gerenciamento Simples**: Oferece domínios gerenciados sem a necessidade de manutenção direta de controladores de domínio.
- **Sincronização Automática**: Sincroniza automaticamente os usuários, grupos e credenciais do Microsoft Entra ID.

---

## Métodos de Autenticação no Azure

## 1. Single Sign-On (SSO)
**SSO** permite que os usuários façam login uma única vez para acessar várias aplicações, eliminando a necessidade de lembrar múltiplas credenciais.


## 2. Autenticação Multifator (MFA)
**MFA** adiciona uma camada extra de segurança, exigindo dois ou mais métodos de verificação (senha e um segundo fator como um código enviado para o celular ou um token de autenticação).

- Um exemplo de autenticação sem senha é o **Microsoft Authenticator** que permite que o usuário aprove ou rejeite uma solicitação de login diretamente no aplicativo.

---

## Identidades Externas e Acesso de Convidado no Azure

## 1. Identidades Externas
Permite que você compartilhe recursos e colabore com usuários fora da sua organização, oferecendo uma maneira segura de conceder acesso aos seus sistemas no Azure.

## 2. Acesso de Convidado
**Acesso de Convidado** permite que indivíduos de fora da sua organização acessem recursos específicos (por exemplo, documentos do Microsoft 365 ou aplicativos Azure) com permissões restritas.

---

## Acesso Condicional no Microsoft Entra
O **Acesso Condicional** é uma ferramenta que permite controlar o acesso aos seus recursos com base em condições específicas. Ele usa sinais, como localização, tipo de dispositivo e identidade do usuário, para determinar se o acesso deve ser concedido ou negado.
