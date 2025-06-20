---
title: "Eliminando o Ruído: Blockchain em 2025 e os Casos de Uso que Transformam Indústrias"
date: "2025-04-25"
authors: ["whiteStone_bot", "Doug Silva"]
tags: [Blockchain, Web3, Cripto, CasosDeUso, Inovação, Stellar, Ethereum, Solana, DeFi, NFTs, Pagamentos, Tokenização, CheesecakeLabs]
thumb: "/img/blog/posts/edicao7/doug_slide1.jpg"
short_description: "Doug Silva da Cheesecake Labs desmistifica o cenário do blockchain, focando em aplicações práticas que vão além da especulação. Descubra como a tecnologia está revolucionando pagamentos internacionais, ajuda humanitária, tokenização de ativos e stablecoins, com insights sobre o futuro da Web3 em 2025."
---

> Este blogpost foi gerado a partir da **talk apresentada pelo [Doug](https://www.linkedin.com/in/douglasgimli)** durante a **7ª Edição | Cripto - Especial Fênix**.  
> O conteúdo abaixo reflete os principais pontos e reflexões compartilhadas ao vivo, adaptados para leitura, e aprofunda a visão do palestrante sobre o presente e o futuro da tecnologia blockchain.  
> Assista à apresentação completa no [YouTube](https://www.youtube.com/live/C-YejH6p878?t=1733)



### O Cenário Atual da Blockchain: Da Especulação à Utilidade Real

Quando a gente olha para o universo cripto e blockchain, percebemos que estamos saindo de um período de muita especulação para um foco muito maior na **utilidade**. Essa mudança é fundamental, pois impulsiona a demanda por blockchains mais **especializadas** – não redes que tentam fazer de tudo, mas aquelas que resolvem problemas específicos.

É visível a **adoção institucional** crescendo a cada dia. Empresas como Fidelity, BlackRock, Itaú, BTG e Nubank já estão integrando a blockchain em diferentes níveis de seus negócios. Até mesmo gigantes tradicionais como Visa e Mastercard já utilizam blockchain em partes de suas operações, e a MoneyGram, que é um "dinossauro" do mercado, abraçou a inovação blockchain como um ponto estratégico. No quesito regulatório, os governos estão se atualizando rapidamente, com avanços na Europa e Ásia, e o Brasil, por incrível que pareça, está bem favorável para essa parte de blockchain.

Para ilustrar essa evolução, eu selecionei três redes que refletem bem o espectro do que estamos vendo:

*   **Ethereum:** A grande pioneira que consolidou conceitos como Smart Contracts e DeFi, não parou no tempo. Ela continua evoluindo com importantes atualizações como a troca para Proof of Stake e o Dunksharding, buscando eficiência em custos e throughput.
*   **Solana:** Essa já nasceu para ser rápida e barata, resolvendo problemas de custo e velocidade que o Ethereum ainda está endereçando. Seu ecossistema de desenvolvimento é muito rico, consolidando-se em pontos de DeFi e NFT.
*   **Stellar:** Parecida com a Solana em velocidade e custo, a Stellar tem uma filosofia focada em resolver dores específicas da área financeira. Ela traz inovações como os "PF payments" (conversão entre moedas com uma única transação), funcionalidades nativas de tokenização e o conceito de "âncoras" – entidades que facilitam a conversão de dinheiro físico (fiat) para cripto e vice-versa, conectando o mundo real à infraestrutura blockchain. Além disso, a adição de Smart Contracts via Soroban, lançada recentemente, é um marco importante, mostrando que eles aprenderam com os acertos e erros de outras redes.

<img src="/img/blog/posts/edicao7/doug_slide3.jpg" />
<img src="/img/blog/posts/edicao7/doug_slide2.jpg" />

A grande mensagem que quero deixar aqui é que o mundo está se movendo de uma competição acirrada entre redes para um caminho de **especialização**. A pergunta não é mais "Qual é a melhor blockchain?", mas sim "Qual rede resolve qual dor? Qual faz mais sentido para o que eu quero construir?". A tecnologia está focando em complementar, não em substituir.

### Casos de Uso Reais: Transformando Indústrias

Agora, vamos aos casos de uso que realmente estão transformando indústrias, com exemplos que talvez vocês já até usem ou que impactam a vida de milhões de pessoas.

#### 1.  **Pagamentos Cross-Border e Remessas:**
Esse é um mercado trilionário, movimentando quase 40 trilhões de dólares por ano, mas que historicamente é lento e caro. As taxas podem chegar a 10%, e as transferências demoram dias para chegar ao destino.

<img src="/img/blog/posts/edicao7/doug_map.png" style="max-width: 300px; display: block; margin: 0 auto;" />


A parceria entre **MoneyGram e Stellar** revolucionou esse cenário. A MoneyGram é uma gigante com capilaridade em 200 países e mais de 300.000 agências. Eles pegaram toda essa infraestrutura tradicional e a disponibilizaram para a blockchain.

Lançaram uma carteira própria, que funciona como um banco no celular, mas é **não-custodial** (você tem o controle total sobre seus criptoativos) e foi feita para quem quer apenas enviar ou receber dinheiro, sem precisar ser um expert em cripto.

Imaginem só: eu posso ir a uma agência MoneyGram com dinheiro físico (real), enviar para minha mãe na Argentina, e esse dinheiro cai na carteira dela instantaneamente, já convertido para **USDC** (uma stablecoin que será abordada na próxima talk, mas que serve como proteção contra a inflação em países como a Argentina). Ela pode então sacar em pesos em outra agência MoneyGram em segundos e com custos relativamente zero.

Isso é vital para a **inclusão financeira**! Mais de 2 bilhões de pessoas no mundo não têm acesso a contas bancárias. Imigrantes, trabalhadores sem documentação – essas pessoas estão excluídas do sistema financeiro. Com a MoneyGram e Stellar, elas conseguem enviar e receber dinheiro internacionalmente sem uma conta bancária tradicional, apenas com o aplicativo e uma identificação.

A MoneyGram também lançou um **SDK**, permitindo que outras carteiras (como Vibrant e Vesso, projetos que a Cheesecake Labs, onde trabalho, tem atuado) utilizem essa infraestrutura para transações.

Um caso que me emociona muito é o uso humanitário. Na guerra da Ucrânia, muitas pessoas perderam acesso a seus meios de pagamento. Organizações humanitárias, em parceria com MoneyGram e Stellar, conseguiram distribuir doações em minutos, não semanas. As pessoas recebiam um SMS, baixavam o aplicativo, faziam um KYC simplificado e podiam sacar o dinheiro em agências MoneyGram, mesmo em meio ao conflito. Isso prova que não precisamos "disruptar" o sistema financeiro, mas sim **complementá-lo e melhorá-lo** com essas ferramentas.

#### 2.  **Tokenização de Ativos:**
Este é um mercado gigante em ascensão, com projeções de atingir US$ 500 bilhões até 2025 (excluindo stablecoins). Basicamente, estamos falando de representar digitalmente ativos do mundo real, como imóveis, títulos (securities) ou commodities (como ouro).

O grande benefício aqui é a **propriedade fracionada** e a **acessibilidade**. Pensem numa barra de ouro de 1 milhão de reais. Antes, só quem tinha 1 milhão de reais comprava. Com a tokenização, você pode dividir essa barra em milhões de "pedacinhos virtuais", e qualquer um pode investir com R$1,00. Isso democratiza o acesso a investimentos antes restritos a poucos.

Alguns exemplos notáveis:
*   **Loft:** Essa startup criou fundos imobiliários na blockchain. Pessoas podem tokenizar seus imóveis e vender frações, recebendo rendimentos em troca. Casos de pessoas que reformaram casas com esses fundos são muito inspiradores.
*   **Mercado Bitcoin:** A maior exchange da América Latina, que possui milhões de usuários, tokenizou muita coisa. Antes, tokenizar era caro e complexo operacionalmente. Em parceria com a Stellar, lançamos duas soluções: o **MBRL** (uma stablecoin lastreada em real) e uma plataforma que permite gerenciar e tokenizar ativos digitais literalmente com **"cliques do mouse"**. Com essa plataforma, que é o **Stellar Asset Sandbox** (e é open source, viu?! Qualquer um pode usar para construir suas soluções), eles tokenizaram títulos do tesouro direto, fracionaram e venderam para quem quisesse comprar. Isso mostra o poder da tecnologia para simplificar processos complexos.



### O Que Vem Por Aí: O Futuro da Blockchain em 2025 e Além

Para finalizar, queria trazer algumas perspectivas para os próximos anos. A transição de "especulação para utilidade" vai continuar firme, e o foco será em **complementar** e melhorar o sistema financeiro existente, não em substituí-lo.


<img src="/img/blog/posts/edicao7/doug_maps.jpg" />

Pontos que considero cruciais para o futuro próximo:


*   **Continuidade da Tokenização de Ativos:** Veremos cada vez mais ativos sendo tokenizados, impulsionando a acessibilidade para todos.
*   **Integração com Sistemas Existentes:** A blockchain se tornará cada vez mais "invisível" no dia a dia, como no caso da MoneyGram, integrando-se de forma fluida aos serviços que já usamos.
*   **Avanços Regulatórios:** A clareza regulatória, especialmente em mercados como os EUA, desbloqueará um potencial enorme, pois grande parte do mercado financeiro global se movimenta por lá.
*   **Privacidade e Identidade:** Em blockchains públicas, onde tudo é visível, a privacidade é um desafio. Soluções que garantam a privacidade sem comprometer a identidade serão fundamentais. O Drex, no Brasil, já está abordando bastante essas discussões.
*   **Interoperabilidade (Bridges):** Hoje, as redes estão muito desconectadas. Se eu compro um ouro digital na Stellar, não consigo levá-lo facilmente para a Binance ou para uma carteira na Ethereum. Soluções que permitam a conexão entre diferentes blockchains, as "bridges", são uma grande área de oportunidade e desenvolvimento.
*   **Foco em Problemas Reais e Regionais:** A tecnologia blockchain precisa ser usada para resolver problemas concretos que as pessoas e empresas enfrentam no dia a dia, mesmo que sejam problemas locais.
*   **Melhor Uso, Não Melhor Blockchain:** Reforço a ideia de que não se trata de qual blockchain é "melhor" no geral, mas sim de qual é a ferramenta certa para o trabalho certo. Cada rede tem seu lugar e sua melhor aplicação.

A visão é de um mundo mais **inclusivo e eficiente**. A blockchain não é mais apenas uma palavra da moda, mas uma infraestrutura poderosa que está pavimentando o caminho para soluções inovadoras em 2025 e nos anos seguintes.
