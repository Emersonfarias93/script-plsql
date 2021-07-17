# script-plsql #Exemplotrigger
**Trigger de statement**

Os Triggers do tipo STATEMENT tem a finalidade de tratar a execução de ações sobre tabelas
independentemente de quantas linhas forem afetadas. Através deste tipo de Trigger podemos
registrar a execução de comandos INSERT, UPDATE e DELETE contra tabelas que tenham Triggers
contemplando essas ações.
Caso um comando UPDATE atualize 1000 linhas, um Trigger deste tipo apenas dispararia 1 única vez.
Este tipo de Trigger não pode referenciar qualquer valor contido em uma coluna da tabela.
Isso ocorre porque se o mesmo dispara uma única vez.
Este tipo de Trigger funciona nos casos de registro de transações ocorridas, independentemente do numero de linhas afetadas.

**By: Emerson de Farias Santos**
