<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Currículum Vitae - Vanderli Marques dos Reis</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body { 
      font-family: 'Merriweather', serif;
    }
    @media print {
      .no-print {
        display: none !important;
      }
      body {
        background-color: white;
        padding: 0;
      }
      .max-w-3xl {
        box-shadow: none !important;
        margin: 0 !important;
        max-width: 100% !important;
      }
    }
    .btn-action {
      display: inline-block;
      font-family: 'Merriweather', serif;
      background-color: #1E3A8A;
      color: #FFFFFF !important;
      padding: 0.5rem 1.5rem;
      border-radius: 0.375rem;
      font-size: 0.9rem;
      font-weight: 600;
      text-decoration: none;
      transition: background-color 0.3s ease;
      border: none;
      cursor: pointer;
    }
    .btn-action:hover {
      background-color: #1E40AF; 
    }
  </style>
</head>

<body class="bg-gray-50 leading-relaxed tracking-normal p-4 md:p-10">

  <div class="max-w-3xl mx-auto bg-white shadow-md rounded-lg overflow-hidden border border-gray-200">

    <!-- HEADER CORRIGIDO - AZUL EM VEZ DE VERDE -->
    <header class="bg-blue-50 border-b border-blue-100 p-6 md:p-8 flex flex-col md:flex-row items-center gap-6 md:gap-8">
      
      <div class="flex-shrink-0">
        <img src="img/foto_vanderli.png" alt="Vanderli Reis" class="w-32 h-40 md:w-36 md:h-44 object-cover rounded-lg border-2 border-blue-200 shadow-sm bg-white">
      </div>

      <div class="text-center md:text-left flex-1">
        <h1 class="text-2xl md:text-3xl font-bold text-blue-900 uppercase">Vanderli Marques dos Reis</h1>
        <p class="text-sm text-blue-700 mt-2 font-semibold">
          CFT/DF
          <a href="https://cft.org.br/" target="_blank" class="text-blue-800 hover:underline ml-2">
            <span>Consultar</span>
          </a>
        </p>

        <div class="mt-4 text-sm text-blue-800 space-y-1">
          <p class="flex items-center justify-center md:justify-start gap-2">
            <span>📧</span>
            <span>vanderlitecnologia@gmail.com</span>
          </p>
          <p class="flex items-center justify-center md:justify-start gap-2">
            <span>📞</span>
            <a href="https://wa.me/5561986516466" target="_blank" class="text-blue-800 hover:underline">
              💬 +55 (61) 98651-6466 (WhatsApp)
            </a>
          </p>
          <p class="flex items-center justify-center md:justify-start gap-2">
            <span>📍</span>
            <span>Taguatinga Norte - Brasília - DF</span>
          </p>
        </div>
      </div>
    </header>

    <div class="p-6 md:p-8 space-y-6 md:space-y-8">

      <section>
        <h2 class="text-lg md:text-xl font-bold text-blue-900 border-b-2 border-blue-900 pb-1 mb-3">Objetivo</h2>
        <p class="text-gray-700 text-sm">Atuar como Desenvolvedor Java, demais conhecimentos podendo ser atendido para Tecnologia.</p>
      </section>

      <section>
        <h2 class="text-lg md:text-xl font-bold text-blue-900 border-b-2 border-blue-900 pb-1 mb-3">Especializações Adquiridas</h2>
        <ul class="flex flex-wrap gap-3 md:grid md:grid-cols-2 text-gray-700 text-sm list-disc pl-5 md:pl-0 md:list-inside">
          <li class="flex-1 min-w-[250px]">Técnico em Desenvolvimento de Sistemas 2025/cursando – SENAC</li>
          <li class="flex-1 min-w-[250px]">Certificate CISCO Engaging Stakeholders for Success - 2025</li>
          <li class="flex-1 min-w-[250px]">Certificado Introdução à IoT e à Transformação Digital - 2025</li>
          <li class="flex-1 min-w-[250px]">Administrador de Banco de Dados – SENAC 2022</li>
          <li class="flex-1 min-w-[250px]">Microsoft Power Bi Avançado – SENAC 2021</li>
          <li class="flex-1 min-w-[250px]">Bacharel em Sistemas de Informação – Centro Universitário Rib. Preto-SP-2020</li>
          <li class="flex-1 min-w-[250px]">Técnico de Manutenção em Microinformática – SENAI – 1999/2001 – CFT-DF</li>
        </ul>
      </section>

     <section>
    <h2 class="text-lg md:text-xl font-bold text-blue-900 border-b-2 border-blue-900 pb-1 mb-3">Experiência Profissional</h2>
    
    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">Senac Fecomércio Sesc – Taguatinga Norte</h3>
            <span class="text-sm font-medium text-cyan-600 bg-cyan-50 px-3 py-1 rounded-full border border-cyan-200 self-start md:self-center">
              Estágio desde julho/2025
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Estagiário Gestão Tecnologia da Informação – GTI - Apoio</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Atendimento a instrutores, contabilidade, coordenação e secretaria</li>
            <li>Instalação de aplicativos e imagem de sistema nos laboratórios</li>
            <li>Entrega e configuração de notebooks para instrutores</li>
            <li>Interação em sistemas e gerenciamento de acesso para alunos</li>
            <li>Suporte à infraestrutura de TI e demais serviços inerentes</li>
        </ul>
    </div>
     
    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">Editora Edebe Brasil LTDA</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                2016 - 2023
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Assistente de Tecnologia I</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Suporte para colaboradores em Sistemas MacOsX e Windows</li>
            <li>Pacote Office e aplicações corporativas</li>
            <li>Manutenção preventiva e corretiva em equipamentos</li>
            <li>Atendimento a iMac, Notebook, Desktop, Macbook e Minimac</li>
        </ul>
    </div>

    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">CIS Brasil Conferência das Inspetorias Salesianas</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                2014 - 2015
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Analista de Suporte I</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Suporte para colaboradores em Sistemas MacOsX e Windows</li>
            <li>Suporte a Pacote Office e aplicações corporativas</li>
            <li>Manutenção preventiva e corretiva em equipamentos Apple</li>
            <li>Atendimento a iMac, Notebook, Desktop, MacBook e MiniMac</li>
        </ul>
    </div>

    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">Stefanini Consultoria e Assessoria em Informática S.A</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                2012 - 2015
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Operador de Computador</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Monitoramento de sistemas e infraestrutura</li>
            <li>Encaminhamento e solução de chamados nível II</li>
            <li>Backup e restauração de dados</li>
            <li>Conformidade com procedimentos CASSI-DF</li>
            <li><em class="text-gray-500">Período noturno</em></li>
        </ul>
    </div>

    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">CSP Consultoria e Sistemas LTDA</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                2010 - 2012
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Técnico de Operação III</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Monitoramento de sistemas e infraestrutura</li>
            <li>Encaminhamento e solução de chamados nível II</li>
            <li>Backup e restauração de dados</li>
            <li>Conformidade com procedimentos do Tribunal Superior do Trabalho</li>
            <li><em class="text-gray-500">Período noturno</em></li>
        </ul>
    </div>

    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">Star do Brasil Informática LTDA</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                2008 - 2011
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Técnico de Suporte</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Autorizada IBM para prestação de serviços técnicos</li>
            <li>Manutenção, integração e configuração de equipamentos</li>
            <li>Atendimento a equipamentos da linha SystemX, BladeCenters e Storages</li>
        </ul>
    </div>

    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">NT-Service Tecnologia LTDA</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                2003 - 2008
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Técnico Manutenção Jr</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Autorizada HP para manutenção de equipamentos</li>
            <li>Suporte e configuração de computadores e periféricos</li>
            <li>Manutenção corretiva e preventiva</li>
        </ul>
    </div>

    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">Shalom – Sistemas de Processamento de Dados - SERPRO - L2Norte</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                2001 - 2003
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Técnico Eletrônica e PD</p>
        <ul class="mt-2 text-gray-700 text-sm list-disc pl-5 space-y-1">
            <li>Atendimento em suporte técnico de sistemas</li>
            <li>Manutenção de sistemas computacionais</li>
            <li>Suporte a infraestrutura de TI</li>
        </ul>
    </div>
