# VISÃO DO PRODUTO E PROJETO

**MinhaTirinha Digital** *Projeto acadêmico da disciplina Arquitetura e Desenho de Software* *Grupo 08 — 2026.1*

---

## 1. CENÁRIO ATUAL DO CLIENTE E DO NEGÓCIO

### 1.1 Introdução ao negócio e contexto
Em meio ao cenário mundial atual influenciado pela revolução da era digital podemos enxergar que o uso de dispositivos eletrônicos e o consumo de conteúdos na internet estão bastante presentes em nossas vidas, principalmente, mas não exclusivamente, no entretenimento, onde podemos encontrar uma população que abdicou e abdica constantemente o entretenimento antes praticado através de hábitos que incentivam positivamente a cognição, como os hábitos de leitura e pintura, para se entreter com as várias opções que temos hoje em dia no meio digital, muitas das quais liberam altas cargas de dopamina mas que pouco influenciam de uma forma saudável cognitivamente.

O abandono ao entretenimento constituído por hábitos positivos para a aderência ao entretenimento de hábitos negativos conhecido como “brain rot” pode afetar diretamente a saúde mental da população acarretando em sintomas maléficos como por exemplo a dificuldade de manter a concentração devido à exposição de várias fontes simultâneas de informação, a dificuldade de formação de pensamento crítico devido superficialidade dos conteúdos consumidos, maior impulsividade e busca contínua por estímulos rápidos contribuindo para casos de ansiedade e estresse, sendo que tais sintomas podem ser contornados ao evitar o consumo de entretenimento que impacta negativamente a saúde mental.

Como alternativa ao entretenimento “brain rot” podemos ressaltar o hábito da leitura linear estruturada que estimula:

* Pensamento crítico;
* Entendimento contínuo e profundo;
* Melhoria da concentração;
* Habilidade de reflexão;
* Capacidade analítica;

E também o hábito prático de pintura que estimula:

* Alívio do estresse e tensão;
* Aumento da criatividade;
* Melhoria da concentração;
* Aumento da felicidade;
* Diminuição da ansiedade;

Sendo que os benefícios citados para ambos os hábitos são bastante procurados por muitas pessoas nos dias atuais que querem cuidar de sua saúde mental e qualidade de vida.

### 1.2 Identificação da oportunidade ou problema
Devido a falta de prática de hábitos cognitivos saudáveis nos dias atuais pela população, identificamos uma oportunidade de estimular hábitos cognitivos saudáveis a partir da leitura e pintura como meio de entretenimento saudável na era digital através do uso de dispositivos eletrônicos e o uso da internet, sendo alternativa ao consumo de entretenimento “brain rot”.

A partir do Diagrama de Ishikawa utilizando os 6M’s adaptados com auxílio de IA ao contexto mencionado:

* **Método (lógicas, hábitos diários e fluxos de consumo):** Refere-se à forma como as pessoas organizam seu tempo e aos rituais (ou falta deles) para consumir entretenimento;
* **Material (informações, conteúdos e estímulos digitais):** Refere-se à matéria-prima informacional e ao tipo de conteúdo que disputa a atenção do usuário hoje;
* **Mão de Obra (capacidade cognitiva, atores e usuários):** Refere-se às condições psicológicas e biológicas do usuário final e das pessoas ao seu redor;
* **Máquina (dispositivos, plataformas e interfaces):** Refere-se aos aparelhos e ambientes digitais que moldam o comportamento do usuário;
* **Medida (métricas, percepção de progresso e feedbacks):** Refere-se a como o usuário percebe se está evoluindo, relaxando ou "ganhando" algo com a atividade;
* **Meio Ambiente (contexto social, cultura e ecossistema):** Refere-se ao cenário externo, cultural e do dia a dia que molda o estilo de vida da população;

![Diagrama de Ishikawa](assets/Captura%20de%20Tela%20(567).jpg)
*Figura 1: Diagrama de Ishikawa do projeto MinhaTirinha*

### 1.3 Desafios do Projeto
O principal desafio identificado para o projeto perdura na dificuldade de desenvolver um produto com alta qualidade técnica tendo em vista que a equipe de desenvolvedores é formada por universitários quase inexperientes, além de visar eficiência e relevância quanto a sua contribuição como ferramenta de entretenimento saudável para o público alvo.

