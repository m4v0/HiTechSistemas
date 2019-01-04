## Projeto Gateway Node JS - HiTech Sistemas

O projeto consiste em realizar chamadas de API de dois sistemas WEB distintos. O objectivo é buscar informações bi-direcionais de Produtos e Pedidos, tratar a informação e dispachar "disparar" para API em pode PUT e POST

## Tecnologias utilizadas

- OS Ubuntu 18.x
- Nginx
- Nvm
- Pm2 (para executar os projetos NODEJS)
- Vi (Vim)
- Certbot (SSL)
  
## Rotinas

- Servidor linux com suporte ao protocolo HTTP e/ou HTTPS esta configurado para aceitar hospedagem temporária de imagens, processadas pelo gateway ERP2ECOMM para o envio da fotos dos produtos ERP, envia para API do sistema E-COMMERCE da flexy, também configurado para receber requisição HTTP/HTTPS e encaminhando para o NODEJS internamente, assim fica escutando a requisições enviadas pelo WEBHook do ECOMMERCE, processa as informações dos pedidos e inputa atraves da API do sistema ERP.

- O Crontab esta configurado para disparar o Gateway a cada 15min, monitorando novos produdos é atualizando-os.

## Telas disponíveis

![Console](https://raw.githubusercontent.com/m4v0/HiTechSistemas/master/ERP2COMM/ERP2ECOMM-CLI-SCREEN-01.png)

## Considerações Finais

Por questões de contrato não tenho autorização para publicar os códigos fontes, estarei apresentando apenas telas de processo executados.

