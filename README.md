# Desafio: Entendendo sobre Segurança e Identidade na Azure

Este documento resume os principais conceitos abordados durante o desenvolvimento do lab sobre segurança e identidade no Microsoft Azure, conforme os tópicos da certificação AZ-900.

## 🌐 Arquitetura e Serviços do Azure

O Azure é a plataforma de nuvem da Microsoft que oferece uma ampla gama de serviços para computação, armazenamento, rede e segurança. A arquitetura do Azure é baseada em datacenters distribuídos globalmente, garantindo alta disponibilidade, escalabilidade e segurança.

## 🔐 Identidade, Acesso e Segurança

Durante o lab, explorei os fundamentos de segurança e identidade no Azure, com foco nos seguintes tópicos:

### Microsoft Entra ID

- Serviço de gerenciamento de identidades e acesso baseado em nuvem.
- Permite autenticação, logon único (SSO), gerenciamento de aplicativos e dispositivos.
- Suporta cenários B2B para colaboração entre organizações.

### Microsoft Entra Domain Services

- Oferece serviços de domínio na nuvem sem necessidade de gerenciar controladores de domínio.
- Ideal para aplicações legadas que não suportam autenticação moderna.
- Sincroniza automaticamente com o Microsoft Entra ID.

### Autenticação vs Autorização

- **Autenticação**: Verifica a identidade do usuário ou serviço.
- **Autorização**: Define os níveis de acesso e permissões após a autenticação.

### Autenticação Multifator (MFA)

- Reforça a segurança exigindo dois ou mais fatores:
  - Algo que você sabe (senha)
  - Algo que você possui (dispositivo)
  - Algo que você é (biometria)

### Acesso Condicional

- Permite aplicar políticas com base em sinais como:
  - Grupo de usuários
  - Localização IP
  - Tipo de dispositivo
  - Aplicativo acessado
  - Detecção de risco

### RBAC (Controle de Acesso Baseado em Função)

- Garante acesso mínimo necessário aos recursos.
- Permite delegar tarefas com granularidade.
- Facilita o gerenciamento de permissões no portal do Azure.

### Confiança Zero (Zero Trust)

- Modelo de segurança que assume que nenhuma entidade é confiável por padrão.
- Requer verificação contínua de identidade, contexto e conformidade.

### Defesa em Profundidade

- Estratégia de segurança em camadas.
- Cada camada protege contra diferentes tipos de ameaças.
- Minimiza o impacto de ataques ao isolar componentes.

### Microsoft Defender para Nuvem

- Serviço de monitoramento e proteção contra ameaças.
- Oferece:
  - Recomendações de segurança
  - Detecção de malware
  - Análise de ataques
  - Controle de acesso just-in-time

---

Este lab foi essencial para compreender como o Azure protege identidades, gerencia acessos e aplica políticas de segurança robustas em ambientes corporativos. A abordagem integrada entre autenticação, autorização e monitoramento reforça a importância de uma arquitetura segura e confiável na nuvem. Como a abordagem foi mais teórica, optou-se por não gerar capturas de tela.
