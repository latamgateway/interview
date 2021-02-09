### API Consulta CEP

Elaborar uma API REST que retorne os dados de um endereço conforme o CEP informado. Considere que essa API terá um alto volume de acesso.

#### Requisitos
- Linguagem utilizada: Ruby.
- Endpoint para gerar token a partir de um email e senha.
- Endpoint busca o cep e retorna: endereço, bairro, cidade, UF e o endereço completo.
- Salvar os ceps e endereços no banco de dados vinculando o endereço com o usuário que solicitou a consulta

#### O que será avaliado
- Organização do código
- Testes
- **Preocupação com performance**

#### Observações
- Não é necessário elaborar o cadastro do usuário, um seed com a criação do usuário já é o suficiente.
- Utilize qualquer serviço de cep que preferir. Existe o http://cep.la caso não conheça nenhum.
- Subir o projeto em um repositório no Github.
- Caso tenha dúvidas fique à vontade para perguntar.
- README explicando como instalar e rodar sua aplicação.