# mentor-prompt

Um prompt que transforma o Claude num mentor técnico de verdade — que puxa, cobra e desafia — em vez de um assistente que entrega tudo mastigado.

Em vez de dar a resposta pronta, ele te faz pensar, justificar cada decisão e errar antes de pesquisar. Serve pra estudar qualquer stack.

## Como funciona

A ideia é simples: você trabalha normalmente no seu projeto, mas o Claude passa a te tratar como aluno. Ele não resolve por você — guia com perguntas, aponta quando você foge do problema e reconhece quando você acerta por raciocínio próprio.

O fluxo dentro do seu `CLAUDE.md` fica assim:

- **Em cima:** o plano / contexto do seu projeto (o que você já tem).
- **No fim:** as regras de mentoria (o conteúdo do `INSTRUCTION.md`).

Assim as instruções de mentoria são a última coisa que o Claude lê, e ficam mais fortes.

## Como configurar

1. Abra (ou crie) o arquivo `CLAUDE.md` na raiz do seu projeto.
2. Copie o conteúdo do [`INSTRUCTION.md`](./INSTRUCTION.md) e **cole no fim** do seu `CLAUDE.md`.
3. **Troque o item 4** pela SUA dificuldade e pela SUA zona de conforto:

   ```
   4. Não deixe ele fugir pra zona de conforto. Se ele tem gap em
      [SUA DIFICULDADE] mas quer pular pra [SUA ZONA DE CONFORTO]
      porque é mais confortável, bloqueie...
   ```

   Exemplos:
   - gap em **testes** mas foge pra **feature nova**
   - gap em **CSS/layout** mas foge pra **lógica de backend**
   - gap em **SQL** mas foge pra **código da aplicação**

4. Salve. Pronto — na próxima conversa o Claude já age como mentor.

> Dica: o item 4 é o único que precisa ser pessoal. Os outros 9 valem pra qualquer um.

## A ideia da mentoria

Aprender de verdade dói um pouco. Quando o assistente entrega a resposta pronta, você copia e não fixa nada. Esse prompt inverte isso: ele te obriga a pensar no design antes de codar, a justificar cada escolha e a ficar no desconforto até aprender — que é onde o aprendizado realmente acontece.
