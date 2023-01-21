<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/la-catalog/database/raw/main/res/white.png">
    <img src="https://github.com/la-catalog/database/raw/main/res/black.png">
  </picture>
</div>

## context
Precisavamos documentar as estruturas dos bancos de dados porém na organização nós temos a regra de deixar a documentação próxima do assunto a qual ela se trata... Infelizmente está regra é inviável de se seguir quando falamos de bancos que podem ser utilizado por N repositórios.  

- Duplicar documentação em todos repositórios que utilizam aquele banco/tabela/collection/index?
  - ❌ Inviável atualizar N repositórios manualmente para qualquer mudança nas estruturas
  - ❌ Desnecessário ter código que atualize N repositórios para qualquer mudança nas estruturas
- Escolher um repositório principal para conter a documentação de determinado banco/tabela/collection/index?
  - ❌ Os membros da organização teriam que descobrir em qual repositório está a documentação e depois lembrar
- Centralizar documentações de bancos em um repositório?
  - ✔️ Após dar pin do repositório na organização, se torna um repositório de fácil acesso para documentação
  - ✔️ Fácil de referênciar este repositório em outros README.md

## guideline

- Não documente detalhes
  - Normalmente os campos da tabela/collection/index são baseados em estruturas vindas de códigos e estes códigos possuem documentações por sua parte
  - Muito campos podem mudar, o que pode tornar trabalhoso atualizar documentação do código + documentação do banco de dados
