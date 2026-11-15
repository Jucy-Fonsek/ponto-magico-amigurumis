# PONTO MÁGICO AMIGURUMIS — DESENVOLVIMENTO DO MVP

## 1. SOBRE O PROJETO

Desenvolva uma loja virtual chamada **Ponto Mágico Amigurumis**, destinada à divulgação e comercialização de amigurumis artesanais produzidos por uma única artesã.

**Slogan:** A magia do crochê feita para abraçar.

O objetivo é facilitar o acesso dos clientes ao catálogo, apresentar informações de preços de maneira transparente e simplificar a solicitação de encomendas.

A loja poderá atender inicialmente clientes da região da artesã, mas deverá estar preparada para receber solicitações de qualquer lugar do Brasil.

A capacidade produtiva inicial considerada é de aproximadamente **10 peças por mês**. Portanto, o sistema deve permitir que a artesã controle as solicitações e organize os pedidos conforme sua capacidade de produção.

## 2. IDENTIDADE VISUAL — USO OBRIGATÓRIO DA IMAGEM ANEXADA

**Utilize diretamente a imagem original anexada a este projeto.**

Essa imagem já foi criada e representa a identidade visual desejada para a marca.

Regras obrigatórias:

- Não crie outra versão da imagem.
- Não redesenhe a arte.
- Não substitua a imagem por uma imagem gerada por inteligência artificial.
- Não altere suas cores, elementos, composição ou características originais.
- Preserve a proporção e a qualidade do arquivo.
- Utilize a imagem na página inicial, em posição de destaque e adequada à identidade da loja.

Caso o arquivo anexado não esteja acessível, solicite seu envio novamente. Não tente recriá-lo.

A identidade visual complementar deve utilizar tons suaves de verde-menta, pêssego, creme e marrom-claro, transmitindo delicadeza, acolhimento e profissionalismo.

O site deve ter aparência artesanal, organizada, moderna e responsiva, sem excesso de elementos decorativos.

## 3. ESTRUTURA DO SITE

Desenvolva uma aplicação web responsiva, adaptada para computadores e celulares.

### 3.1 Página inicial

A página inicial deve apresentar:

- A imagem original da marca em destaque.
- O nome Ponto Mágico Amigurumis.
- O slogan da loja.
- Uma breve apresentação da proposta da marca.
- Uma seção com alguns produtos em destaque.
- Um botão para acessar o catálogo.
- Um botão de contato pelo WhatsApp.

A navegação deve ser simples e intuitiva.

### 3.2 Catálogo de produtos

Criar uma página com os amigurumis disponíveis no catálogo.

Cada produto deve apresentar:

- Fotografia do produto.
- Nome.
- Breve descrição.
- Preço ou faixa de preço estimada.
- Informação sobre disponibilidade ou necessidade de encomenda.
- Botão para visualizar detalhes.

O catálogo deve permitir que a artesã cadastre novos produtos e atualize as informações existentes.

Os preços poderão ser apresentados como valores de referência, faixas estimadas ou orçamento sob consulta.

Não invente preços. Utilize apenas os valores cadastrados pela artesã.

### 3.3 Página de detalhes do produto

Cada produto deverá ter uma página própria com:

- Fotografia.
- Nome.
- Descrição.
- Preço ou estimativa, quando disponível.
- Possibilidades de personalização.
- Informação sobre encomendas.
- Botão para solicitar orçamento ou encomendar.

### 3.4 Solicitação de encomenda

Criar um formulário simples, sem exigir cadastro ou login do cliente.

Campos:

- Nome do cliente.
- WhatsApp ou telefone para contato.
- Produto desejado.
- Tamanho pretendido.
- Cores desejadas.
- Quantidade.
- Personalização, se houver.
- Observações adicionais.

O formulário deverá permitir o envio da solicitação e armazenar os dados no banco de dados.

Após o envio, apresentar uma mensagem confirmando que a solicitação foi recebida e que a artesã entrará em contato.

A solicitação não representa confirmação automática de compra. A artesã deverá analisar a disponibilidade, o prazo e o orçamento antes de confirmar o pedido.

### 3.5 Contato pelo WhatsApp

Disponibilizar um botão de contato pelo WhatsApp em locais estratégicos do site.

O botão deverá direcionar o cliente para uma conversa com a artesã, utilizando o número configurado no sistema.

Quando possível, incluir uma mensagem inicial relacionada ao produto visualizado.

