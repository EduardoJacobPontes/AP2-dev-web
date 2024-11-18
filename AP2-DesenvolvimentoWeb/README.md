p2-desweb-2024-2
P2 de desenvolvimento web

Objetivo
Reproduzir o comportamento da página de exemplo.

Restrições
CSS e Javascript devem ser em arquivos separados
É preciso usar armazenamento local para viabilizar a solução de autorização
A listagem de atletas e a página de detalhes só devem ser acessíveis a usuários autorizados 👀
A senha deve estar disponível na página de entrada (é só uma demonstração) 😌
A comparação entre as senhas deve usar um HASH sha256 calculado pela biblioteca da página do Paj
A página principal deve obter os elencos com chamadas, obrigatoriamente 👮, aos end-points:
https://botafogo-atletas.mange.li/2024-1/all
https://botafogo-atletas.mange.li/2024-1/masculino
https://botafogo-atletas.mange.li/2024-1/feminino
Sua página deve permitir filtrar a lista de atletas 🤨
Os dados da página de detalhes devem ser obtidos do end-point https://botafogo-atletas.mange.li/2024-1/{atleta-id}
A página de detalhes deve ser construída com a informação do id contida na URL ❗❗❗
Não deve ser possível acessar a página de detalhes sem autorização 🛑
Erros na obtenção dos dados para a construção da página de detalhes devem gerar uma mensagem na tela
O estilo das páginas e cartões é de livre escolha, use a criatividade e garanta que não é uma cópia 😜
Sua página deve usar fontes personalizadas 🦄
É obrigatório usar um favicon :octocat:
O trabalho deve ser publicado no githubPages com acesso público
não é obrigatório usar URL personalizada, mas se quiser pode 😎
Responsividade:
Página de Login:
vertical até 768px;
Página Detalhes:
vertical até 768px;
Container de atletas da Página Principal:
uma colunas até 768px;
três colunas até 1024px;
quatro colunas até de 1300px;
cinco colunas depois de 1300px
largura máxima da lista de 1400px;
Seleção de elenco da Página Principal:
select até 768px;
botões para viewports maiores que 768px;
Página de exemplo:
Sua solução deve estar publicada no githubPages e emular o compartamento da página: https://p2-2024-2-desweb.mange.li/
