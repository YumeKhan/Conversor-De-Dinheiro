# Conversor De Dinheiro

Resumo do que foi Criado.

O código HTML define uma página da web que apresenta um conversor de moedas. A página possui um formulário com campos para entrada de quantia, seleção da moeda de origem e destino, além de um botão para obter a taxa de câmbio. O JavaScript interage com o HTML para preencher as seleções de moeda com opções, exibir bandeiras correspondentes às moedas selecionadas e realizar a conversão de moeda com base na taxa de câmbio obtida de uma API.

O código JavaScript faz o seguinte:

Seleciona os elementos relevantes do HTML, como seleções de moeda, botões, campos de entrada e elementos de exibição de resultados.

Preenche as seleções de moeda com opções usando um loop que itera pelas moedas disponíveis no objeto Country_List. A moeda de origem (USD) e a moeda de destino (BRL) são pré-selecionadas.

Define um manipulador de evento para atualizar a bandeira da moeda sempre que uma seleção de moeda é alterada. Isso é feito alterando o atributo src da tag img correspondente.

Define uma função assíncrona getExchangeRate() para obter a taxa de câmbio da API exchangerate-api.com. A função extrai a taxa de câmbio da resposta e calcula a conversão da quantia de uma moeda para outra.

Define manipuladores de eventos para carregar a taxa de câmbio quando a página é carregada, quando o botão é clicado e quando o ícone de troca de moeda é clicado. Ao clicar no ícone de troca, as moedas de origem e destino são trocadas, e a taxa de câmbio é recalculada.

No geral, os códigos criam uma página da web interativa que permite aos usuários converter quantias de uma moeda para outra com base nas taxas de câmbio em tempo real. O JavaScript é usado para manipular as interações do usuário e fazer solicitações a uma API para obter as taxas de câmbio.
