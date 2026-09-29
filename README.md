# MOP — Distribuição oficial

Aplicativo de monitoramento operacional para Windows, desenvolvido por **NOXUZ**.

Este repositório é destinado à distribuição dos instaladores oficiais, arquivos do atualizador automático e notas de versão do MOP. O código-fonte do aplicativo permanece privado.

## Versão atual — 2.2.2

A versão pública mais recente é a **MOP 2.2.2**.

### Novidades da 2.2.2

- Passagem de turno reformulada em duas etapas independentes: **entrega** e **recebimento**.
- Autoria automática pelo usuário autenticado, eliminando campos manuais redundantes.
- Ciência das pendências críticas exigida somente no recebimento.
- Sincronização ajustada para completar uma entrega pendente com o recebimento sem reabrir passagens concluídas.
- Tutorial guiado no primeiro login, com opção de pular e refazer pela aba **Sobre**.
- Tutorial adaptado ao perfil do usuário e com apresentação visual menos intrusiva.
- Correções acumuladas de autoria, consistência operacional e testes aplicadas desde a 2.2.1.

### Correção da 2.2.1

- Corrigido o travamento da interface ao alterar um registro para **Resolvido** pelo dropdown de status.
- A confirmação nativa foi substituída por um modal próprio do MOP, evitando bloqueio de cliques e foco após a alteração.
- O fluxo foi validado para operadores e administradores, mantendo a interface utilizável após resolver registros.

### Principais novidades da 2.2.0

- Tela **Novidades do MOP** após o login, mostrando notas ainda não lidas das versões recentes.
- Recebimento obrigatório do turno antes de liberar ações operacionais.
- Ciência das pendências críticas e registro auditável de quem assumiu o turno, com data e hora.
- Login com **usuário ou e-mail + senha**.
- Indicador permanente do turno assumido.
- Melhorias visuais no seletor de status, componentes expansíveis e experiência geral da interface.
## Download

Acesse a página de [Releases](https://github.com/NOXUZ-CySec/MOP-Releases/releases) e utilize o instalador da versão mais recente.

Para a versão 2.2.2, os arquivos principais são `MOP-Instalador-2.2.2.exe`, `MOP-Instalador-2.2.2.exe.blockmap` e `latest.yml`.

Os arquivos “Source code” gerados automaticamente pelo GitHub não correspondem ao instalador do MOP.

## Atualização automática

A partir da versão **2.1.1**, o MOP pode consultar este repositório, detectar novas versões, baixar os arquivos necessários e oferecer a reinicialização para instalar a atualização. A **2.2.2** é a versão atual do canal de testes e será oferecida automaticamente aos clientes compatíveis em versões anteriores.

Para que uma release seja reconhecida corretamente, ela deve conter o instalador, o arquivo `.blockmap` e o `latest.yml` produzidos pelo processo oficial de build.

## Recursos atuais

Registros operacionais, passagem de turno com recebimento obrigatório, checklists e rotinas, alertas e prazos, anexos, relatórios PDF/Excel/CSV, indicadores, perfis de acesso por condomínio, sincronização entre estações, fila offline, revisão de conflitos, administração de acessos e login por usuário ou e-mail.

**O portal web/mobile ainda não está liberado.**

## Requisitos

Windows 10/11 64 bits. O instalador inclui o runtime necessário. O primeiro login e a sincronização exigem internet. O pacote atual não possui assinatura digital.

## Licença

Software proprietário desenvolvido por **NOXUZ**. A disponibilidade do instalador não concede acesso ou licença ao código-fonte.
