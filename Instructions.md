# Passo-a-Passo para aplicar pacote de tradução #

  1. Descompactar a pasta em seu desktop.
  1. Dentro das pasta terá arquivos com extensão .properties... copiar estes arquivos nas respectivas pastas onde encontram-se instalado seu Alfresco. A maneira simples de fazer isto é:
    1. `cp -pr <directorio_do_pacote>/explorer/config/alfresco/* <directorio_do_Alfresco>/tomcat/shared/classes/alfresco/extension`
  1. Fazer o mesmo com o arquivo web-client-config. Uma maneira simples de fazer isto é:
    1. `cp -pr <directorio_do_pacote>/share/config/alfresco/* <directorio_do_Alfresco>/tomcat/shared/classes/alfresco/web-extension`
  1. Reiniciar o serviço do Alfresco e sair para o abraço.