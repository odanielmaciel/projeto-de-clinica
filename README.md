# projeto-de-clinica
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Página Principal | Clínica Vida Plena</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f1f5f4; color: #222; }
    .container { max-width: 960px; margin: 0 auto; background: #fff; }
    nav { background: #0f766e; }
    nav ul { list-style: none; margin: 0; padding: 0; display: flex; flex-wrap: wrap; }
    nav a { display: block; padding: 16px 22px; color: #fff; text-decoration: none; font-weight: bold; }
    nav a:hover, nav a.ativo { background: #115e59; }
    header img { width: 100%; height: auto; display: block; }
    main { padding: 24px 32px; line-height: 1.6; }
    h1, h2 { color: #0f766e; }
    table { border-collapse: collapse; width: 100%; margin: 16px 0; }
    th, td { border: 1px solid #99c9c3; padding: 10px; text-align: center; }
    th { background: #0f766e; color: #fff; }
    tbody tr:nth-child(even) { background: #e6f4f2; }
    iframe { width: 100%; height: 320px; border: 0; }
    label { display: block; margin-top: 12px; font-weight: bold; }
    input[type=text], input[type=email], textarea { width: 100%; padding: 8px; box-sizing: border-box; }
    button { margin: 16px 8px 0 0; padding: 10px 22px; border: 0; background: #0f766e; color: #fff; cursor: pointer; }
    footer { background: #134e4a; color: #fff; padding: 18px 32px; font-size: 14px; line-height: 1.6; }
    footer a { color: #fff; }
  </style>
</head>
<body>
<div class="container">

  <!-- MENU -->
  <nav>
    <ul>
      <li><a href="index.html" class="ativo">Página Principal</a></li>
      <li><a href="sobre.html">Sobre a clínica</a></li>
      <li><a href="horarios.html">Horário de Atendimento</a></li>
      <li><a href="contato.html">Contato</a></li>
    </ul>
  </nav>

  <!-- HEADER -->
  <header>
    <img src="img/header-home.svg" alt="Fachada acolhedora da Clínica Vida Plena">
  </header>

  <!-- CONTENT -->
  <main>
    <h1>Bem-vindo à Clínica Vida Plena</h1>
    <p>A <strong>Clínica Vida Plena</strong> cuida da saúde de toda a família com <em>carinho, ética e tecnologia</em>. Estamos em Fortaleza, no coração do Meireles, com uma equipe multidisciplinar pronta para receber você.</p>
    <h2>Nossas especialidades</h2>
    <ul>
      <li>Clínica geral</li>
      <li>Psicologia</li>
      <li>Pediatria</li>
      <li>Oftalmologia</li>
    </ul>
    <p>Conheça <a href="sobre.html">nossa história</a>, veja os <a href="horarios.html">horários de atendimento</a> ou <a href="contato.html">entre em contato</a> para agendar sua consulta.</p>
  </main>

  <!-- FOOTER -->
  <footer>
    <strong>Clínica Vida Plena</strong><br>
    Av. Beira Mar, 1000 - Meireles, Fortaleza - CE, 60165-121<br>
    Tel.: <a href="tel:+558532001000">(85) 3200-1000</a> | WhatsApp: <a href="https://wa.me/5585999001000">(85) 99900-1000</a><br>
    E-mail: <a href="mailto:contato@vidaplena.com.br">contato@vidaplena.com.br</a><br>
    <small>&copy; 2026 Clínica Vida Plena. Todos os direitos reservados.</small>
  </footer>

</div>
</body>
</html>

<main>
    <h1>Sobre a clínica</h1>
    <p>Fundada em 2010, a <strong>Clínica Vida Plena</strong> nasceu com o propósito de oferecer atendimento médico humanizado e de qualidade, onde cada paciente é ouvido com atenção e tratado com respeito.</p>
    <p>Ao longo dos anos, ampliamos nossa estrutura e reunimos profissionais experientes nas áreas de clínica geral, psicologia, pediatria e oftalmologia, trabalhando de forma integrada para oferecer um cuidado completo.</p>
    <h2>Nossos valores</h2>
    <ol>
      <li>Acolhimento e escuta atenta</li>
      <li>Ética e transparência</li>
      <li>Excelência técnica</li>
      <li>Compromisso com a comunidade</li>
    </ol>
    <h2>Missão</h2>
    <p>Promover saúde e bem-estar, com atendimento <em>acessível, seguro e humano</em>, para pessoas de todas as idades.</p>
    <p>Quer nos conhecer pessoalmente? <a href="contato.html">Fale conosco</a>.</p>
</main>

<main>
    <h1>Horário de Atendimento</h1>
    <p>Oferecemos consultas nas quatro especialidades abaixo, com horários especiais aos sábados e feriados. Recomendamos agendar com antecedência pelo telefone ou WhatsApp.</p>
    <table>
      <caption><strong>Horários por serviço</strong></caption>
      <thead>
        <tr>
          <th>Serviços</th>
          <th>Segunda a Sexta</th>
          <th>Sábados</th>
          <th>Feriados</th>
        </tr>
      </thead>
      <tbody>
        <tr><td>Clínica geral</td><td>08h - 19h</td><td>08h - 14h</td><td>08h - 14h</td></tr>
        <tr><td>Psicologia</td><td>08h - 19h</td><td>08h - 14h</td><td>08h - 14h</td></tr>
        <tr><td>Pediatria</td><td>08h - 19h</td><td>08h - 18h</td><td>-</td></tr>
        <tr><td>Oftalmologia</td><td>08h - 19h</td><td>08h - 18h</td><td>-</td></tr>
      </tbody>
    </table>
    <p><small>O símbolo "-" indica que não há atendimento no período.</small></p>
</main>


<main>
    <h1>Contato</h1>
    <h2>Telefones</h2>
    <ul>
      <li>Celular: <a href="tel:+558532001000">(85) 3200-1000</a></li>
      <li>WhatsApp: <a href="https://wa.me/5585999001000">(85) 99900-1000</a></li>
    </ul>
    <h2>Endereço</h2>
    <address>
      Clínica Vida Plena<br>
      Av. Beira Mar, 1000 - Meireles<br>
      Fortaleza - CE, 60165-121
    </address>
    <h2>Como chegar</h2>
    <iframe src="https://www.google.com/maps?q=Av.+Beira+Mar,+1000,+Meireles,+Fortaleza,+CE&output=embed" title="Mapa da Clínica Vida Plena" loading="lazy" allowfullscreen></iframe>
    <h2>Envie uma mensagem</h2>
    <form action="#" method="post">
      <label for="nome">Nome</label>
      <input type="text" id="nome" name="nome" required>

      <label for="email">E-mail</label>
      <input type="email" id="email" name="email" required>

      <label for="assunto">Assunto</label>
      <input type="text" id="assunto" name="assunto" required>

      <label for="mensagem">Mensagem</label>
      <textarea id="mensagem" name="mensagem" rows="6" required></textarea>

      <button type="submit">Enviar</button>
      <button type="reset">Limpar formulário</button>
    </form>
</main>
