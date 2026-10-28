# Atividades Engenharia de Software

## Atividade 1 - Comentário no trecho: O que exatamente queremos dizer com Engenharia de Software?

- Programar é entregar a solução imediata funcionando, já a engenharia de software é garantir que essa solução continue de pé, segura e escalável no longo prazo, com método e rigor. Toda engenharia constrói coisas usando blocos, mas o tipo de bloco muda.
- Um engenheiro civil constrói uma ponte usando blocos de concreto e ferro. Se ele errar a conta, a ponte cai.
- Um engenheiro mecânico constrói o motor de um carro usando blocos de metal e engrenagens. Se ele errar, a peça quebra e o carro para na rua.
- O engenheiro de software constrói um castelo gigante, só que usando blocos invisíveis. O bloco dele é a lógica, o código. Ninguém consegue encostar a mão no software, mas se você errar a conta, o aplicativo do banco trava, a venda não entra e o sistema da loja para.
- A diferença é que, se o engenheiro civil quiser mudar a ponte de lugar depois de pronta, ele tem que derrubar tudo e gastar uma fortuna. Já o bloco invisível do software permite que a gente mexa, troque as peças e aumente o tamanho do castelo com a estrutura ainda funcionando desde que o castelo tenha sido bem construído lá no começo para não desmoronar tudo de uma vez.

## Atividade 2 - Comentário no trecho: Programação ao Longo do Tempo

- Para quem tá começando na área, é super comum focar 100% em fazer o programa rodar e achar que o trabalho acabou ali. Mas a sacada de que programar é "integrar o código ao longo do tempo" mostra que o ciclo de vida real de um software começa justamente depois que ele vai para o ar, lidando com atualizações, correções e mudanças de requisitos.

## Atividade 3 - Trade-offs:

Toda decisão na programação cobra um preço. Se você quer entregar algo rápido para testar no mercado agora, geralmente abre mão da arquitetura perfeita e vai acumulando um débito técnico que vai cobrar juros lá na frente. Por outro lado, se gasta tempo demais tentando deixar tudo impecável e blindado para o futuro, o projeto pode nunca ver a luz do dia. O grande desafio dessa "engenharia ao longo do tempo" parece ser exatamente encontrar o equilíbrio certo entre a velocidade de entrega de hoje e a sustentabilidade do código para amanhã.

**Exemplos:**

- Escrever código rápido (Gambiarra Funcional vs. Arquitetura Limpa):
  - O ganho: Você entrega a funcionalidade no mesmo dia e resolve a urgência do cliente ou da sprint.
  - O preço: O código fica acoplado e confuso. Daqui a três meses, qualquer alteração simples vai exigir refatoração pesada, gastando o dobro do tempo que você economizou agora.

- Escolha de Bibliotecas e Frameworks (Prontas vs. Customizadas):
  - O ganho: Usar uma biblioteca de terceiros gigante poupa semanas de desenvolvimento inicial.
  - O preço: Você fica preso às atualizações, bugs e vulnerabilidades de outra pessoa. Se o projeto original for abandonado, migrar depois vai dar uma dor de cabeça imensa.

- Testes Automatizados (Sem Testes vs. Cobertura Alta):
  - O ganho: Pular os testes acelera muito a fase inicial de codificação.
  - O preço: Qualquer mudança futura vira um jogo de roleta russa, porque você só descobre que quebrou algo quando o sistema já está na mão dos usuários.

## Atividade 4 - Contribuições na API:

A minha principal contribuição foi na parte inicial e estrutural, ajudando a montar a base do sistema. Algo crucial considerando que poucos integrantes tinham familiaridade com programação no começo. Além de estruturar o código e o ambiente, fiquei responsável pela documentação do projeto. Essa organização inicial e o cuidado com a documentação foram fundamentais para que o grupo conseguisse entender o sistema, acompanhar o ritmo do desenvolvimento e integrar as peças ao longo da sprint, garantindo que o código se mantivesse sustentável e claro para todos.

## Atividade 5 - Habilidades desenvolvidas na API:
**Python:** Evoluir um pouco meu conhecimento em Python que é básico ainda.
**Integração de APIs e Bots:** Desenvolvimento e configuração de bot para o Telegram utilizando a biblioteca pyTelegramBotAPI para automação de interações e processamento de mensagens.
**Uso de LLMs Locais e DSPy:** Implementação de inteligência artificial com modelos locais via Ollama, estruturando assinaturas, fluxos e lógica de rotas utilizando o DSPy.
**Manipulação e Análise de Dados:** Processamento e cruzamento de bases de dados (como arquivos CSV de vendas, estoque e descarte) utilizando pandas para extração de métricas e suporte à tomada de decisão.
**Arquitetura Inicial e Organização de Código:** Concepção da estrutura de pastas, definição da base técnica e configuração do ambiente de desenvolvimento do projeto.
**Documentação:** Elaboração da documentação do sistema e suporte aos colegas com menos familiaridade em programação para alinhar o ritmo do grupo.
