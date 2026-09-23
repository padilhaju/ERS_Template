# 3. Requisitos do Software

Esta seção detalha os requisitos do sistema, organizados em requisitos funcionais, não funcionais, de hardware e regras de negócio.

## 3.1 Requisitos Funcionais

Os requisitos funcionais detalham as interações que os usuários terão com o sistema. Devem ser corretos, rastreáveis, inequívocos, verificáveis, priorizados e identificados exclusivamente.

| # | Requisito | Descrição dos Requisitos Funcionais | Prioridade |
| :--- | :--- | :--- | :--- |
| **RF 01** | Login com Gmail | O software deverá permitir o usuário realizar login com sua conta do Gmail. | ALTA |
| **RF 02** | | | |
| **RF 03** | | | |
| **RF 04** | | | |
| **RF 05** | | | |
| **RF 06** | | | |


## 3.2 Requisitos Não Funcionais

Descrevem atributos de qualidade do software (desempenho, usabilidade, segurança, etc.).

### 3.2.1 Usabilidade
| # | Descrição dos Requisitos Não Funcionais |
| :--- | :--- |
| **RNF 01** | O software deverá seguir o padrão xxx. |
| **RNF 02** | |
| **RNF 03** | |

### 3.2.2 Confiabilidade
| # | Descrição dos Requisitos Não Funcionais |
| :--- | :--- |
| **RNF 01** | O software deverá possuir mecanismo que garanta ao usuário que nenhuma informação dele será perdida. |
| **RNF 02** | |

### 3.2.3 Desempenho
| # | Descrição dos Requisitos Não Funcionais |
| :--- | :--- |
| **RNF 01** | Não possui. |
| **RNF 02** | |

### 3.2.4 Segurança
| # | Descrição dos Requisitos Não Funcionais |
| :--- | :--- |
| **RNF 01** | Não possui. |
| **RNF 02** | |

### 3.2.5 Acessibilidade
| # | Descrição dos Requisitos Não Funcionais |
| :--- | :--- |
| **RNF 01** | Não possui. |
| **RNF 02** | |

### 3.2.6 Portabilidade
| # | Descrição dos Requisitos Não Funcionais |
| :--- | :--- |
| **RNF 01** | Não possui. |
| **RNF 02** | |

### 3.2.7 Requisitos de Hardware

| # | Descrição dos Requisitos de Hardware |
| :--- | :--- |
| **RH 01** | Memória RAM: Mínimo de 8 GB para garantir um desempenho fluido durante a execução da aplicação. Recomenda-se 16 GB para operações mais intensivas. |
| **RH 02** | |
| **RH 03** | |


---
### 3.4 Histórias de Usuário

Cada requisito funcional corresponde a uma história do usuário no formato: *Como [tipo de usuário], eu quero [objetivo] para que [benefício].*

#### História de Usuário 1 (referente a RF 01)
* **História:** Como administrador, eu quero gerenciar os usuários do sistema para que eu possa garantir que apenas pessoas autorizadas tenham acesso às informações.
* **Critérios de Aceitação:**
  1. O administrador deve ser capaz de adicionar novos usuários ao sistema.
  2. O administrador deve poder editar as permissões de acesso de usuários existentes.
  3. O sistema deve enviar uma notificação ao usuário quando seu acesso for alterado.
  4. O sistema deve rejeitar tentativas de adicionar usuários com informações incompletas.

---
### 3.5 Matriz de Rastreabilidade de Requisitos

**Matriz de Rastreabilidade de Requisitos (RTM)** é uma ferramenta de gestão de projetos utilizada para mapear, acompanhar e validar o ciclo de vida de um requisito, desde a sua concepção inicial até a sua implementação e fase de testes. 

O seu principal objetivo é garantir o **alinhamento do escopo**, permitindo que a equipe de desenvolvimento e as partes interessadas verifiquem se todos os requisitos de negócio foram transformados em funcionalidades reais (como Histórias de Usuário) e devidamente testados. Além disso, a matriz ajuda a identificar se há códigos ou tarefas "órfãs" (que não atendem a nenhum requisito) e facilita a análise de impacto caso ocorra alguma mudança no escopo do projeto.

---

## Exemplo de Matriz de Rastreabilidade Simplificada

A tabela abaixo ilustra o mapeamento direto entre os Requisitos Funcionais (RF) do sistema e as suas respectivas Histórias de Usuário (US). 

> **Nota:** Um único Requisito Funcional pode ser desmembrado em mais de uma História de Usuário, dependendo da complexidade da entrega.

| Código do Requisito | Nome do Requisito Funcional | Código da História de Usuário (US) |
| :--- | :--- | :--- |
| **RF 01** | Gerenciamento de Usuários | US 01 |
| **RF 02** | Cadastro de Produtos | US 02 |
| **RF 03** | Emissão de Relatório Mensal | US 03, US 04 *(Um RF pode gerar mais de uma US)* |

---

## 3.6 Regras de Negócio

As regras de negócio definem as diretrizes, restrições e condições que impactam as operações e processos do software.

| # | Descrição das Regras de Negócio |
| :--- | :--- |
| **RN 01** | Não possui. |
| **RN 02** | |
| **RN 03** | |
