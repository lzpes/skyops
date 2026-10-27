# Levantamento de Requisitos

## Introdução

A especificação de requisitos é a base para a construção dos diagramas e da arquitetura do sistema. Ela define o escopo funcional e comportamental esperado pelos usuários e serve como contrato técnico entre analistas e operadores do setor aeronáutico.

## Técnicas de elicitação (simuladas)

- Simulação de entrevistas com profissionais de despacho e tripulação
- Análise de manuais regulatórios e procedimentos operacionais padrão (SOP)
- Benchmarking com soluções corporativas consolidadas no mercado internacional de aviação

## Requisitos funcionais

| ID | Descrição |
|----|-----------|
| RF01 | Gerenciar o ciclo de vida completo dos voos |
| RF02 | Registrar e acompanhar o status operacional da frota |
| RF03 | Escalonar pilotos e comissários |
| RF04 | Gerenciar manutenção preventiva e corretiva, integrando ordens de serviço e bloqueios de aeronaves |
| RF05 | Realizar o despacho operacional |
| RF06 | Calcular combustível |
| RF07 | Consultar dados meteorológicos |
| RF08 | Tratar disrupções |
| RF09 | Emitir alertas automáticos |
| RF10 | Gerar relatórios gerenciais de pontualidade (OTP) |
| RF11 | Administrar perfis e acessos via RBAC |

## Requisitos não funcionais

Conforme a norma ISO/IEC 25010.

| ID | Descrição |
|----|-----------|
| RNF01 | Cálculo de rotas e combustível processado pelo servidor em menos de 3 segundos |
| RNF02 | Disponibilidade de 99,9% para o sistema do OCC, em regime 24x7 |
| RNF03 | Criptografia em trânsito (TLS 1.3) e controle restrito de acesso |
| RNF04 | Trilhas de auditoria imutáveis |
| RNF05 | Interface web responsiva, adaptada a estações de trabalho e dispositivos móveis |
