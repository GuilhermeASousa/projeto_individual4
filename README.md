# projeto_individual4

⇨ Existem outras entidades além dessas três?

    Além das 3 existem: Professores e Matrículas.

⇨ Quais são os principais campos e tipos?

    Matrículas: Matrícula (int) e Data da Matrícula (date);
    Cursos: ID (int), Nome (varchar), Valor (float), Requisitos (varchar) e Carga Horária (int);
    Turams: Número (int), Turno (char), Data Fim (date) e Data Início (date);
    Professores: CPF (char), Formação (varchar), Email (varchar), Data de Nascimento (date) e Nome (varchar);
    Alunos: CPF (char), Data de Nascimento (date), Email (varchar), Nome (varchar) e Telefone (char).

⇨ Como essas entidades estão relacionadas?

    Cursos - Turmas -> (1, n)
    Professores - Turmas -> (n, n)
    Matrículas - Turmas -> (1, n)
    Alunos - Turmas -> (n, n)
    Alunos - Matrículas -> (1 n)
