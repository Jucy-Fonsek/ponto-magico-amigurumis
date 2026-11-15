# Ponto Mágico Amigurumis 🧶

**A magia do crochê feita para abraçar.**

Uma loja virtual desenvolvida para facilitar a divulgação e a comercialização de amigurumis artesanais, aproximando clientes e artesã por meio de um catálogo organizado e de um processo simplificado de solicitação de encomendas.

> Projeto desenvolvido como parte de um desafio de criação de produto digital com apoio de inteligência artificial.

---

## 1. A dor escolhida: por que esse negócio existe?

O projeto nasceu de uma situação real: uma artesã que produz e comercializa amigurumis precisa responder repetidamente às mesmas perguntas de diferentes clientes.

Dúvidas sobre modelos, tamanhos, preços, personalizações e encomendas acabam tornando o atendimento repetitivo e consumindo tempo que poderia ser dedicado à produção artesanal.

Além disso, existe uma hipótese a ser investigada: alguns potenciais compradores podem deixar de entrar em contato por imaginar que o processo de encomenda será complicado ou que os produtos terão preços acima do que podem pagar.

A oportunidade de negócio está em tornar essas informações mais acessíveis, organizar a apresentação dos produtos e simplificar o primeiro contato entre cliente e artesã.

**Problema central:** a ausência de um canal digital organizado que apresente os produtos, forneça referências de preços e facilite a solicitação de encomendas.

## 2. Tamanho de mercado: TAM, SAM e SOM

O mercado de amigurumis está inserido no segmento mais amplo do artesanato. Como não há, neste levantamento inicial, uma mensuração específica e consolidada do mercado brasileiro de amigurumis, foram utilizadas referências do setor artesanal como aproximação.

### TAM — Mercado Total Endereçável

O TAM corresponde ao mercado brasileiro de artesanato como um todo.

Uma estimativa preliminar utilizada na etapa de validação foi de aproximadamente **R$ 102 bilhões** para o mercado artesanal brasileiro. Esse valor representa o setor amplo, não exclusivamente o mercado de amigurumis.

### SAM — Mercado Disponível

O SAM considera a parcela do mercado que pode ser alcançada por canais digitais.

Como referência preliminar, foi considerado um levantamento setorial que apontou aproximadamente 20% de participação das compras pesquisadas realizadas pela internet.

Aplicando esse percentual à estimativa ampla anterior, chega-se a uma referência indicativa de R$ 20,4 bilhões.

Esse cálculo é uma aproximação, não uma mensuração direta do mercado online de amigurumis.

### SOM — Mercado Obtível

O SOM considera a capacidade real de atendimento da artesã.

A capacidade produtiva inicial informada é de aproximadamente **10 peças por mês**, o equivalente a até 120 peças por ano, caso esse ritmo seja mantido.

O faturamento potencial dependerá do preço médio das peças:

**SOM anual em faturamento = 120 × preço médio por peça.**

Esse cálculo representa capacidade produtiva teórica, não uma previsão de vendas. A demanda efetiva, o tempo de produção e a disponibilidade da artesã precisam ser acompanhados.

## 3. Business Model Canvas

| Elemento | Definição |
|---|---|
| **Segmentos de clientes** | Pessoas interessadas em presentes artesanais, peças personalizadas, decoração e amigurumis. |
| **Proposta de valor** | Catálogo acessível, informações de preços mais transparentes e solicitação simplificada de encomendas. |
| **Canais** | Loja virtual, redes sociais e WhatsApp. |
| **Relacionamento com clientes** | Atendimento direto e personalizado, com acompanhamento manual das solicitações. |
| **Fontes de receita** | Venda de amigurumis disponíveis e produção de peças sob encomenda. |
| **Recursos principais** | Conhecimento artesanal, materiais, fotografias dos produtos, catálogo digital e plataforma de vendas. |
| **Atividades principais** | Produção das peças, atualização do catálogo, atendimento e organização das encomendas. |
| **Parcerias principais** | Fornecedores de materiais e serviços de entrega. |
| **Estrutura de custos** | Materiais, tempo de produção, embalagem, entrega e manutenção da presença digital. |

## 4. A tese que o MVP pretende testar

A principal hipótese do projeto é:

**Se os clientes encontrarem um catálogo organizado, com fotografias, descrições e referências de preços, e puderem solicitar uma encomenda por meio de um formulário simples, haverá menos dúvidas repetitivas e maior facilidade para iniciar uma compra.**

O MVP foi pensado para testar quatro hipóteses:

1. A apresentação organizada dos produtos facilita a descoberta e a escolha.
2. A disponibilização de referências de preços reduz dúvidas iniciais.
3. Um formulário estruturado melhora a qualidade das informações recebidas pela artesã.
4. A organização das solicitações facilita o acompanhamento dos pedidos.

### Indicadores que poderão ser acompanhados

- Quantidade de visitantes do catálogo.
- Quantidade de solicitações recebidas.
- Produtos mais procurados.
- Solicitações convertidas em pedidos confirmados.
- Dúvidas que continuam aparecendo no atendimento.
- Tempo gasto pela artesã na organização das encomendas.