### 1.4 Segmentação de Clientes
Por mais que os benefícios já mencionados sejam algo que beneficie praticamente todas as pessoas, iremos priorizar o foco no **público jovem (13-27 anos)**:

* Adolescentes (13 - 17 anos)
* Jovens Adultos (18 - 27 anos)

---

## 2. SOLUÇÃO PROPOSTA

### 2.1 Objetivos do Produto
O objetivo geral compreende viabilizar uma ferramenta digital de entretenimento que estimule hábitos cognitivos saudáveis através da leitura linear, pintura e criação de conteúdo.

| Código | Objetivo Específico |
| :--- | :--- |
| **OE1** | Facilitar o acesso à ferramenta. |
| **OE2** | Incentivar a prática da pintura. |
| **OE3** | Incentivar a prática da leitura linear. |
| **OE4** | Incentivar a criação de histórias. |
| **OE5** | Promover a visibilidade de conteúdos da plataforma. |

### 2.2 Características da Solução

| Objetivo Específico | Código | Característica da Solução |
| :--- | :--- | :--- |
| **OE1** | CS1 | Disponibilizar acesso a conta pessoal do usuário. |
| | CS2 | Garantir acesso contínuo à ferramenta. |
| **OE2** | CS3 | Disponibilizar uma coleção de tirinhas de gibi contendo imagens para pintura. |
| | CS4 | Disponibilizar ferramentas para exercer a prática de pintura nas imagens das tirinhas. |
| **OE3** | CS5 | Disponibilizar uma coletânea de tirinhas de gibi contendo histórias para leitura. |
| | CS6 | Promover o acompanhamento da evolução do usuário na leitura. |
| **OE4** | CS7 | Disponibilizar meios para criar tirinhas que contenham imagens e histórias. |
| | CS8 | Disponibilizar meios para gerenciar tirinhas criadas. |
| **OE5** | CS9 | Disponibilizar meios de compartilhamento de tirinhas finalizadas para ambientes externos. |
| | CS10 | Disponibilizar meios para armazenar de forma local tirinhas finalizadas. |

---

## 3. ESTRATÉGIAS DE ENGENHARIA DE SOFTWARE

### 3.1 Estratégia Priorizada

| Dimensão | Definição |
| :--- | :--- |
| **Abordagem** | Ágil |
| **Ciclo de vida** | Incremental e iterativo |
| **Processo** | Híbrido, combinando Scrum e XP |
| **Organização visual** | Kanban no Trello |
| **Práticas de apoio** | Design Sprint, prototipação, validação com usuário, revisão técnica e rastreabilidade |

### 3.2 Justificativa
A abordagem ágil é adequada porque o produto depende de validação constante da experiência do usuário (pintura, fluxo de leitura). A combinação de Scrum e XP favorece o planejamento por entregas e a qualidade técnica através de revisões e colaboração.

---

## 4. DOR E DOD

### 4.1 Definition of Ready (DoR)
* Registrado no backlog e vinculado a um requisito.
* Descrição clara do valor esperado.
* Critérios de aceitação verificáveis.
* Priorizado para a sprint ou release.
* Dependências conhecidas.
* Coerente com protótipos e diagramas.
* Estimativa de esforço compatível.

### 4.2 Definition of Done (DoD)
* Código implementado conforme critérios de aceitação.
* Interface coerente com protótipos e tons pastéis.
* Fluxo testado em ambiente mobile via Expo Go.
* Funcionalidade revisada via pull request.
* Documentação atualizada.
* Sem erros críticos no fluxo principal.
* Requisito rastreado no backlog e documentação.

---

## 5. BACKLOG DO PRODUTO

### 5.1 Requisitos funcionais

