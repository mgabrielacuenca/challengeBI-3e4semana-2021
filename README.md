**<h1>Challenge de BI - 3ª e 4ª Semana - Alura</h1>**
<br>
<h2>Dashboard Financeiro</h2>
<p>A pessoa que gerencia o financeiro da Alura Store disponibilizou para a gente o banco de dados do financeiro, para fazermos nossas análises e verificarmos quais os lucros e os gastos da empresa e ajudá-los a tomarem decisões com base nas análises.</p>
<br>
<h2>Base de Dados</h2>
<p>A base de dados consiste em um banco de dados no MySQL com a seguinte estrutura:</p>

<p><b>Tabela Pedidos</b></p>
<ul>
<li>Data da compra
<li>ID pedido
<li>ID produto
<li>Quantidade
</ul>

<p><b>Tabela Produtos</b></p>
<ul>
<li>ID produto
<li>Categoria produto
<li>Preço
<li>Custos
</ul>

<p><b>Tabela Vendedores</b></p>
<ul>
<li>ID vendedor
<li>Vendedor
</ul>

<p><b>Tabela Notas Fiscais</b></p>
<ul>
<li>ID nota
<li>ID pedido
<li>ID vendedor
<li>ID pedido
<li>Imposto
<li>Valor venda
<li>Número da nota
<li>Frete
</ul>

<br>

<h1>Ferramentas Utilizadas no Projeto</h1>
<p>Foi utilizado o Power BI para o desenvolvimento do Dashboard e o Adobe Color para tornar o dashboard acessível a pessoas que possuem daltonismo</p>

<br>

<h1>Tratamento dos Dados</h1>
<p><b>Tabela Pedidos</b></p>
<ul>
<li>Alteração na tipagem dos dados, colocado a tipagem correta
</ul>

<p><b>Tabela Produtos</b></p>
<ul>
<li>Alteração na tipagem dos dados, colocado a tipagem correta
<li>Remoção do Underscore
<li>Primeira letra de cada palavra maiúscula na coluna 'categoria'
<li>Ajuste dos valores das colunas 'preço' e 'custos'
</ul>

<p><b>Tabela Vendedores</b></p>
<ul>
<li>Alteração na tipagem dos dados, colocado a tipagem correta
<li>Ajuste dos nomes dos vendedores
</ul>

<p><b>Tabela Notas Fiscais</b></p>
<ul>
<li>Alteração na tipagem dos dados, colocado a tipagem correta
<li>Ajuste dos valores das colunas 'imposto', 'valor venda' e 'frete'
<li>Ajuste de vendedores repetidos na coluna 'id_vendedor'
</ul>

<br>

<h1>Métricas</h1>
<ul>
<li>Custos
<li>Despesas
<li>Lucro
<li>Número de vendas
<li>Receita
</ul>

<br>

<h1>Relacionamentos</h1>

<ul>
<li>Pedidos(n) - (1)Produtos = muitos para um (n-1)
<li>Pedidos(1) - (1)Notas Fiscais = um para um (1-1)
<li>Vendedores(1) - (n)Notas Fiscais = um para muitos (1-n)
</ul>

<br>

<h1>Link do Dashboard</h1>
https://app.powerbi.com/view?r=eyJrIjoiMjVmMTljZGYtZDlmMy00NTMxLTkyYmQtZmRhYjliMGJiYTc0IiwidCI6Ijk0NjZmMmYwLTI4ZmQtNDYxMi04MjhkLTQ0YzdlNzU4MDA3OCJ9
