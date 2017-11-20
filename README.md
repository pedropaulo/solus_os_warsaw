# WARSAW no SOLUS OS

Para executar o WARSAW da CAIXA ECONOMICA FEDERAL no SOLUS OS 3:

Instalar a dependência libnss 

Fazer o download do arquivo .DEB no site da CAIXA e descompatá-lo.

Em seguida, copiar alguns arquivos/pastas manualmente para seus respectivos diretório no SOLUS

- /usr/share/fonts/truetype/dbldwrsw.ttf
- /usr/local/bin/warsaw/*
- /usr/local/etc/warsaw/*
- /usr/local/lib/warsaw/*

Executar as permissões necessárias, de acordo com arquivo control/postinst

Executar o arquivo - /usr/local/bin/warsaw/wscertmgr para gerar o certificado

### Quando for entrar no site

Executar o - /usr/local/bin/warsaw/core

TESTADO no FIREFOX 56