| Código | Requisito funcional |
| :--- | :--- |
| **RF01** | Visualizar catálogo de histórias em quadrinhos organizado por temas. |
| **RF02** | Selecionar uma história para visualização. |
| **RF03** | Exibir a história selecionada em quadrinhos sequenciais, um por vez. |
| **RF04** | Selecionar um quadrinho específico para interação, quando desbloqueado. |
| **RF05** | Exibir ícone de cadeado nos quadrinhos indisponíveis até a conclusão do anterior. |
| **RF06** | Permitir a pintura dos elementos do quadrinho, exceto os balões de fala. |
| **RF07** | Bloquear a visualização dos balões de fala antes da conclusão da pintura. |
| **RF08** | Desbloquear automaticamente os balões após a conclusão da pintura. |
| **RF09** | Retomar a história e a pintura do ponto em que foram interrompidas. |
| **RF10** | Visualizar histórias já iniciadas ou concluídas. |
| **RF11** | Salvar automaticamente o progresso do usuário em cada história. |
| **RF12** | Acessar galeria pessoal com histórias disponíveis e respectivo progresso. |
| **RF13** | Exibir feedback visual ao concluir a pintura e desbloquear os balões. |
| **RF14** | Realizar login no sistema. |
| **RF15** | Realizar cadastro no sistema. |
| **RF16** | Compartilhar ou baixar histórias completamente coloridas. |
| **RF17** | Redefinir o progresso de uma história já concluída. |
| **RF18** | Disponibilizar paleta de cores para pintura dos quadrinhos. |
| **RF19** | Disponibilizar ferramenta de balde de tinta na página Cavalete. |
| **RF20** | Disponibilizar ferramenta de borracha na página Cavalete. |
| **RF21** | Exibir três opções de cores recentes na página Cavalete. |
| **RF22** | Exibir modal de seleção RGB ao clicar em uma das cores recentes. |
| **RF23** | Salvar remotamente o progresso do usuário vinculado à conta. |

### 5.2 Requisitos não funcionais

| Código | Requisito não funcional |
| :--- | :--- |
| **RNF01** | Possuir interface simples, intuitiva e de fácil navegação. |
| **RNF02** | Utilizar paleta de cores em tons pastéis. |
| **RNF03** | Apresentar design limpo e com baixa poluição visual. |
| **RNF04** | Garantir tempo de resposta rápido durante a pintura. |
| **RNF05** | Garantir armazenamento seguro do progresso vinculado à conta. |
| **RNF06** | Ser compatível com dispositivos Android. |
| **RNF07** | Adotar arquitetura modular para facilitar manutenção e evolução. |
| **RNF08** | Permitir inclusão de música de fundo suave. |
| **RNF09** | Ser escalável para suportar novas histórias e funcionalidades. |

### 5.3 User Story Mapping consolidado

| Código | História de usuário | RF relacionados |
| :--- | :--- | :--- |
| **US01** | Como usuário, quero criar uma conta para salvar meu progresso. | RF15 |
| **US02** | Como usuário, quero entrar no sistema para continuar em outro momento. | RF14, RF23 |
| **US03** | Como usuário, quero navegar por temas para escolher o conteúdo. | RF01, RF02 |
| **US04** | Como usuário, quero pintar quadrinhos para avançar na narrativa. | RF03, RF04, RF06 |
| **US05** | Como usuário, quero que balões fiquem bloqueados até eu concluir a pintura. | RF05, RF07, RF08 |
| **US06** | Como usuário, quero visualizar meu progresso para entender meu avanço. | RF09, RF10, RF11, RF12 |
| **US07** | Como usuário, quero usar ferramentas de pintura (balde, paleta, borracha). | RF18, RF19, RF20, RF21, RF22 |
| **US08** | Como usuário, quero baixar ou compartilhar a história concluída. | RF16 |
| **US09** | Como usuário, quero redefinir uma história concluída para repintar. | RF17 |

---

## 6. REFERÊNCIAS E FONTES ANALISADAS
* REVISTA FT. Os desafios da leitura na era digital. 05 out. 2025.
* COSTERUS, Marco. 7 Benefícios da Pintura para a Saúde Mental. 15 fev. 2022.
* FENATI. Brain rot: o que a ciência sabe sobre os vídeos curtos. 8 dez. 2024.
* GOOGLE. Template Ishikawa Engenharia de Software. Gemini 3 Flash, 4 abr. 2026.




## Histórico de Versões 

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| :--: | :--: | :--: | :--: | :--: |
| 1.0 | 23/04/2026 | Adição das informacoes referentes a essa entrega | [Guilherme Flyan](https://github.com/GFlyan) | [Marjorie](https://github.com/Marjoriemitzi) |
| 1.2 | 23/04/2026 | Adição do documento e Adição de informacoes faltantes | [Marjorie Mitzi] (https://github.com/Marjoriemitzi) | [Guilherme Flyan](https://github.com/GFlyan)  | 