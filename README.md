# Explorando Práticas de Teste

Neste exercício, vamos explorar práticas de teste em sistemas reais utilizando a ferramenta [TestMiner](https://andrehora.github.io/testminer).

O TestMiner permite visualizar e analisar testes de software em repositórios do GitHub, fornecendo dados sobre como os projetos organizam seus testes, como eles evoluem entre versões e quais bibliotecas de teste são utilizadas.
Explore a ferramenta antes de começar para se familiarizar com seu funcionamento.

Mais detalhes no GitHub da ferramenta: https://github.com/andrehora/testminer.

---

## Passo 1: Selecionar DOIS repositórios

Escolha dois repositórios reais que possuam testes de software.
Abaixo estão alguns links para ajudá-lo a encontrar projetos interessantes:

- Python: https://github.com/topics/python?l=python
- JavaScript: https://github.com/topics/javascript?l=javascript
- TypeScript: https://github.com/topics/typescript?l=typescript
- Java: https://github.com/topics/java?l=java

- Tópicos: [ai](https://andrehora.github.io/testminer/#topic:ai), [llm](https://andrehora.github.io/testminer/#topic:llm), [api](https://andrehora.github.io/testminer/#topic:api), [nodejs](https://andrehora.github.io/testminer/#topic:nodejs), [android](https://andrehora.github.io/testminer/#topic:android)

- Por organização: [Google](https://andrehora.github.io/testminer/#google), [Microsoft](https://andrehora.github.io/testminer/#microsoft), [Apple](https://andrehora.github.io/testminer/#apple), [Facebook](https://andrehora.github.io/testminer/#facebook), [Netflix](https://andrehora.github.io/testminer/#netflix), 
[GitHub](https://andrehora.github.io/testminer/#github), [Apache](https://andrehora.github.io/testminer/#apache), [HuggingFace](https://andrehora.github.io/testminer/#huggingface)

## Passo 2: Explorar os repositórios selecionados

Busque os repositórios escolhidos no [TestMiner](https://andrehora.github.io/testminer) e analise os dados de teste gerados pela ferramenta.

## Passo 3: Explicar as prática de teste

Para cada repositório, escolha uma prática ou dado de teste relevante e explique com suas próprias palavras.

---

## Instruções de entrega

1. Faça um `fork` deste repositório (saiba mais sobre forks [aqui](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)).
2. Responda às questões abaixo diretamente neste arquivo `README.md` do seu fork. Pode adicionar imagens para enriquecer sua explicação.
3. No Moodle, submeta apenas a URL do seu fork.

---

## Respostas

### Repositório 1 

Repositório: [https://github.com/freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)

URL TestMiner: [https://andrehora.github.io/testminer/#freeCodeCamp/freeCodeCamp](https://andrehora.github.io/testminer/#freeCodeCamp/freeCodeCamp)

Explicação: O projeto freeCodeCamp apresenta 159 testes E2E, que verificam se as funcionalidades do sistema funcionam corretamente do início ao fim, simulando as ações de um usuário real. Isso ajuda a identificar problemas na interação entre diferentes partes da aplicação e a garantir que os principais fluxos funcionem como esperado.

<img width="927" height="462" alt="image" src="https://github.com/user-attachments/assets/407f5fee-76ec-47b7-8528-2f1c72175ad8" />


### Repositório 2

Repositório: [https://github.com/pallets/flask/tree/main](https://github.com/pallets/flask/tree/main)

URL TestMiner: [https://andrehora.github.io/testminer/#pallets/flask](https://andrehora.github.io/testminer/#pallets/flask)

Explicação: É uma boa prática que testes sempre sejam escritos e realizados no sistema o qual está sendo desenvolvido. Entretanto, com base nas estatísticas de teste do flask, desde a versão 2.0.2 até a 3.1.3, a quantidade de testes permaneceu a mesma, sem nenhuma evolução. Para garantir uma melhor qualidade do sistema, é necessário implementar novos testes conforme esse sistema cresce, de forma que ambos cresçam simultaneamente.

<img width="930" height="513" alt="image" src="https://github.com/user-attachments/assets/9787eb8f-e26b-49ab-9105-b65a60c93054" />

