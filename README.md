<h1 align="left">Relatório do Projeto: Gerador de QR Code</h1>

###

<h2 align="left">Introdução</h2>

###

<p align="left">Este projeto é um Gerador de QR Code, desenvolvido utilizando HTML, CSS e JavaScript. Seu objetivo é permitir que usuários criem QR Codes personalizados de forma simples e rápida, inserindo URLs ou textos em um campo de entrada. A ferramenta é prática, responsiva e intuitiva, oferecendo uma experiência amigável tanto para dispositivos móveis quanto para desktops.</p>

###

<h2 align="left">Desenvolvimento</h2>

###

<h3 align="left">Estrutura do Projeto</h3>

###

<p align="left">HTML: Define a estrutura do projeto, incluindo o cabeçalho com título e descrição, campo de entrada para o texto/URL e área para exibição do QR Code.<br>CSS: Estiliza o projeto, garantindo uma interface atraente e responsiva. Inclui:<br>Cores vibrantes: Fundo verde com contrastes em branco e laranja.<br>Transições suaves: Elementos que mudam de estado com animações fluídas.<br>Design centralizado: Foco no alinhamento central para facilitar a navegação.<br>JavaScript: Adiciona interatividade ao projeto. Funcionalidades incluem:<br>Geração do QR Code: Conexão com uma API para criar QR Codes com base na entrada do usuário.<br>Feedback visual: Botões e áreas de exibição mudam de estado para indicar progresso e resultados.<br>Tratamento de eventos: Respostas às ações do usuário, como cliques e pressionamento de teclas.</p>

###

<h3 align="left">Funcionamento</h3>

###

<p align="left">Entrada de Dados: O usuário insere uma URL ou texto no campo de entrada.<br>Geração do QR Code: Ao clicar no botão, o JavaScript envia os dados para a API https://api.qrserver.com/v1/create-qr-code/, que retorna o QR Code correspondente.<br>Exibição: A imagem do QR Code gerada é exibida em uma área designada, com feedback visual para o usuário.<br>Limpeza Automática: Se o campo de entrada for apagado, a área de exibição é automaticamente ocultada, e o botão retorna ao estado inicial.</p>

###

<h3 align="left">Tecnologias Utilizadas</h3>

###

<p align="left">HTML5: Para estruturação semântica.<br>CSS3: Para estilização e responsividade.<br>JavaScript Vanilla: Para lógica e interatividade.<br>API externa: https://api.qrserver.com/ para geração dos QR Codes.</p>

###

<h2 align="left">Conclusão</h2>

###

<p align="left">O projeto Gerador de QR Code é uma aplicação web funcional, visualmente agradável e eficiente, que pode ser utilizada em diversas situações do dia a dia, como geração de links compartilháveis e digitalização de textos. Sua implementação exemplifica boas práticas em desenvolvimento front-end, com uso de APIs para integração e um design responsivo.<br><br>O código está organizado e segue princípios de usabilidade e acessibilidade, podendo ser facilmente expandido para incluir novas funcionalidades, como personalização de tamanhos e cores dos QR Codes. Este projeto é ideal tanto como ferramenta prática quanto como exemplo de aprendizado para desenvolvedores front-end iniciantes e intermediários.</p>

###
