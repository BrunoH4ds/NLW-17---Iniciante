# Gerenciador de Metas

Este é um simples aplicativo de linha de comando para gerenciar metas, desenvolvido em JavaScript utilizando Node.js e a biblioteca @inquirer/prompts para interação com o usuário.

# Funcionalidades

- Cadastrar Metas: Adicione novas metas à sua lista.
- Listar Metas: Visualize suas metas e marque-as como concluídas.
- Metas Realizadas: Visualize as metas que já foram concluídas.
- Metas Abertas: Veja as metas que ainda precisam ser concluídas.
- Deletar Metas: Exclua metas da sua lista.
- Persistência de Dados: As metas são salvas em um arquivo metas.json para que você possa continuar de onde parou.

# Requisitos

Node.js (versão 14 ou superior)
Biblioteca @inquirer/prompts

# Instalação

Clone este repositório:
git clone https://github.com/seu-usuario/gerenciador-de-metas.git
Navegue até o diretório do projeto:
cd gerenciador-de-metas
Instale as dependências:
npm install
Como Usar
Execute o aplicativo no terminal:
node index.js

# Interaja com o menu principal use (enter) para entrar na interface e sair (espaco) para selecionar:

- Cadastrar meta: Insira uma nova meta.
- Listar metas: Veja todas as metas e marque as concluídas.
- Metas realizadas: Mostra apenas as metas já concluídas.
- Metas abertas: Mostra apenas as metas que ainda estão em aberto.
- Deletar metas: Selecione metas para excluir.
- Sair: Encerra o aplicativo.
As metas serão salvas automaticamente em metas.json.

# Exemplo de Uso

Menu >
  - Cadastrar meta
  - Listar metas
  - Metas realizadas
  - Metas abertas
  - Deletar metas
  - Sair

# Estrutura do Projeto
index.js: Contém toda a lógica do aplicativo.
metas.json: Armazena as metas cadastradas e suas respectivas informações.
Contribuição
Contribuições são bem-vindas! Se você encontrar algum bug ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.
