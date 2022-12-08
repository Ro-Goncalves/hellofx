# JavaJX

Bem, nem só de navegadores vive o homem, e não é só de soluções Web que vivem às empresas. Estudar um pouco sobre aplicações Desktop pode ser útil em vários cenários hoje em dia.

Eu estou querendo aprender para automatizar alguns trabalhos que realizo no meu dia a dia do trabalho, e deixar alguns outros em mais auto-nível. Por exemplo, sempre tenho que fazer a mesma correção na base de dados do BI, se criar uma aplicação Desk posso abstrair toda a parte técnica e fazer mais rápido e livre de erros, e o mais importante, sem custo extra à empresa, lindo.

Um outro motivo e colocar tudo aquilo que aprendi na empresa em um único lugar, dando a possibilidade de qualquer outra pessoa fazer o meu trabalho, ou parte dele. Enfim, irei criar essa aplicação para **n** coisas.

Escolhi o JavaFX por ser Java, trabalho com ele, mas é algo bem superficial, e para evoluir melhor na linguagem decidir criar essa aplicação com em um *framework* Java.

Meu objetivo com esse repositório guardar aquilo que estou aprendendo para servir de referência no futuro.

Que Deus ilumine a minha Intelecto para que eu possa aprender essa nova tecnologia e aplicá-la da melhor forma possível, que todo o conhecimento que eu adquira seja para buscar e contemplar a Verdade.

## Scene Graph

É o ponto inicial para a contrução de uma aplicação JavaFX. Pode ser definido como uma coleção de *nodes* que representam os elementos visuais da interface.

Cada *node* possui um **id, estilo e volume**, além disso pode ter nunhum ou um pai e vários filhos.

Suas classe são encontradas em `javafx.scene`.

## Graphics Engine

O JavaFX provê um software para renderizar gráficos 2D e 3D quando o sistema em que a aplicação está rodando não possui hardware gráfico. Existem dois *pipelines* para aceleradores gráficos no JavaFX.

### Prism

Dependendo da plataforma ele usa uma maneira para renderizar os gráficos.

* Directx9 no Windows XP ou Vista
* DirectX 11 no Windows 7
* OpenGL no Mac e Linux
* Java 2D quando não da para fazer aceleração por hardware

### Quantum Tool Kit

Junta o Prism com Glass Windowing e disponibiliza às camadas superiores.

## Glass Windowing Tool Kit
