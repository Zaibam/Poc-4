#  Poc-4


# Chamadas Asíncronas
- O que são elas: São casos onde o código permite com que múltiplas operações sejam executadas de forma concorrente, sem necessidade de que uma operação espere a finalização da anterior, tendo como alguns desses casos:

  •Operações de entrada e saída

  •Requisições de rede

  •Busca de dados

- Além disso, em relação as funções assíncronas, o javasctipt utiliza o conceito de Promises, que são literalmente promessas, criando ações para caso a promessa ocorra e também caso não ocorra
# O que É o Fetch?
O Fetch API é uma interface JavaScript moderna para fazer requisições HTTP/HTTPS de forma assíncrona. Essa API permite que os desenvolvedores criem aplicações web mais interativas e dinâmicas, oferecendo uma maneira mais intuitiva e fácil de realizar chamadas de rede.
  Além disso, a Fetch API fornece suporte para promessas, o que significa que os desenvolvedores podem usar o método then() para manipular a resposta da requisição e o método catch() para lidar com erros.
A API Fetch oferece uma variedade de métodos para personalizar uma requisição, como headers personalizados, tipos de dados, autenticação, entre outros. Por exemplo, um desenvolvedor pode usar o método fetch() para solicitar um arquivo JSON do servidor e, em seguida, usar o método then() para manipular os dados recebidos.
image
Nesse exemplo, é possível ver como a função fetch() é utilizada para fazer uma solicitação GET para a API pública de Pokémon (https://pokeapi.co/). Mais especificamente, a requisição busca informações sobre os primeiros 10 pokémons, definidos pelos parâmetros "offset" e "limit" na URL.
Assim que a requisição é concluída, a resposta é convertida em um objeto JavaScript usando o método json(), o que permite que os dados sejam manipulados no código da aplicação. Por fim, os dados são exibidos no console, permitindo que o desenvolvedor possa analisar a resposta da requisição e utilizar as informações obtidas em sua aplicação.
A Fetch API também permite que os desenvolvedores usem diferentes tipos de requisições HTTP, como GET, POST, PUT e DELETE. Além disso, a API oferece suporte a CORS (Cross-Origin Resource Sharing), o que significa que os desenvolvedores podem fazer solicitações entre domínios diferentes com segurança.
