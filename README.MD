#1 Estrutura de dados e SQL
1-) SELECT a.nome FROM ALUNO a JOIN ALUNO_TURMA at ON a.id=at.aluno_id JOIN TURMA t ON at.turma_id=t.id JOIN PROFESSOR p ON t.PROFESSOR_id=p.id WHERE p.nome LIKE 'JOAO PEDRO';
2-) SELECT t.dia_da_semana FROM TURMA t JOIN DISCIPLINA d ON t.DISCIPLINA_id=d.id WHERE d.nome LIKE 'MATEMATICA';
3-) SELECT a.Nome FROM ALUNO a JOIN ALUNO_TURMA at ON a.id=at.aluno_id JOIN TURMA t ON at.turma_id=t.id JOIN DISCIPLINA d ON t.DISCIPLINA_id=d.id WHERE d.nome LIKE 'MATEMATICA' AND d.nome LIKE 'FISICA';
4-)
5-)