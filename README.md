# EVENT TRACKER 

O Event Tracker é um calendário que exibe eventos que podem ser adicionados e removidos. 
Você pode interagir com essa aplicação e indicar que um evento foi completado, você pode deletar um evento do calendário, você pode mover um evento no drag'n'drop e mudar o horário e o dia dele.

No projeto inicial o gerenciamento de estado está sendo feito direto no “app.tsx”.

Essa configuração traz diversos problemas que vamos trabalhar e ver qual é a alternativa que temos em vez de fazer esse gerenciamento de estado em um arquivo grande: vamos usar o Recoil para atingir um bom resultado!

Ao final vamos ter uma aplicação refatorada, com alta coesão, baixo acoplamento, pronta para crescer de forma escalável. 

## Objetivos do projeto:

- Projetar uma boa solução de gestão de estado com Recoil
- Entender todas as vantagens do Recoil
- Extrair a comunicação com o recoil em hooks
- Implementar os principais hooks do Recoil
- Comparar diferentes soluções de mercado para gestão de estado

## Para rodar o projeto

Execute json-server --watch db.json -p 8080 no terminal.