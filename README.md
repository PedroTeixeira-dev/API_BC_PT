# A PI de Classificação de Câncer de Mama

## Esta API tem como objetivo fornecer endpoints para a inclusão, consulta e exclusão de dados de usuários. Além disso, ela será utilizada para classificar cânceres de mama com base nas informações fornecidas.

### Tecnologias Utilizadas:
Flask
SQLAlchemy
OpenAPI3
SQLite
### Instalação:
Para instalar a API, é necessário garantir que todas as bibliotecas Python listadas no arquivo requirements.txt estejam instaladas. Após clonar o repositório, acesse o diretório raiz pelo terminal para executar os comandos a seguir.

É altamente recomendável utilizar ambientes virtuais, como o virtualenv.

bash
Copiar código
(env)$ pip3 install -r requirements.txt
Esse comando instalará as dependências e bibliotecas especificadas no arquivo requirements.txt.

Executando o Servidor:
Para iniciar a API, basta executar o seguinte comando:

bash
Copiar código
(env)$ flask run --host 0.0.0.0 --port 5000
Durante o desenvolvimento, é recomendável usar o parâmetro --reload, que reiniciará automaticamente o servidor sempre que houver alterações no código fonte:

bash
Copiar código
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
Acesso no Navegador:
Para verificar o status da API em execução, abra o seguinte endereço no seu navegador: http://localhost:5000/#/