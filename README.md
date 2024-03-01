# BiteFit
Projeto utilizado para apresentação do 18° Congresso da faculdade Fundação Hermínio Ometto (FHO-Uniararas).

Esse projeto não propõem nenhum tipo de venda, apenas para fins de estudo e pesquisa.

Realiazado em colaboração com https://github.com/layssahillary, https://github.com/marcelocorbon, https://github.com/IsabeleRenovato, https://github.com/HugoLima-590.

Linguagens utilizadas:

- HTML
- CSS
- PHP
- MySQL
- JavaScript

Funcionalidades do projeto:

- Cadastro de pacientes: permite que nutricionistas cadastrem novos pacientes informando nome, data de nascimento, altura e peso.
- Lista de pacientes: exibe a lista de pacientes cadastrados e permite que o nutricionista acesse o perfil de cada paciente para visualizar as informações cadastradas e editar ou excluir o paciente.
- Perfil do paciente: exibe as informações cadastradas de um paciente específico e permite que o nutricionista edite ou exclua o paciente.
- Login: página de login para acesso ao sistema por parte dos nutricionistas.

- Agendamento de consultas;
- Cálculos nutricionais;
- Cadastro de dietas saudáveis;
- Logout: botão para sair do sistema;

  
Instruções de instalação:

- Baixe o arquivo zip do projeto e extraia os arquivos para o diretório raiz do servidor web (por exemplo, htdocs/ para o XAMPP).
- Importe o arquivo "banco.sql" para criar a tabela "pacientes" no banco de dados.
- Configure as credenciais de acesso ao banco de dados no arquivo "conexao.php".
- Abra o navegador e acesse o endereço do servidor web (por exemplo, http://localhost/).
- Faça login com as credenciais de nutricionista para acessar o sistema.
- Para utilizar o ChatBite (API do Chat OpenAI) é preciso criar uma Key no site https://platform.openai.com/account/api-keys e colocar essa Key em request.php antes de iniciar, lembrando que essa API é limitada, e pedir uma requisição muito alta pode diminuir a sua velocidade de resposta e também criar falhas de resposta, tente utilizar requisitos curtos.
