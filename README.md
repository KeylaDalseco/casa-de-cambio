Casa de Câmbio
O projeto da casa de câmbio é uma aplicação que busca a conversão da taxa de uma moeda para diversas outras. O projeto foi uma uma proposta passada pela Trybe..

Requisitos:

1. Ambiente do Projeto
Criar um repositório do zero ou fazer um fork desse repositório (fique à vontade para fazer PRs quando terminar o desenvolvimento).
Iniciar projeto com NPM.
Estruturar o projeto para usar ESModules (usar typecomo modulenão package.jsone nas tags script).
Instale o Vite como Dev Tool e npm run dev.

2. Estrutura da Aplicação
Estruturar o HTML de acordo com o protótipo .
Crie tags semânticas no HTML.

3. Interação com API
O endpoint da API que deve ser usado é https://api.exchangerate.host/latest?base=${moeda}.
A moeda a ser pesquisada deve ser passada como o parâmetro moedado endpoint .
Todas as moedas devem ser listadas na tela.


4. Tratamento de Erro
Você deve usar o Sweet Alert 2 para as mensagens de erro.
Um erro deve aparecer quando nenhuma moeda é passada.
Um erro deve aparecer quando uma moeda inexistente é passada.