## 5. O que o MVP oferece

O escopo inicial foi reduzido para concentrar os esforços nas funcionalidades essenciais.

### Área pública

- Página inicial com a identidade visual da marca.
- Catálogo de amigurumis.
- Página de detalhes dos produtos.
- Informações de preços ou estimativas.
- Formulário de solicitação de encomenda.
- Acesso ao contato pelo WhatsApp.

### Área administrativa

- Acesso restrito à artesã.
- Cadastro, edição e gerenciamento de produtos.
- Visualização das solicitações recebidas.
- Atualização do status das encomendas.

### O que ficou manual de propósito?

Algumas atividades foram mantidas sob responsabilidade da artesã:

- Avaliação da disponibilidade para produzir uma peça.
- Confirmação do orçamento e do prazo.
- Negociação de personalizações.
- Confirmação definitiva do pedido.
- Atendimento pelo WhatsApp.
- Organização da produção e da entrega.

Essa decisão evita a complexidade de automatizar processos que dependem de avaliação humana e respeita a capacidade produtiva inicial de aproximadamente 10 peças mensais.

O MVP não contempla pagamento online, carrinho de compras, cadastro de clientes, integração automática com WhatsApp ou múltiplos vendedores.

## 6. Desenvolvimento com inteligência artificial

A construção do projeto foi orientada por um mega-prompt elaborado previamente, com a descrição do negócio, da identidade visual, das funcionalidades e das limitações do MVP.

A ferramenta utilizada para desenvolver a aplicação foi o **Lovable**, com a proposta de utilizar o Lovable Cloud para a infraestrutura de backend.

### Mega-prompt

O prompt completo utilizado no desenvolvimento está disponibilizado neste repositório como:

`docs/mega-prompt.md`

Ele especifica:

- Contexto e objetivo do negócio.
- Identidade visual da marca.
- Uso obrigatório da imagem original anexada.
- Estrutura das páginas.
- Catálogo e detalhes dos produtos.
- Formulário de encomendas.
- Painel administrativo.
- Banco de dados e permissões.
- Limitações do MVP.

### Correções e orientações posteriores

Durante o desenvolvimento, foram necessárias orientações complementares para manter o projeto alinhado à proposta inicial:

1. **Uso da identidade visual original:** foi reforçado que a imagem já criada e anexada deveria ser utilizada diretamente, sem ser redesenhada ou substituída por outra gerada por IA.
2. **Controle do escopo:** foram excluídas funcionalidades adicionais que poderiam aumentar a complexidade e o consumo de créditos.
3. **Acesso administrativo:** foi solicitada uma configuração segura para a criação da primeira conta da artesã, sem permitir cadastro público de administradores.
4. **Uso econômico dos créditos:** as instruções priorizaram as funcionalidades essenciais do MVP, considerando o limite de cinco créditos disponíveis.

O desenvolvimento foi realizado considerando as restrições do plano utilizado e priorizando uma primeira versão demonstrável.

## 7. Tecnologias e ferramentas

- **Lovable:** desenvolvimento da aplicação com auxílio de inteligência artificial.
- **Lovable Cloud:** backend, banco de dados, autenticação e armazenamento, conforme a configuração do projeto.
- **GitHub:** versionamento e disponibilização pública do código-fonte.
- **ChatGPT:** apoio à estruturação do negócio, validação das hipóteses, elaboração do mega-prompt e refinamento dos requisitos.

## 8. Evidências do projeto

Nesta seção serão disponibilizadas capturas de tela da aplicação e do painel administrativo.

As imagens estão adicionadas ao repositório  na pasta `docs/images/`.

Evidências previstas:

- Página inicial.
- Catálogo de produtos.
- Detalhes de um produto.
- Formulário de solicitação de encomenda.
- Tela de acesso da artesã.
- Painel administrativo.
- Gerenciamento das solicitações.

## 9. Aplicação publicada

**Endereço da aplicação:** https://ponto-magico-amigurumis.lovable.app

**Repositório GitHub:** https://github.com/Jucy-Fonsek/ponto-magico-amigurumis

## 10. Considerações finais

O Ponto Mágico Amigurumis surgiu de uma necessidade observada em uma atividade artesanal real e foi transformado em uma proposta de produto digital.

Mais do que construir uma loja virtual, o objetivo do projeto é testar se a organização das informações e a simplificação do processo de encomenda podem melhorar a experiência dos clientes e facilitar a rotina da artesã.

A primeira versão prioriza o essencial: apresentar os produtos, informar preços de referência, receber solicitações e organizar o atendimento.

O desenvolvimento com inteligência artificial permitiu transformar uma ideia de negócio em uma aplicação digital, mantendo o foco em uma dor concreta, em hipóteses testáveis e em uma solução compatível com a realidade produtiva da artesã.

---

**Ponto Mágico Amigurumis — A magia do crochê feita para abraçar.**
