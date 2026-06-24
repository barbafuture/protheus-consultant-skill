# Protheus Consultant Skill

Uma Skill especializada para Claude focada em suporte, sustentação, parametrização, troubleshooting e consultoria funcional/técnica do ERP TOTVS Protheus.

## Objetivo

Transformar o Claude em um Consultor e Analista Sênior TOTVS Protheus capaz de:

* Resolver chamados de sustentação
* Analisar erros funcionais e técnicos
* Identificar causas raiz
* Consultar tabelas Protheus
* Validar parâmetros
* Analisar logs
* Gerar SQL
* Desenvolver ADVPL/TLPP
* Consultar documentação oficial TOTVS
* Realizar pesquisas web para validação de informações

## Especialidades

### Módulos

* Financeiro (SIGAFIN)
* Compras (SIGACOM)
* Estoque/Custos (SIGAEST)
* Faturamento (SIGAFAT)
* Fiscal (SIGAFIS)
* Contabilidade (SIGACTB)
* Gestão de Pessoal (SIGAGPE)
* PCP (SIGAPCP)
* Contratos (SIGAGCT)
* WMS
* TMS
* E outros

### Desenvolvimento

* ADVPL
* TL++
* MVC
* REST API
* ExecAuto
* Ponto de Entrada

### Infraestrutura

* AppServer
* SmartClient
* DBAccess
* License Server
* TSS

## Instalação

1. Baixe o repositório.
2. Compacte a pasta `skill`.
3. Faça upload da Skill no Claude.

## Estrutura

Veja a pasta `/skill` para a implementação principal.

## Exemplos

Os exemplos de utilização estão na pasta `/examples`.

## MCP Protheus Source Repository

Esta Skill pode ser integrada a um servidor MCP especializado que disponibiliza acesso controlado ao repositório completo de fontes do TOTVS Protheus Release 12.1.2510.

### O que o MCP disponibiliza

O servidor MCP permite ao Claude consultar diretamente:

* Fontes padrão da release 12.1.2510
* Framework Protheus
* Rotinas padrão
* Funções internas
* Classes MVC
* APIs REST nativas
* Pontos de Entrada
* Fontes do TSS
* Dicionário de Dados
* Arquivos de configuração
* Documentação técnica relacionada à release

A release 12.1.2510 introduz diversas alterações de Framework, segurança, infraestrutura e componentes que impactam diretamente customizações ADVPL, integrações e processos de sustentação.

### Capacidades da Skill com o MCP

Quando conectada ao MCP, a Skill passa a conseguir:

#### Localizar rotinas padrão

Exemplos:

* FINA330
* FINA050
* MATA261
* MATA103
* CTBA102
* GPEA240

#### Analisar código fonte nativo

Identificando:

* Regras de negócio
* Validações internas
* Fluxos de processamento
* Eventos
* Gatilhos
* Pontos de entrada utilizados

#### Mapear dependências

A Skill consegue identificar:

* Funções chamadas
* Classes utilizadas
* Relacionamentos entre fontes
* Dependências do Framework

#### Investigar erros

A partir de uma mensagem de erro, a Skill pode:

* Localizar o fonte responsável
* Identificar a rotina executada
* Explicar a regra aplicada
* Sugerir correções compatíveis com a release

### Casos de Uso

#### Sustentação

* Diagnóstico de chamados
* Investigação de comportamentos padrão
* Validação de correções

#### Desenvolvimento

* Criação de customizações
* Desenvolvimento ADVPL
* Desenvolvimento TL++
* Implementação MVC

#### Atualização de Release

* Análise de impactos
* Identificação de breaking changes
* Comparação entre versões
* Adequação de customizações

### Segurança

O acesso ao repositório de fontes é realizado em modo somente leitura.

A Skill:

* Não altera fontes
* Não recompila objetos
* Não modifica RPO
* Não altera dicionários
* Não executa comandos administrativos

Todo acesso é destinado exclusivamente à análise técnica e geração de respostas.

### Benefícios

Com acesso aos fontes nativos da release utilizada pela empresa, a Skill deixa de responder apenas com conhecimento genérico sobre Protheus e passa a atuar com base no comportamento real do produto instalado.

Isso aumenta significativamente a precisão em:

* Diagnóstico de erros
* Atendimento de chamados
* Explicação de regras de negócio
* Identificação de parâmetros
* Localização de tabelas
* Desenvolvimento ADVPL
* Troubleshooting avançado
* Sustentação N3

## Licença

MIT License.
