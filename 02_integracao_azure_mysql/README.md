<hr>
<h1>Projeto 002 - Importação de dados, Transformação e Visualização de Dados da Microsoft Azure (Banco de dados MySQL) - "Relatório Criativo" &#x1F60E;</h1>
<p>Olá à todos! Este projeto baseia-se em uma banco de dados MySQL dentro de um ambiente Clound (Microsoft Azure) onde, foram importados para o Microsoft Power BI e realizado todo o processamento de dados, como manipulação, transformação e carregamento das informações para que, seja elaborada o relatório dos dados para a posterior tomada de decisão</p>
<hr>
<p>Desafio proposto na plataforma DIO</p>
<hr>
<p><a href="https://app.powerbi.com/links/kjZlM53RpM?ctid=38ae2f02-5710-4e12-80bb-83600c3fdf1e&pbi_source=linkShare">Clique aqui</a> para visualizar o relatório pelo Power BI Web.
<hr>
<ul>
  <h2>Etapas realizadas:</h2>
  <li>Criação de uma instância na Microsoft Azure;</li>
  <li>Criação de um Banco de Dados com base disponível no GitHub;</li>
  <li>Integração do Power BI com MySQL na Microsoft Azure;</li>
  <li>Verificar Problemas na base a fim de realizar a transformação dos dados no Power Query;</li>
  <ul>
    <h3>Transformação de dados:</h3>
    <li>Verificar os cabeçalhos e tipos de dados;</li>
    <li>Modificar os valores monetários para o tipo double preciso;</li>
    <li>Verificar existência de nulos e analisar a remoção;</li>
    <li>Os dados Employees com nulos em Super_ssn podem ser os gerentes;</li>
    <li>Verificar se algum colaborador está sem gerente;</li>
    <li>Verificar se há algum departamento sem gerente;</li>
    <li>Se houver departamento sem gerente, analisar e preencher as lacunas faltantes;</li>
    <li>Verificar o número de horas de cada projeto;</li>
    <li>Separar colunas complexas;</li>
    <li>Mesclar consultas Employee e Departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá base a tabela Employee;</li>
    <li>Eliminar colunas desnecessárias.</li>
    <li>Realização de junção dos colaboradores e respectivos nomes dos gerentes (Mesclagem no Power BI ou via consulta SQL);</li>
    <li>Mesclar colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores;</li>
    <li>Mesclar os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. (Isso irá ajudar na criação do modelo estrela em módulos futuros).</li>
    <li>Explicar o por quê, neste caso, podemos apenas utilizar o mesclar e não o atribuir;</li>
    <li>Agrupar os dados a fim de saber quantos colaboradores existem por gerente;</li>
    <li>Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela.</li>
  </ul><br>
  <li>Criar o relatório para visualização acertiva dos dados.</li>
</ul>
<hr>
<img src="\projeto-dio-azure.gif">
<hr>
<br>
<p>À medida que estarei desenvolvendo projetos mais complexos estarei compartilhando com vocês neste repositório dedicado.</p>
<p>Estou totalmente aberto à <em>feedbacks</em> sobre visualização de dados em <strong>Power BI</strong>! &#x1F601;</p>
<p>Obrigado à todos e tenham um ótimo dia!</p>
<hr>
