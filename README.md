# ForSign Monitor

O **ForSign Monitor** é uma aplicação que simplifica o processo de envio de arquivos para o ForSign, oferecendo monitoramento em tempo real e controle eficiente. Este aplicativo é compatível com sistemas Windows e macOS (Intel).

## Instalação

1. Faça o download do aplicativo para o seu sistema operacional a partir das [releases](https://github.com/forsign-digital/forsign-monitor/releases).
2. Siga as instruções de instalação apropriadas para o seu sistema.

## Configuração

Ao iniciar o aplicativo, você será solicitado a configurar suas credenciais e preferências.

1. **Opção 1: Configuração Manual**
    - Insira o diretório que deseja monitorar.
    - Informe a sua API Key.

2. **Opção 2: Login**
    - Insira o diretório que deseja monitorar e clique em `Fazer login`.
    - Faça login com seu e-mail e senha.
    - Escolha a empresa para a qual deseja se autenticar.

## Funcionalidades

### Monitoramento em Tempo Real

O aplicativo mapeia o diretório especificado, monitorando-o continuamente. Quando um novo arquivo PDF é detectado, ele é automaticamente enviado para o ForSign.

### Registro de Envios

Você pode consultar o log de envios, contendo informações como:
- Nome da operação
- Hora de atualização
- Status do envio (Pendente, Sincronizando, Sucesso ou Falha)

### Ações Adicionais

- **Reenvio (Status: Pendente):** Se o status for "Pendente", é possível reenviar o arquivo.
- **Detalhes do Erro (Status: Falha):** Se ocorrer uma falha, é possível consultar os detalhes do erro para solucionar problemas.

### Operações Bem-sucedidas

- **Abrir Operação (Status: Sucesso):** Caso o envio tenha sido bem-sucedido, você pode abrir a operação diretamente do log.
