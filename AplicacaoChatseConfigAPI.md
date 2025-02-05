# Resumo módulo Aplicação de Chats e Configuração API

Nesta aula vimos os modos suportados da API do Azure OpenAI como:

- Chat
- Completar: Questões e Respostas
- Imagens
- Áudio

Obervamos um fragmento de código em Python para instanciar a API (AzureOpenAI), para cada tipo suportado.

Foi apresentado um código exemplo em Python, do uso da API, onde é possível observar a forma de efetuar requests e a composição da chamada
como authorization, nome do recurso, nome do deploy e versão.

Também foi possivel acompanhar como implementar o BODY do request, com o prompt e as variáveis mais comums como:

- Model ID
- Temperatura
- Máximo de Tokens
- Top-P
- Presence/Frequency penalties
- Personas

O interessante também foi verificar a tela de visualização de métricas das solicitações para acompanhar o uso das chamadas de APIs e modelos.

# Semantic Kernel

Vimos a introdução do que é o Semantic Kernel, definido como um Middleware de IA e como ele agrega mais funcionalidades.

Então foi definido para o que serve:

- Funcionalidades extras
- Colocar funções de processo automático
- Agentes de IA

Observamos a arquitetura básica do Semantic Kernel:

- Kernel
- Skills
- Functions
- Memory

Sendo o kernel o principal componente da arquitetura onde ocorre:

- Select IA Service
- Render Prompt
- Invoke IA Service
- Parse LLM Response
- Create Function Result
- Event Notifications

Functions temos:

- Suas classes implementadas
- Open API Spec
- Prompt Templates
- Prompt Template Files
- Text Search

Memory:

- Vector Stores
- Usando uma API para buscar dados rapidamente

Filtros:

Person makes a request -> Filter Checks -> Request Validated | Request denied

Após esta introdução, foi apresentado uma implementação, utilizando código Python em um NoteBook,
que ilustrou a aplicação prática do SK. 
  



