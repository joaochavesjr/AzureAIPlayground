# Desafio DIO - Azure OpenAI Playground

Este é um resumo das interações observadas utilizando o Azure OpenAI Playground.

Primeiramente o Playground permite exercitar e testar os prompts para preparar o modelo.

E antes de partir para a criação destes prompts, para entender melhor estes macanismos, aprendemos sobre o conceito de tokens.
Uma ferramenta interessante (e free), demonstrada na aula, foi o Tokenizer da OpenAI, onde é possível entender como é feita o processamento de texto utilizando tokens, permitindo visualizar como os diferentes modelos tratam ou dividem os conjuntos de caracteres.

Também foi possível obervar um fragmento de código python, demonstrando o uso da biblioteca tiktoken, para efetuar tokenização de texto, que permite garantir um processamento de texto eficiente dentro dos limites (tamanho e custo).

E agora diretamente relacionado com o resultado dos prompts, entendemos a relação Temperatura X Top-P, que permite melhorar a "criatividade" e a variação de respostas diferentes.

No caso a temperatura é a configuração de pegar palavras enquanto há a criação de texto, controlando o quão randômico podem ser as ligações.

Temperatura menor (0): Respostas muito previsíveis, determinísticas;

Temperatura maior (1): Respostas muito improváveis, sem sentido (Brainstorm).


Top-P: Quais palavras podem ser usadas na possível escolha.

Top-P 0.1: Considera o primeiro eixo de palavras prováveis, até dar 10% das possibilidades;

Top-P 0.9: Considera muitas palavras até dar o eixo de 90% das possibilidades;

**NOTA**: Use variações de Top-P ou temperatura, raramente ambos.

Não existe valores definidos, é necessário ajustar e testar o modelo com os prompts variando os valores de temperatura e Top-P para achar o melhor resultado, podemos considerar as melhores práticas:

- Começar com valores padrões;
- Ajustar um parâmetro por vez;
- Observar e documentar os resultados;
- Alterar baseado em feedback.

# Dall-E

E ainda, com este modelo multimodal é possível gerar imagens utilizando o Dall-E.

As melhores práticas para criar imagens utilizando estes recursos são:

- Clareza;
- Especificidade;
- Contexto;
- Estrutura.

  





