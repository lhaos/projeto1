# projeto1
Primeiro projeto de git para code-education

* Primeiramente o repositorio foi criado aqui normalmente, já com o arquivo READNE.md;
* Então com o comando git clone e url do repositorio, ele foi clonado para ser usado localmente;
* O arquivo.txt foi criado normalmente usando o vim e logo após os seguintes comandos foram dados: 
  1. git status;
  2. git add . ;
  3. git commit -m "arquivo.txt pronto para receber o push";
  4. git log (para verificar);
  5. git push origin master.
* Assim o repositorio online ficou atualizado e por fim o arquivo README foi alterado pelo próprio github online e commitado.

Atualização

* Todos os comandos dados para criar uma nova versão:
  1. git tag 0.1.0;
  2. git tag -l;
  3. git push --tag origin master;
  4. git pull;
  5. vim arquivo.txt;
  6. vim arquivonovo.txt;
  7. git status;
  8. git add . ;
  9. git commit -m "modificando arquivo anterior e adicionando arquivonovo";
  10. git log;
  11. git push origin master;
  12. vim README.md;
  13. git add . ;
  14. git commit -m "atualizando o README";
  15. git push origin master;
  16. git tag 0.1.1;
  17. git push --tag origin master.
