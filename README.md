## Projeto Gateway Node JS - HiTech Sistemas

O projeto consiste em realizar chamadas de API de dois sistemas WEB distintos. O objectivo é buscar informações bi-direcionais de Produtos e Pedidos, tratar a informação e disparar requisições para as API's utilizando métodos GET, PUT e POST

## Tecnologias utilizadas

- OS Ubuntu 18.x
- Nginx
- Nvm
- Pm2 (para executar os projetos NODE JS)
- Vi (Vim)
- Certbot (SSL)
- SSMTP (para envio de notificações email via linha de comando linux)
- NODEMAILER (para enviar email atraves do código NODE JS)
  
## Rotinas

- Servidor linux com suporte ao protocolo HTTP e/ou HTTPS esta configurado para aceitar hospedagem temporária de imagens, processadas pelo gateway ERP2ECOMM para o envio da fotos dos produtos ERP, envia para API do sistema E-COMMERCE da flexy, também configurado para receber requisição HTTP/HTTPS e encaminhando para o NODEJS internamente, assim fica escutando a requisições enviadas pelo WEBHook do ECOMMERCE, processa as informações dos pedidos e inputa atraves da API do sistema ERP.

- O Crontab esta configurado para disparar o Gateway a cada 15min, monitorando novos produdos é atualizando-os.

## Telas disponíveis

- Tela linha de comando: ```node index.js```

![Console](https://user-images.githubusercontent.com/34343415/50668925-ec96ca80-0fa0-11e9-8c66-cfcbcd0e74a7.png)

- Tela da linda de comando: ```node index.js -id=1```

![Execute](https://user-images.githubusercontent.com/34343415/50668932-f7515f80-0fa0-11e9-92f7-836bb32c58e5.png)

- Tela de notificação via email.
  
![Notification Email](https://user-images.githubusercontent.com/34343415/50668939-fc161380-0fa0-11e9-8155-59231607c31a.png)

## Considerações Finais

Por questões de contrato não tenho autorização para publicar os códigos fontes, estarei apresentando apenas telas de processo executados.

