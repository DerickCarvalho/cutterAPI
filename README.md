# cutterAPI

API para gerar código Cutter baseado na revisão Cutter-Sanborn.

# Como usar:

1 - Copie o seguinte código: <script src="https://cdn.jsdelivr.net/gh/DerickCarvalho/cutterAPI/api.js"></script>
2 - Cole o código copiado dentro do seu html (de preferência em cima de qualquer outra tag script, e no final da tag body);
3 - A API já está linkada e funcional, para usa-la basta usar o seguinte código:

# const buscarCodigo = buscarMaisSimilar(data, lastName).codigo;

<b>O.B.S.: SUBSTITUA A VARIÁVEL 'lastName' PELA VARIÁVEL DA SUA APLICAÇÃO</b>

# Concatenando primeira letra do trabalho no final do código Cutter

Basta pegar a string do nome do projeto, e buscar a primeira letra da string do mesmo, e após isso, 
colocar em letras minúsculas, como no exemplo:

<b>let primeiraLetraTrabalho = nomeTrabalho[0];</b>
<b>primeiraLetraTrabalho = primeiraLetraTrabalho.toLowerCase();</b>
