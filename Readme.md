### Relatório - Mini Projeto (Módulo 01_Python) 🤺
📘 Data-Driven Insights 

🧑‍💻 Projeto
Projeto prático de exploração e visualização de dados com Python com Google Colab, utilizando um data set em .csv

🎯 Objetivo
Práticar análise exploratoria, transformação e visualização de dados utilizando Python e suas bibliotecas (pandas, numpy e matplotlib) e suas funções com proposito de gerar insights descritivos.

✅ Ferramentas: Google Colab e Github

📊 Bases de dados utilizada

* Fonte: [https://colab.research.google.com/drive/13gFZfM78CaWpXsDmkS0Pm8m1hb6c9pX0#scrollTo=knRO-mC8I-uo](https://archive.ics.uci.edu/dataset/320/student+performance )

🧐Roteiro Guiado:

1. Instalando as Bibliotecas necessárias para uso na análise.
2. Importando as bibliotecas para o projeto
3. Criando um dataframe (df) no Google Colab.
4. Explorando o data set (base).
   * Com o uso do comando head(), identificamos que a base está no idioma inglês, com isso optei por explorar dados básicos como: failures (reprovações), sex (sexo), absences (ausências), age (idade), G1, G2 (notas do primeiro e segundo período) e Pstatus (Status civil dos pais), a escolha dos campos foi para facilitar a prática da exploração de dados e realização da atividade, deixando o menos complexa possível.
     
   <img width="625" height="232" alt="image" src="https://github.com/user-attachments/assets/6df5575a-4a98-498b-81c3-0f98a688a61d" />

    * A estrutura do data set escolhido contem um total de 395 linhas por 33 colunas.
    * A coluna G1 e G2 do tipo int64 considera notas de 0 a 20.

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

   * alé disso as reprovações anteriores não tem influência com quem não frequentou creche, o percentual maior aponta para quem frequentou, ou seja, foi incluido antes, mesmo assim o registro aponta o maior indice de reprovações para este grupo.
     <img width="592" height="456" alt="image" src="https://github.com/user-attachments/assets/5773d644-17b0-488f-b892-350312a4fba5" />

   * Por fiim podemos reafimar as informções do primeiro gráfico, onde nota-se que as auxencias inicia na pré adolescencia e vai até o inicio da adolescencia, onde identifica-se uma redução o que pode indicar maior responsabilidade, fase onde o jovem está de olho em seu futuro o que vai fazer, faculdade a cursar entre outros fatores.
  
  <img width="452" height="347" alt="image" src="https://github.com/user-attachments/assets/40a67b7b-c560-4004-abee-7e4636306eb2" />

* #Conclusão:
* ![MuaKissGIF (2)](https://github.com/user-attachments/assets/c4e9755d-84ee-4ac0-bba1-d7bda1ece48a)

Com esta atividade, pude praticar e entender conceitos fundamentais, realizei a atividade umas 5 vezes até conseguir compreender que antes precisava de fato ler, enteder, enteder e entender a base bem como o que ela tras de informações. O resultado aqui não é o melhor, poderia ainda trazer muito mais insights com esta base e motivos das reprovações. Contudo, de uma forma resumida, pude entender que as repovações anteriores não tem forte influencia sobre pais casados e separado, aponta muito mais para uma fase na idade dos 15 aos 17 anos e para o perfil feminino, a base vai além dos dados analisados, a atividade encerro aqui, porém meu trabalho e olhar a fundo e melhorar este projeto ficará como liçãod e casa para que possa melhorar e praticar utilizando puthon.

Obrigado!!!

   
