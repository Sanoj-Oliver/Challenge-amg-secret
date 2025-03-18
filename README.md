# Challenge-amg-secret
Challenge do amigo secreto.
O Amigo Secreto é uma aplicação simples que permite aos usuários inserir nomes de amigos em uma lista para, em seguida, realizar um sorteio aleatório e determinar quem é o "amigo secreto". A aplicação oferece uma interface simples onde os usuários podem adicionar amigos à lista, visualizar a lista e realizar o sorteio de forma interativa.

Este projeto foi desenvolvido com HTML, CSS e JavaScript para fins de aprendizado e entretenimento. A aplicação é totalmente funcional em um navegador web.

Funcionalidades
Adicionar Nomes: Os usuários podem adicionar amigos à lista através de um campo de texto e um botão "Adicionar".
Validar Entrada: O campo de nome não pode ser vazio. Caso esteja vazio, será exibido um alerta.
Visualizar Lista de Amigos: Todos os nomes inseridos são exibidos em uma lista na página.
Sortear Amigo Secreto: Um nome é selecionado aleatoriamente entre os amigos inseridos e exibido na página.
Tecnologias Utilizadas
HTML: Para estruturação da página.
CSS: Para estilização e design da interface.
JavaScript: Para implementar as funcionalidades interativas como adicionar amigos e realizar o sorteio.
Como Rodar o Projeto
Clone o repositório:

Se você ainda não fez o clone do repositório, execute o seguinte comando no seu terminal:

bash
Copiar
git clone <URL_DO_REPOSITORIO>
Instale as dependências:

Este projeto não possui dependências externas. Não é necessário instalar pacotes adicionais.

Abra o arquivo index.html:

Basta abrir o arquivo index.html no seu navegador de preferência. Caso queira uma experiência mais interativa, pode usar a extensão "Live Server" do VSCode para visualizar as alterações em tempo real.

Execute a aplicação:

Após abrir o index.html, você poderá adicionar nomes ao campo de entrada, visualizar a lista e realizar o sorteio de amigos secretos.

Estrutura do Projeto
index.html: Contém a estrutura HTML da página.
style.css: Contém os estilos da página para garantir uma boa experiência visual.
app.js: Contém a lógica da aplicação em JavaScript, como a funcionalidade de adicionar amigos e realizar o sorteio.
Como Contribuir
Clone o repositório:

Se você ainda não fez o clone do repositório, execute:

bash
Copiar
git clone <URL_DO_REPOSITORIO>
Crie uma branch para a sua contribuição:

bash
Copiar
git checkout -b nome-da-sua-branch
Faça as alterações no código.

Commit e Push:

bash
Copiar
git add .
git commit -m "Sua mensagem de commit"
git push origin nome-da-sua-branch
Crie um Pull Request com suas alterações.

Possíveis Problemas e Soluções
O sorteio não funciona:
Verifique se o campo de nomes não está vazio. O sorteio só será realizado quando houver pelo menos um nome na lista.
A lista de amigos não está sendo atualizada:
Certifique-se de que o nome foi corretamente adicionado ao array de amigos. Verifique o console do navegador para erros no JavaScript.
Licença
Este projeto é de uso livre e pode ser modificado conforme a necessidade. Não há uma licença específica associada a este projeto.
