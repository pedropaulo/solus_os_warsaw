# WARSAW no SOLUS OS

Pra rodar o WARSAW da CAIXA ECONOMICA FEDERAL no SOLUS OS 3 , eu fiz o seguinte:

Instalei a dependência libnss 

Baixei e descompatei o arquivo .DEB no site da CAIXA.
Daí em diante, copiei alguns arquivos/pastas manualmente para seus respectivos diretório no SOLUS

- usr/share/fonts/truetype/dbldwrsw.ttf
- /usr/local/bin/warsaw/*
- /usr/local/etc/warsaw/*
- /usr/local/lib/warsaw/*

Dou as permissões necessárias, de acordo com arquivo control/postinst

Executo o arquivo - /usr/local/bin/warsaw/wscertmgr pra gerar o certificado

E depois executo o - /usr/local/bin/warsaw/core

Depois disso, entrei na CAIXA com o Firefox e funcionou.




