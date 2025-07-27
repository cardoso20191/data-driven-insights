### Relatório Mini Projeto**
📘 Mini Projeto: Data-Driven Insights (Módulo 01_Python)

🧑‍💻 Projeto
Projeto prático de exploração e visualização de dados com Python no Google Colab, utilizando um data set extraído do site [https://www.kaggle.com/datasets/kyanyoga/sample-sales-data?resource=download](https://archive.ics.uci.edu/dataset/320/student+performance - arquivo (student-mat) no formato .csv.

🎯 Objetivo
Práticando Análise exploratoria: transformação e visualização de dados utilizando Python e suas bibliotecas (pandas, numpy e matplotlib), gerando insights descritivos a partir da análise realizada.

✅ Roteiro:
Ferramentas: Google Colab e Github

📊 Bases de dados sugeridas

https://colab.research.google.com/drive/13gFZfM78CaWpXsDmkS0Pm8m1hb6c9pX0#scrollTo=knRO-mC8I-uo

🧐Roteiro Guiado para análise gerada:

1. Instalando as Bibliotecas necessárias para uso na análise.
2. Importando as bibliotecas bases para o projeto
3. Carregamento da Base a partir do arquivo disponibilizado no ambiente do Colab
4. Conhecendo o data set (base) da análise.
   * Com o uso do comando head(), identificamos que a base se tratava de dados de alunos, porém contiam dados mais pessoais, como relacionamento, trabalho, acesso a internet entre outros.
   <img width="625" height="232" alt="image" src="https://github.com/user-attachments/assets/6df5575a-4a98-498b-81c3-0f98a688a61d" />
   * A estrutura da base contem um total de 395 linhas por 35 colunas.
   * Identificamos também que dados como nota, foi considerado sempre como do tipo int64, sendo que um aluno não teria notas com meio ponto exemplo: 5.5.

   4.1 Listas, Dicionarios e Tuplas
     * Criado uma lista com um for para visualizar as 10 primeiras linhas para buscar as reprovações deste grupo com isso identificamos apenas 3, podendo ser considerado baixo.
     * A partir de uma tupla, buscamos o indice 20 para saber o status do aluno, sexp e suas ausencias.
  
  4.2 Estruturas Condicionais e Laços
    * Utilizado o if/elif/else a partir do indice 2 e verificar o status de aprovação por meio da coluna "absences (ausências).
    * Utilizado For identificamos que foram registrados um total de ausencias de 2255 total.
    * Utilizado o while identificamos que o primeiro valor encontrado a parir de 6 foi 10 (ausencias)

  4.3 Operadores Aritméticos e Manipulação de Dados
    * Verificamos que a diferenã entre G1 e G3 fica abaixo de 0. (Não consefuir compreender muito bem as colunas em questão, mais interpretei como bimestre sendo 3.
    * Um dado interessante que acontece na prática é a partir de aplicações de trabalhos escolares com desconto nas ausencias seria possível reverte a situação de de alunos com nível elevado de faltas (absences).

5. NumPy e Arrays Numéricos
  * Utilizando a biblioteca também é possível chegar ao total de faltas geral que foi 2255.
  * Registrado uma média de 5.7 e ausencias, o que reforça a aplicação de descontos em ausencias por realização de trabalhos.

6. Acesso e Manipulação de Dados com Pandas
   * Nenhum insight, apenas filtrados informações a partir do uso da função iloc utilizando filtros como condições.
  
7. Visualização de Dados
   * As ausencias ocorrem principalmente na fase da pré adolexcencia dos 15 até a juventude 17, onde identificamos uma redução.
    <img width="472" height="360" alt="image" src="https://github.com/user-attachments/assets/f303f19e-17d0-4384-81bb-3bd76577840b" />

    * Podemos notar também que o publico que registra o maior número de ausências é o feminino.
      <img width="462" height="356" alt="image" src="https://github.com/user-attachments/assets/57567764-3a55-45f9-8524-500e7e3d2e5f" />

   * Por fiim podemos reafimar as informções do primeiro gráfico, onde nota-se que as auxencias inicia na pré adolescencia e vai até o inicio da adolescencia, onde identifica-se uma redução o que pode indicar maior responsabilidade, fase onde o jovem está de olho em seu futuro o que vai fazer, faculdade a cursar entre outros fatores.
  
  <img width="452" height="347" alt="image" src="https://github.com/user-attachments/assets/40a67b7b-c560-4004-abee-7e4636306eb2" />

* #Conclusão:
* ![MuaKissGIF (2)](https://github.com/user-attachments/assets/c4e9755d-84ee-4ac0-bba1-d7bda1ece48a)


Esse é minha primeira análise exploratória, confesso que me perdir não no uso das funções mais como aplicar efetivamente, porém me deu vários insghts em uma situação de uso no excel que possuo vasto dominio e isso me levou a pensar como algo que parece tão simples pode ficar complexo. Foi um desafio que pareceu fácil, mais gerar insights nem sempre é algo simples, na verdade é uma responsabilidade grande. Nesta jornada é apenas o começo e estou buscando cada vez mais melhor mais e mais, trazer minha experiência e conhecimento em outras ferramentas para uso com o Python e as proximas ferramentas que virá durante o programa.

Obrigado!!!

   
