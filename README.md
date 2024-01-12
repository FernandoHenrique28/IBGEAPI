Este script em Python fornece um cliente simples para interagir com a API do IBGE (Instituto Brasileiro de Geografia e Estatística). Ele inclui funcionalidades para obter rankings de nomes com base em dados censitários no endereço: https://servicodados.ibge.gov.br/api/docs/.

Este projeto foi construído para aprender os conceitos de API, orientação a objetos e sobretudo aprender sobre o módulo requests.

Você pode acessar a API do ibge utilizando esse script através de um terminal, normalmente eu utlizo o terminal do vs code.


No terminal você pode procurar a frequencia que um nome determinado tem. 

Exemplo de uso: 

````
python main.py --nome Fernando Henrique --localidade 12 --sexo M
````

Para obter uma frequência geral dos nomes, basta execultar o arquivo main.