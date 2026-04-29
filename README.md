Repositório oficial do programa que realiza Cópia de Segurança Incrementais de Arquivos Back In Time

https://github.com/bit-team/backintime


Plataforma de tradução do programa

https://translate.codeberg.org/projects/backintime/-/pt_BR/



Para utilizar os arquivos "backintime.desktop", "backintime-qt.desktop" e "backintime-qt-root.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

Utilize o comando para copiar cada um dos arquivos com a extensão ".desktop" para a pasta "/usr/share/applications".

$ sudo cp backintime.desktop /usr/share/applications

$ sudo cp backintime-qt.desktop /usr/share/applications

$ sudo cp backintime-qt-root.desktop /usr/share/applications


Utilize o comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
