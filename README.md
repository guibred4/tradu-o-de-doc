//  Este projeto tem como objetivo automatizar o processo de tradução de dados textuais em arquivos CSV para o idioma português, utilizando a API do Google Translate.
//  O script em Python realiza a leitura de um arquivo CSV contendo dados e traduz as colunas de texto de forma eficiente e assíncrona, aproveitando o poder do asyncio e aiohttp para realizar múltiplas requisições simultaneamente e otimizar o tempo de execução//.
//  O processo de tradução é feito em lotes, o que minimiza o risco de exceder os limites de requisição da API. Após a tradução, os dados são salvos em um arquivo Excel, facilitando o acesso e a manipulação dos resultados.

Principais funcionalidades:
Leitura de Arquivos CSV: O script carrega dados de arquivos CSV, permitindo trabalhar com grandes volumes de informação de forma eficiente.
Tradução em Lote Assíncrona: Utiliza a API do Google Translate para traduzir colunas de texto em lotes, otimizando o tempo de execução e respeitando os limites da API.
Saída em Excel: Após a tradução, os dados são salvos em formato Excel, um formato amplamente utilizado e de fácil manipulação.
Controle de Erros: Implementação robusta para lidar com falhas durante a tradução e salvar os dados corretamente.
Este projeto pode ser utilizado para qualquer tipo de dados que contenham texto em diferentes idiomas, permitindo traduções em larga escala para facilitar a análise de dados em diferentes mercados.

Por - Guilherme Fernandes
