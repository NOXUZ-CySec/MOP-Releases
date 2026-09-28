# MOP — Distribuição oficial

Aplicativo de monitoramento operacional para Windows, desenvolvido por **NOXUZ**.

Este repositório é destinado exclusivamente à distribuição de instaladores, instruções para usuários/testadores e notas de versão. O código-fonte do MOP é privado e não é distribuído aqui.

## Downloads e versões

Acesse [Releases](https://github.com/NOXUZ-CySec/MOP-Releases/releases) e confira a versão, o estado de homologação e as notas antes de baixar o instalador anexado. Os arquivos automáticos “Source code” do GitHub correspondem a este repositório de distribuição; não são o instalador do aplicativo.

A próxima versão 2.2.0 está em preparação. Não considere uma funcionalidade disponível até que ela conste nas notas de uma build publicada. A 2.1.0 não possui o verificador de atualizações integrado planejado para a 2.2.0.

## Recursos da base 2.1.0

- Registros operacionais com protocolo, condomínio, prioridade, responsável, prazo, acompanhamento e histórico.
- Passagem de turno com fotografia das pendências e ciência de itens críticos. Nesta base, quem recebe registra a passagem.
- Checklists e rotinas por turno, diárias, semanais, mensais ou únicas, com histórico de execução.
- Alertas de urgência e prazos, confirmação de ciência e notificações do Windows quando permitidas, com o aplicativo aberto.
- Anexos/evidências PNG, JPEG e PDF, até 512 KB por arquivo.
- Relatório PDF com histórico e passagens; listagem de registros em Excel e CSV; indicadores operacionais.
- Perfis de consulta, operador, supervisor e administrador, com acesso limitado aos condomínios autorizados.
- Sincronização entre estações autorizadas, fila offline e revisão de conflitos.

**O portal web/mobile ainda não está liberado.** A opção informativa no aplicativo não representa um serviço disponível para acesso pelo navegador ou celular.

## Requisitos e instalação

1. Utilize Windows 10/11 de 64 bits. O instalador inclui o runtime; não é necessário instalar Node.js ou ferramentas de desenvolvimento.
2. Baixe o arquivo `MOP-Instalador-<versão>.exe` anexado à release escolhida e execute-o.
3. Abra o MOP com internet disponível para o primeiro login. Utilize uma conta autorizada pelo administrador da sua central; cadastro de conta e autorização de acesso são etapas distintas.
4. Aguarde a sincronização e confira os condomínios disponíveis para seu perfil.

O pacote atual não possui assinatura digital. O Windows pode apresentar aviso de editor desconhecido; confirme a origem do arquivo e siga as orientações de TI da sua organização.

## Atualização e dados

Salve um backup, feche o MOP e execute o novo instalador disponibilizado nas Releases. Os dados locais ficam no perfil do usuário do Windows, fora da pasta de instalação. Não apague a pasta de dados para atualizar. Confira a versão na área Sobre e valide seus registros e a sincronização após a atualização.

Após um login online autorizado, o último operador validado pode acessar a estação offline com a mesma conta e senha por até sete dias, desde que a proteção local de credenciais esteja disponível. Alterações ficam na fila até a reconexão. O primeiro acesso exige internet. Revogações de acesso só podem ser conhecidas pela estação ao reconectar.

Conflitos exigem escolher a versão do registro que deve prevalecer; não há fusão automática por campo. Backups locais devem ser protegidos e guardados também em local adequado à política da organização.

## Homologação

Use dados de teste e valide com o administrador:

- Login, permissões e condomínios permitidos.
- Criação e atualização de registros nas duas estações, comparando o protocolo MOP.
- Checklists, anexos, alertas, passagem de turno e exportações.
- Trabalho offline, reabertura, reconexão e revisão de conflitos.
- Preservação dos registros e configurações após instalar uma nova versão.

Consulte as notas de cada release para novidades, limitações e estado de teste. Ao relatar problemas, informe a versão instalada e os passos para reproduzir, sem publicar senhas, dados pessoais, registros operacionais ou backups neste repositório público.

## Licença

Software proprietário desenvolvido por NOXUZ. A disponibilidade do instalador não concede acesso ou licença ao código-fonte.
