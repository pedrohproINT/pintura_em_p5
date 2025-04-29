# Calçadão de Copacabana de Burle Marx em P5*js

Escolhi talvez a obra mais famosa de Burle Marx. O calçadão de Copacabana é um dos marcos visuais mais icônicos do Rio de Janeiro. Desenvolvido pelo paisagista Roberto Burle Marx, o desenho em ondas pretas e brancas foi inspirado nos padrões de calçadas portuguesas do período colonial, especialmente os de Lisboa. Reinterpretando esse traço histórico com sua visão modernista, Burle Marx aplicou seu domínio sobre o uso de formas orgânicas e integração com o ambiente natural para criar uma calçada que se tornou símbolo cultural da cidade mundialmente.

Para imitar a obra foi preciso criar um nested loop onde o loop externo corresponde às colunas e o interno às linhas. Cada coluna é uma fila de diversos círculos preto/branco intercalados sobrepostos verticalmente começando de cima. Todavia, a coluna seguinte deve começar de baixo e assim por diante, intercalando cores e o local em que cada coluna começa.

A animação foi pensada considerando que o calçadão, apesar de fixo no mundo real, carrega um movimento visual contínuo, como o das ondas do mar que ele representa. Para isso, utilizei uma função senoide aplicada ao deslocamento horizontal de cada coluna, com fase crescente, o que produz o efeito ondulatório dinâmico ao longo do tempo, reforçando a sensação rítmica e fluida da obra original.

Trabalho para a disciplina de UX da professora Bruna Mayer.

![Alt text](images/calcadao.jpg)