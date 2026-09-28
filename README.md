# MOP — Distribuição oficial

Aplicativo de monitoramento operacional para Windows, desenvolvido por **NOXUZ**.

Este repositório é destinado à distribuição dos instaladores oficiais, arquivos do atualizador automático e notas de versão do MOP. O código-fonte do aplicativo permanece privado.

## Versão atual — 2.1.1

A versão pública mais recente é a **MOP 2.1.1**.

### Novidades da 2.1.1

- Atualização automática integrada.
- Verificação de novas releases diretamente neste repositório.
- Download da nova versão pelo próprio aplicativo.
- Reinício assistido para instalação da atualização.
- Publicação dos artefatos exigidos pelo updater: `latest.yml`, instalador `.exe` e `.blockmap`.
- Melhorias de privacidade e identificação operacional por nome de exibição e identificador interno.

## Download

Acesse a página de [Releases](https://github.com/NOXUZ-CySec/MOP-Releases/releases) e utilize o instalador da versão mais recente.

Para a versão 2.1.1, os arquivos principais são `MOP-Instalador-2.1.1.exe`, `MOP-Instalador-2.1.1.exe.blockmap` e `latest.yml`.

Os arquivos “Source code” gerados automaticamente pelo GitHub não correspondem ao instalador do MOP.

## Atualização automática

A partir da versão **2.1.1**, o MOP pode consultar este repositório, detectar novas versões, baixar os arquivos necessários e oferecer a reinicialização para instalar a atualização. Para que uma release futura seja reconhecida corretamente, ela deve conter o instalador, o arquivo `.blockmap` e o `latest.yml` produzidos pelo processo oficial de build.

## Recursos atuais

Registros operacionais, passagem de turno, checklists e rotinas, alertas e prazos, anexos, relatórios PDF/Excel/CSV, indicadores, perfis de acesso por condomínio, sincronização entre estações, fila offline, revisão de conflitos e administração de acessos.

**O portal web/mobile ainda não está liberado.**

## Requisitos

Windows 10/11 64 bits. O instalador inclui o runtime necessário. O primeiro login e a sincronização exigem internet. O pacote atual não possui assinatura digital.

## Licença

Software proprietário desenvolvido por **NOXUZ**. A disponibilidade do instalador não concede acesso ou licença ao código-fonte.