Não implementar integração automática com a API do WhatsApp. Apenas utilizar o link de conversa.

## 4. PAINEL ADMINISTRATIVO DA ARTESÃ

Criar uma área administrativa protegida por autenticação.

Somente a artesã autorizada poderá acessar essa área. Não permitir cadastro público de administradores.

O painel deverá permitir:

### Gerenciamento de produtos

- Cadastrar produtos.
- Editar produtos.
- Excluir produtos.
- Ativar ou desativar produtos.
- Inserir fotografias.
- Informar nome, descrição e preço.
- Definir se o produto está disponível, é feito sob encomenda ou está temporariamente indisponível.

### Gerenciamento de solicitações

- Visualizar as solicitações recebidas.
- Consultar os dados informados pelo cliente.
- Visualizar o produto desejado.
- Consultar as personalizações solicitadas.
- Atualizar o status da solicitação.

Utilizar os seguintes status:

1. Recebida.
2. Em análise.
3. Orçamento enviado.
4. Pedido confirmado.
5. Em produção.
6. Finalizado.
7. Entregue.
8. Cancelado.

O painel deve apresentar uma visão simples e organizada das solicitações.

## 5. BANCO DE DADOS E BACKEND

Utilize exclusivamente o **Lovable Cloud** para implementar o backend e o banco de dados.

Não utilizar serviços externos de banco de dados.

Criar as estruturas necessárias para armazenar:

- Produtos.
- Fotografias dos produtos.
- Solicitações de encomenda.
- Informações necessárias à autenticação administrativa.

Implementar as permissões de acesso adequadas:

- Visitantes podem visualizar produtos ativos.
- Clientes podem enviar solicitações.
- Clientes não podem consultar solicitações de outras pessoas.
- Somente a administradora autorizada pode acessar e gerenciar produtos e solicitações.
- Proteger os dados pessoais dos clientes.

Utilizar as políticas de segurança do banco de dados e do armazenamento de arquivos.

## 6. FUNCIONALIDADES QUE NÃO DEVEM SER IMPLEMENTADAS NESTA VERSÃO

Para manter o projeto simples e econômico, não desenvolver:

- Cadastro ou login de clientes.
- Área pessoal do cliente.
- Pagamento online.
- Carrinho de compras.
- Integração automática com WhatsApp.
- Controle avançado de estoque.
- Sistema de cupons.
- Programa de fidelidade.
- Avaliações de clientes.
- Integração com transportadoras.
- Aplicativo para celular.
- Relatórios avançados.
- Funcionalidades de marketplace.
- Múltiplos vendedores.

Essas funcionalidades poderão ser consideradas em versões futuras.

## 7. ORIENTAÇÕES TÉCNICAS

- Desenvolva a aplicação do zero.
- Utilize o Lovable Cloud para banco de dados, autenticação e armazenamento.
- Priorize uma estrutura simples, funcional e de fácil manutenção.
- Garanta que o site funcione corretamente em computadores e celulares.
- Utilize componentes reutilizáveis.
- Evite funcionalidades desnecessárias.
- Não crie páginas ou recursos que não foram solicitados.
- Não utilize imagens fictícias como se fossem fotografias reais dos produtos. Se ainda não houver fotografias disponíveis, utilize espaços reservados que possam ser preenchidos posteriormente.
- Não invente informações comerciais, preços, contatos ou prazos.

## 8. RESULTADO ESPERADO

Entregar um MVP funcional da loja Ponto Mágico Amigurumis, contendo:

1. Página inicial com a imagem original da marca.
2. Catálogo de produtos.
3. Página de detalhes dos produtos.
4. Formulário de solicitação de encomendas.
5. Contato pelo WhatsApp.
6. Painel administrativo protegido.
7. Cadastro e gerenciamento de produtos.
8. Visualização e gerenciamento das solicitações.
9. Banco de dados integrado ao Lovable Cloud.
10. Layout responsivo.

**PRIORIDADE ABSOLUTA:** entregar primeiro as funcionalidades essenciais descritas neste documento. Não ampliar o escopo por iniciativa própria. Se alguma implementação exigir decisões adicionais ou funcionalidades que não foram especificadas, priorize a solução mais simples e segura, preservando os requisitos do MVP.

Antes de finalizar, verifique se as principais funcionalidades estão operacionais e se as permissões de acesso estão corretamente configuradas.
