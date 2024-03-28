# Lição-do-dia-28-03-2024-no-mysql

O côdigo para que o mysql apenas pegue as pessoas com a idade de 16:
SELECT * FROM `alunos` WHERE idade='16';

O côdigo para ele apenas pegar pessoas com o sobrenome de Santos no mysql, no caso no meu não irá aparecer por ser Dos Santos:
SELECT * FROM `alunos` WHERE sobrenome='dos Santos';

Caso você queira que qualquer nome que começe com Santos mas por exemplo que tenha dos Santos teremos que utilizar o côdigo:
SELECT * FROM 'alunos' WHERE sobrenome LIKE '%Santos%';

Graças ao porcentagem ele servirá para indicar que qualquer coisa antes de santos e depois de santos ira contar para que ele possa identificar, e o LIKE para que possa encontrar qualquer sobrenome que contenha Santos.