</section>

<section class="mt-6">
    <h2 class="text-lg md:text-xl font-bold text-blue-900 border-b-2 border-blue-900 pb-1 mb-3">Carteira Nacional de Habilitação</h2>
    
    <div class="mb-6">
        <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-2 mb-3">
            <h3 class="text-base md:text-lg font-bold text-gray-800">CNH</h3>
            <span class="text-sm font-medium text-blue-600 bg-blue-50 px-3 py-1 rounded-full border border-blue-200 self-start md:self-center">
                Validade até 2033
            </span>
        </div>
        <p class="text-gray-600 font-medium mt-1">Categoria: <span class="font-bold">"B"</span></p>
    </div>
</section>

<section class="mt-6">
    <h2 class="text-lg md:text-xl font-bold text-blue-900 border-b-2 border-blue-900 pb-1 mb-3">Informações Adicionais</h2>
    
    <div class="mb-4">
        <h3 class="text-base md:text-lg font-bold text-gray-800 mb-3">Resumo das Qualificações</h3>
        <div class="text-gray-700 text-sm bg-gray-50 p-4 rounded-lg border border-gray-200">
            <p class="mb-3">Mais de 20 anos com sólidas experiências em diversas áreas em Tecnologia da Informação, mantendo constante busca por atualizações através de cursos online e presenciais, aprimorando conhecimentos e técnicas:</p>
            
            <ul class="list-disc pl-5 mb-3 space-y-1">
                <li>Inteligência Artificial (IA) e virtualização Azure e Aws;</li>
                <li>Programação e segurança da informação;</li>
                <li>Metodologias ágeis (Scrum), Jira;</li>
                <li>Participação em squads de Desenvolvimento de Software;</li>
                <li>Versionamento GitHub, prototipagem com Figma.</li>
            </ul>
            
            <p class="mb-3">Além das experiências descritas, possuo vasta capacidade de aprendizado, comprometimento e foco nas tarefas designadas. Adapto-me rapidamente a novos desafios e ambientes de trabalho.</p>
            
            <p class="font-medium text-gray-800 italic">Contando que os dados supracitados satisfaçam às expectativas desta empresa, desde já, me coloco à disposição para contribuir com minha experiência e dedicação.</p> 
        </div>
    </div>
</section>
      
      <div class="flex flex-col md:flex-row gap-4 no-print border-t pt-6 md:pt-8">
          <div class="bg-gray-100 border border-gray-300 p-4 rounded-lg text-center flex-1 flex flex-col items-center justify-center">
            <h2 class="text-md font-bold text-gray-800 mb-3">📄 Baixar PDF</h2>
            <a href="Curriculum-Vanderli.pdf" class="btn-action">⬇️ Download</a>
          </div>
          <div class="bg-gray-100 border border-gray-300 p-4 rounded-lg text-center flex-1 flex flex-col items-center justify-center">
            <h2 class="text-md font-bold text-gray-800 mb-3">🖨️ Imprimir</h2>
            <button onclick="window.print()" class="btn-action w-full md:w-auto">Gerar Impressão</button>
          </div>
      </div>

    </div>
  </div>
  
  <footer class="text-center mt-6 mb-10">
    <p class="text-[12px] text-gray-500">
      Currículum desenvolvido por vanderlinuxcode - 2026
    </p>
  </footer>

</body>
</html>