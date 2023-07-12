# Projeto Automação Web

### Objetivo
Construir um projeto que automatize extração de informações da web sobre produtos que está interessado em comparar e precisa comparar o preço entre fornecedores.

### Créditos e inspirações
Este projeto foi desenvolvido no curso "Python Impressionador" coordenado e ministardo por João Paulo Lira da empresa Hashtag.

### Tecnologia
Python.

### Sobre o projeto
Serão extraídas da web as informações dos produtos de interesse de compra executando os passos abaixo. Será utilizado o Selenium.
- procurar no Google Shopping cada produto que há na base de dados "buscas", pegar todos os resultados que estejam dentro da faixa de preço e possuam o nome correto.
- procurar no Buscapé cada produto que há na base de dados "buscas" , pegar todos os resultados que estejam dentro da faixa de preço e possuam o nome correto.
- salvar o nome dos produtos, preço e link de compra do site do fornecedor em um dataframe (tabela).
- enviar um e-mail com a lista, preço e link de compra dos produtos encontrados no corpo do e-mail.

Exemplo de e-mail:

![email](https://github.com/FernandaDamaceno/Imagens/blob/f738f4f275f44d3017186722df6805e4526561b7/Automacao_Web/email.png)


Sobre a base de dados, há uma base de dados chamada "buscas". A base apresenta os seguintes campos:
- nome: nome dos produtos que serão buscados na web.
- termos banidos: termos que deverão ser evitados nos resultados das buscas na web.
- preço mínimo: preço limite definido para buscar os produtos na web.
- preço máximo: preço limite definido para buscar os produtos na web.
