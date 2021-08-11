"# PRO-FUC-aula-03-java"  
Por meio de eventos, programamos as ações dentro de uma interface gráfica. Em outras
palavras, um evento indica a mudança do estado de um objeto.
A interação entre a Interface e o Usuário se dá por meio de eventos. Podemos citar alguns
exemplos muito comuns como: clicar em um botão, como é o caso desse projeto.
Um evento tem três componentes principais:
» Eventos (Events): um evento é uma mudança de estado de um objeto.
» Eventos Fonte (Events Source): fonte do evento é um objeto que gera o evento.
» Ouvintes (Listners): um ouvinte é um objeto que ouve o evento. Um ouvinte avisa
quando ocorre um evento.

# Ciclo de um Evento
Uma fonte gera um evento e o envia para um ou mais Listners registrados para a fonte.
Uma vez que evento é recebido pelo Listner, este processa o evento e, em seguida, envia uma
resposta à fonte.
