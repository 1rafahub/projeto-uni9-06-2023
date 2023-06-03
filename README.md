Para conseguir fazer o projeto rodar localmente em uma maquina virtual é necessário seguir os seguintes passos:

Criar uma maquina virtual : 

- python -m venv .venv

Ativa o ambiente da maquina virtual : 

- .\.venv\Scripts\Activate.ps1

 Atualizar o pip:
 
 - python  pip -m pip install --upgrade pip

 Fazer o download das bibliotecas e framworks utilizados no projeto:

 - pip install -r requirements.txt


Decidimos que o tema do projeto será um site que terceiriza a contratação de serviços residenciais, 
facilitando o contato entre os prestadores de serviços e os contratantes (pessoas que necessitam do serviço em específico ) 
Decidimos usar com base o projeto que o @Emanuel Anderson  mandou aqui no grupo ,gostamos da ideia de serviços de limpeza e 
tivemos a ideia de complementar isso, adicionando todo o tipo de serviço residencial, eletricista, faxina, contrução e etc. 

Tecnologia usada: 

Decidimos usar para a parte web / frontend:

Html
Css 
Bootstrap 

Para o backend decidimos usar :

Python 
Flask (framework de python) usado fazer a conexão entre o banco de dados e a página web ,   estruturar e tratar os dados que vem do banco de dados para que o usuário tenha uma melhor visualização.
