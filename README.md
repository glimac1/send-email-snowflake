# send-email-snowflake

Código de automatização em Python para envio de emails no Gmail, extraindo em xlsx o resultado de uma query rodada no Snowflake e enviando por email para uma lista de recipientes.

## Instruções:
- Configurar um python interpreter e definir o ambiente virtual
- Garantir a instalação dos pacotes requeridos (ver arquivo requirements.txt)*
- Imputar query desejada no arquivo EXAMPLE_QUERY.sql
- Inserir suas credenciais nos campos delimitados do Snowflake e do Gmail --> atenção: para o Snowflake, isso funcionará apenas se tiver um usuário e senha (excluindo SSO) e para o gmail será necessário configurar uma [senha de app](https://support.google.com/accounts/answer/185833?hl=pt-BR)

*OBS: o `snowflake-connector-python` deve ser instalado seguindo a [documentação do Snowflake](https://docs.snowflake.com/en/developer-guide/python-connector/python-connector-install), assim como o [pandas](https://docs.snowflake.com/en/developer-guide/python-connector/python-connector-pandas)
