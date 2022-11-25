# Simulação de planejamento de projeto
Nesse repositório estão armazenadas partes de uma simulação de planejamento de um projeto de programação. O projeto consiste em criar um PDV com banco integrado ao Ecommerce já existente. 

#### > Apresentação de projeto

É necessário criar um software para gerenciar as vendas de um comércio. A loja pretende expandir suas vendas para fora do âmbito online até dezembro, e necessita de um sistema que entregue a mesma eficiência que o site, mas sem perder os dados já cadastrados no banco de dados do Ecommerce.

#### > Simulação de escopo - Levantamento de dados
 
| Partes do escopo | Descrição |
| :------ | ----------- |
| Projeto | Foi solicitado a criação de um sistema PDV com todas as telas necessárias, possuindo integração com o banco de dados já existente na loja online. É importante que as informações de cliente, produtos, e pedidos sejam únicos nos dois ambientes. |
| Prazo | De 11/11 até 31/11 |
| Equipe nescessária | Analista, UX/UI, Desenvolvedor Back, Desenvolvedor Front e Tester |
| Motivo da solicitação | Expandir as vendas do cliente, adicionando um sistema para venda no âmbito físico

#### > Identificação de história raiz

Como cliente, gostaria de ter um sistema PDV que tenha conexão com o banco de dados do sistema de vendas online

#### > Critério de aceitação

- Aceitação do cliente
- Funcionamento do PDV
- Vinculo dos dados de clientes cadastrados, pedidos feitos e produtos configurados

#### > Premissas do projeto

- Vamos assumir que o cliente não exigirá que o sistema seja feito em uma linguagem que os desenvolvedores não conhecem  
- Vamos assumir que o banco de dados original (loja online) é bem projetado e permite a ligação de sistemas
- Vamos assumir que os dias de jogo da copa 2022 não irão reduzir a produtividade da equipe

#### > Restrições do Projeto 

- Prazo muito curto
- Baixo desempenho devido a copa 2022

#### > Riscos do projeto

- A equipe não irá trabalhar nos horários que estiver acontecendo jogo do Brasil na copa 2022
- O sistema deverá ser entregue até dia 31/12/2022
- O sistema deverá, de inicio, ter as mesmas configurações de produtos que a loja original (online)

#### > Requisitos principais 

| Requisitos Funcionais | Requisitos não funcionais |
| :----------- | :----------- |
| RF001 - O sistema deve permitir criar, alterar e excluir um produto do cadastro no banco de dados. | RNF001 - O sistema deve gerar um relatório de vendas e lucro no final de cada dia, semana, e mês. | 
| RF002 - O sistema deve permitir o funcionário responsável pelo PDV de logar e se cadastrar antes de iniciar a venda. | RNF002 - O sistema deve ser simples e intuitivo para facilitar o treinamento dos funcionários. |
| RF003 - O sistema deve ser capaz de gerar uma nota fiscal ou "notinha" ao final de cada compra. | RNF003 - O sistema deve enviar automaticamente a nota fiscal para o contador responsável. |

#### > Entregas estimadas 

- Layout da tela de login para o vendedor, carrinho de compras com os valores e quantidades, seleção de produtos com opção de selecionar quantidade, finalização de venda com possibilidade de cadastras novos usuários, configuração de vendedor antes de iniciar uma venda, ajuste de produtos para preço ou código de venda, criação de cadastro de cliente na página da home e outras telas necessárias em um PDV.
- Análise de funcionamento do banco de dados original, de esforço e como será feito o vínculo da forma mais eficaz possível.
- Apresentação de funcionamento pelo tester e pela equipe, após a validação de todos os ajustes necessários e pleno funcionamento do projeto.

#### > Etapas do projeto - Planejamento inicial

- 01. [UX/UI] Desenvolvimento de layout do carrinho de compras, cadastro de clientes, tela de seleção e ajuste de produtos no PDV [11/11 a 18/11]
>> Entrega das telas no Figma
- 02. [Analista] Análise do banco de dados original (Loja online) e de como será a ligação com a loja física [11/11 a 10/12]
>> Entrega de relatório de banco e modelo de fluxo
- 03. [Dev. Back] Desenvolvimento das telas criadas [21/11 a 09/12]
>> Entrega do back das telas
- 04. [Dev. Front] Desenvolvimento das telas criadas [21/11 a 09/12]
>> Entrega do front das telas
- 05. [Dev. Back] Vinculo com o banco de dados original [09/12 a 16/12]
>> Entrega no Fluxo de banco implementado
- 06. [Tester] Verificação de funcionamento completo [16/12 a 23/12]
>> Entrega de relatório de testes
- 07. [Equipe] Ajustes necessários pontuados pelo tester [ 23/12 a 28/12/2022]
>> Entrega do projeto final

_Entregas planejadas com 2 dias de sobra para ressalva de atraso_

#### > Diagrama de PERT

![PERT Diagram](https://user-images.githubusercontent.com/74381091/203989098-49adeef3-c3fb-47c4-a6cb-c548b3197f2a.png)

