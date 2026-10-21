# Documentação Flask

como instalar o uv
 use o comando:
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

Para configurar o uv use:
"uv init" cria uma estrutura inicial
"uv venv" cria uma pasta isolada

Para instalar uma versão no python use: "uv python install 15.0",  coloque a versão que você quer.

Para instalar o flask use: "uv add flask"

"uv run flask run",  esse código ele vai excutar o script utilizando o ambiente virtual automaticamente.


{% if nome %}
      <h1>Olá, {{nome}}!</h1>
 {% else %}
       <h1>Olá, Flask!</h1>
{%endif %}
 como funciona esse código HTML no python: no python utiliza o templates para processar variáveis e condições dentro do HTML antes de 
 enviar. 