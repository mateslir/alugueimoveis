# alugueimoveis
<h1>Aluguel de Imoveis</h1>
<h2>Feito por Mateus</h2>
    <p>O projeto tem o proposito de fazer o CLiente alugar seu imovel e tambem poder alugar um imovel de um outro cliente, podendo avaliar e reservar eles.</p>
     <h2>Tecnologias Utilizadas</h2>
    <ul>
        <li><strong>Java JDK 17</strong>: Linguagem de programação principal.</li>
        <li><strong>IntelliJ IDEA</strong>: IDE para desenvolvimento.</li>
        <li><strong>PostgreSQL</strong>: Banco de dados relacional.</li>
        <li><strong>Maven</strong>: Ferramenta de gerenciamento de dependências.</li>
        <li><strong>Spring Boot</strong>: Framework para criação de aplicativos Java.</li>
    </ul>
<h2>Endpoints Disponíveis</h2>
    <h3>Cliente</h3>
    <ul>
        <li><code>POST /api/cliente</code>: Cria um novo Cliente.</li>
        <li><code>GET /api/cliente/{id}</code>: Retorna um cliente específico pelo ID.</li>
    </ul>
    <h3>Imovel</h3>
        <li><code>POST /imoveis</code>: Cria um novo imovel.</li>
        <li><code>GET /imoveis</code>: Retorna todos os imovel .</li>
        <li><code>GET /imoveis/{estado}</code>: Retorna um imovel específico pelo estado.</li>
        <li><code>PUT /imoveis/{id}</code>: Atualiza um imovel existente.</li>
        <li><code>DELETE/imoveis/{id}</code>: Remove um imovel.</li>
    </ul>
    <h3>Reserva</h3>
        <li><code>POST /reservas</code>: Cria um novo imovel.</li>
        <li><code>GET /reservas/{id}</code>: Retorna uma reserva especifica pelo ID.</li>
        <li><code>PUT /reservas{id}</code>: Atualiza uma reserva existente.</li>
        <li><code>DELETE/reservas/{id}</code>: Remove uma reserva.</li>
    </ul>
    <h3>Avaliação</h3>
        <li><code>POST /avaliacoes</code>: Cria uma avaliação.</li>
        <li><code>GET /avaliacoes</code>: Gera todas as avaliações .</li>
        <li><code>GET /avaliacoes/imovel/{idImovel}</code>: Retorna as avaliações de um imovel específico</li>
        <li><code>PUT /avaliacoes/{id}</code>: Atualiza uma avaliação existente.</li>
        <li><code>DELETE/avaliacoes/{id}</code>: Remove uma avaliaçcao.</li>
    </ul>
    
    
    
