# Script de Provisionamento Automático do Servidor Web

Este projeto tem como objetivo criar um script para a provisionamento automático de um servidor web. Um servidor web é composto por software e hardware que utiliza o protocolo HTTP (Hypertext Transfer Protocol) e outros protocolos para responder às solicitações dos clientes feitas pela World Wide Web. O principal objetivo de um servidor web é exibir o conteúdo de um site, armazenando, processando e entregando páginas da web aos usuários.

## Funcionalidades

O script de provisionamento automático realiza as seguintes etapas:

1. Atualiza a lista de pacotes disponíveis no sistema operacional.
2. Atualiza os pacotes instalados para suas versões mais recentes.
3. Instala o servidor web Apache 2.
4. Instala o utilitário "unzip" para descompactar arquivos ZIP.
5. Baixa e extrai os arquivos da aplicação de um repositório do GitHub.
6. Copia os arquivos da aplicação para o diretório padrão do Apache, onde serão servidos pela web.

## Utilização

Para utilizar o script de provisionamento automático, siga as instruções abaixo:

1. Clone este repositório em sua máquina:
   ```
   git clone https://github.com/seu-usuario/provisionamento-servidor-web.git
   ```

2. Navegue até o diretório do projeto:
   ```
   cd provisionamento-servidor-web
   ```

3. Execute o script de provisionamento:
   ```
   bash provisionamento.sh
   ```

   Observação: é necessário ter privilégios de administrador (root) para executar o script.

4. Aguarde até que o script seja concluído. Ele realizará automaticamente as etapas de atualização do sistema, instalação do Apache e configuração da aplicação.

5. Após a conclusão do script, os arquivos da aplicação estarão disponíveis em seu servidor web, acessíveis através do endereço IP do servidor ou do nome de domínio configurado.

## Considerações Finais

Este projeto oferece uma solução prática para o provisionamento automático de um servidor web, utilizando o script fornecido. É importante ressaltar que o script foi projetado para sistemas operacionais baseados em Debian, como o Ubuntu. Caso esteja utilizando um sistema operacional diferente, algumas adaptações podem ser necessárias.

Antes de executar o script, é recomendável revisar e entender seu conteúdo para garantir que seja adequado ao seu ambiente e requisitos específicos. É responsabilidade do usuário configurar corretamente o servidor web e a aplicação após a conclusão do script, de acordo com suas necessidades.

**Aviso**: Este script foi criado apenas para fins educacionais e de demonstração. Sempre leve em consideração as boas práticas de segurança ao configurar e implantar um servidor web em um ambiente de produção.