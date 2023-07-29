# Gerador de Senhas

Este é um aplicativo simples de gerador de senhas criado usando a biblioteca React. Ele permite gerar senhas aleatórias com diferentes caracteres e copiar a senha gerada para a área de transferência.

## Como Usar

1. Abra o aplicativo em seu navegador.

2. Clique no botão "Gerar!" para gerar uma nova senha aleatória.

3. A senha gerada será exibida abaixo do botão "Gerar!".

4. Clique no botão "Copiar" para copiar a senha gerada para a área de transferência.

5. Após copiar a senha, o texto do botão "Copiar" será alterado para "Copiado!".

6. Você pode gerar quantas senhas desejar clicando repetidamente no botão "Gerar!".

## Funcionamento do Código

O código utiliza o React e o hook `useState` para gerenciar o estado da senha e do texto do botão. A função `generate` é responsável por gerar uma nova senha aleatória e a função `copyToClipboard` copia a senha gerada para a área de transferência.

O gerador de senhas utiliza os seguintes caracteres para compor a senha:

`'1234567890-=!@#$%¨&*()_+qwertyuiop[asdfghjklç~]zxcvbnm,.;/QWERTYUIOP{ASDFGHJKLÇ^}ZXCVBNM<>:?`

## Contribuindo

Se você encontrar algum problema ou tiver ideias para melhorar o Gerador de Senhas, sinta-se à vontade para contribuir! Você pode relatar problemas, sugerir melhorias ou enviar solicitações de pull para o repositório no GitHub.
