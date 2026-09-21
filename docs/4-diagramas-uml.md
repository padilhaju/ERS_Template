# 4. Diagramas UML

Nesta seção, apresentam-se os principais modelos de análise que auxiliam na compreensão da arquitetura e funcionamento do sistema.

## 4.1 Diagramas de Caso de Uso

*(Insira a imagem do seu Diagrama de Caso de Uso aqui, por exemplo: `![Diagrama de Caso de Uso](caminho/para/imagem.png)`)*

### Documentação do Caso de Uso: Encerrar Conta

| Campo | Descrição |
| :--- | :--- |
| **Ator principal** | Cliente |
| **Atores secundários** | Funcionário |
| **Resumo** | Este caso de uso descreve as etapas necessárias para que um cliente encerre uma conta. |
| **Pré-condições** | É necessário existir uma conta ativa. |
| **Pós-condições** | Nenhuma |

#### Fluxo Principal
| Ações do Ator | Ações do Sistema |
| :--- | :--- |
| 1. Solicitar encerramento de conta fornecendo o seu número. | |
| | 2. Executar caso de uso *Emitir Saldo*. |
| | 3. Encerrar a conta. |

**Restrições/Validações:**
1. A conta só pode ser encerrada pelo seu titular.
2. A conta só pode ser encerrada se o seu saldo estiver zerado.

#### Fluxo Alternativo I – Saldo Positivo
| Ações do Ator | Ações do Sistema |
| :--- | :--- |
| | 1. Executar caso de uso *Realizar Saque*. |

#### Fluxo Alternativo II – Saldo Negativo
| Ações do Ator | Ações do Sistema |
| :--- | :--- |
| 1. Fornecer valor para depósito. | |
| | 2. Executar caso de uso *Realizar Depósito*. |

#### Fluxo Alternativo III – Manutenção do Cadastro do Cliente
| Ações do Ator | Ações do Sistema |
| :--- | :--- |
| | 1. Se for a única conta do cliente, atualizar seu cadastro, tornando-o inativo. Executar o caso de uso *Manter Cliente*. |

*Fonte de referência: ENADE - Analista de Sistemas - INEP, 2017.*

---

## 4.2 Diagramas de Classe

Inclua aqui um diagrama que detalhe as principais classes do sistema, suas propriedades, métodos e as relações entre elas.
