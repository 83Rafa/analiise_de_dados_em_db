<h1 align='center'>Transformando dados em relatórios PDF  com Python e SQL</h1>
<div align='justyfy'>
  <p>Neste projeto foi possível explorar um pouco a praticidade do Python com banco de dados SQLite para transformar dados em relatórios em PDF muito úteis para auxiliar em tomadas de decisões. Tanto para analistas, proprietários de empresas ou apenas para quem quer criar relatórios com aparência profissional para uso próprio, este projeto segue um passo-a-passo do processo.</p>

  <p>O rimeiro passo é a configuração de um banco de dados SQLite. Depois, carregar dados de amostra usando Python. Em seguida, a criação de consultas SQL para extrair os dados necessários do banco de dados. Em seguida, usar o Pandas para manipular e transformar os dados criar gráficos interativos com o Plotly Express.</p>

  <p>Com os dados organizados, analizados e gerados insights de suas informações, pode-se utilizar a biblioteca <strong>FPDF</strong> para gerar um belo relatório em PDF.</p>
  <br>
</div>
<br>
<div align='center'>
  <h3 >Database Schema</h3>
  <img src="https://github.com/83Rafa/analiise_de_dados_em_db/blob/main/output/vendas_db_schema.png" width="600" alt="DB Schema">

  <h3>Demostrativo do documento PDF</h3>
  <img src="https://github.com/83Rafa/analise_de_dados_em_db/blob/main/output/report.png" width="600" alt="PDF Output">
</div>
<hr>
<div>
  <p>Requirements.txt</p>
  <ul>
    <li>numpy==1.22.4</li>
    <li>pandas==1.3.5</li>
    <li>kaleido==0.2.1</li>
    <li>fpdf==1.7.2</li>
    <li>plotly==5.5.0</li>
    <li>pathlib==1.0.1</li>
  </ul>
