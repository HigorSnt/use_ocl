# Atividade UseOCL

Atividade realizada para a disciplina de **Análise de Sistemas**, no período de 2019.1, utilizando OCL, que é  uma linguagem para especificação de restrições em objetos.

## Atividade

### Diagrama 1

Considerando o diagrama acima, implemente-o usando USE, como instruído nos exemplos do README. Em seguida, especifique as questões:

![Chat](img/diagrama1.png)

1. O Horario deve ter segundos e minutos entre 0 e 59, e horas entre 0 e 23 (inclusos).

2. A data deve ter dias entre 1 e 31, meses entre 1 e 12, e ano sendo o atual ou algum ano anterior, mas não anterior à 2000 (inclusos).

3. Para uma dada conversa, os membros da conversa são diferentes entre si.

4. Para um dado grupo, nenhum membro está repetido.

5. Nenhuma mensagem deve ter seu texto vazio.

6. Cada grupo deve ter pelo menos 1 administrador, e este administrador deve ser um de seus membros.

7. Um grupo não pode ter mais administradores que membros.

8. Especifique que a função `listarUsuarios()` de uma Conversa retorna os nomes dos usuários.

Já que não é possível utilizar o `def`, modifique o diagrama para incluir a assinatura de função `mensagensEnviadas`, e especifique que deve retornar todas as mensagens enviadas pelo usuário.

### Diagrama 2

Considerando o diagrama acima, implemente-o usando USE, como instruído nos exemplos do README. Em seguida, especifique as questões:

![Musica](img/diagrama2.png)

1. Um artista não pode ter dois albums com nomes iguais.

2. Dois discos de um mesmo album não podem ter números iguais

3. Um EP deve conter de três a seis músicas.

4. Um Single deve conter de uma a três músicas.

5. Um album deve conter ao menos 8 musicas.

6. A duração de uma música não pode ser negativo ou zero.

7. A duração de uma Playlist/EP/Disco/Single é igual à soma do tempo de cada uma de suas músicas.

8. A duração de um Album é a soma do tempo de cada um de seus discos.

9. O total de Visualizações de um Album/Single/EP é o total de visualizações de suas músicas.

10. Uma Playlist Colaborativa não pode ser pública, e vice-versa.

11. Especifique que após ouvir uma música, a quantidade de suas visualizações aumentou em 1.

**LINK PARA O REPOSITÓRIO ORIGINAL:**  
[JÚLIO GUEDES](https://github.com/juliobguedes/use_instrucoes/blob/master/2019_1/exercicio.md)