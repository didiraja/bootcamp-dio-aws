# Bootcamp GFT/DIO - Fundamentos de Cloud com AWS
Arquivos referentes ao Bootcamp GFT - Fundamentos de Cloud com AWS

## Módulo 2
Diagrama criado com Draw.io representando o fluxo de um sistema que gera resumo de vídeos do youtube periodicamente.

`Lambda Function`, atua como um Cron Job e uma vez por dia avisa aplicação, rodando em máquina `EC2`, que busca vídeo de um canal no `Youtube`, ao ser acessado, retorna metadados do último vídeo de volta para `EC2` que gera um arquivo de resumo do vídeo, que é armazenado em um bucket `S3`.