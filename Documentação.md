Avaliação Regimental P1 

Tecnologias e Programação Integrada

Bruno Agoston de Assis



1. O Problema estudado

Durante a reflexão sobre qual seria o problema iria desenvolver a solução, me veio à cabeça como funciona o pedido de alimentos por entrega nos dias de hoje, temos no geral apenas uma opção caso não seja proprietária, que seria o IFood.

`	`Visto isso, pensei em desenvolver um site onde constaria o cardápio do estabelecimento, algumas informações do restaurante, review e que fosse possível fazer o pedido.



1. O Objetivo

`	`Analisando a problemática,  surgiu o site na qual foi desenvolvido para disciplina constando todos os pré requisitos solicitados. Com o objetivo de disponibilizar de maneira mais acessível um site para pequenos restaurantes fugirem das taxas abusivas que são cobradas nessas empresas intermediárias.

`	`De fácil utilização desde a instalação, até a manutenção, este site já traz tudo que seria necessário para o próprio restaurante gerenciá-lo, trazendo o site e também uma parte de administração, onde é possível verificar os pedidos, usuários cadastros, adicionar e remover produtos e até adicionar novos administradores.



1. Documentação

- Inicialmente será necessário instalar o XAMPP (<https://sourceforge.net/projects/xampp/>), que será o servidor para rodarmos o site em PHP e o banco de dados utilizado que é o MySQL.
- Após o XAMPP está instalado, pegar os arquivos que estão dentro da pasta **site** e colocar na pasta htdocs dentro da pasta de instalação do XAMPP que por padrão é: C:\xampp\htdocs\
- Com os arquivos já alocados, devemos abrir o XAMPP e executar o servidor Apache e o servidor MySQL que deverá ficar semelhante a imagem abaixo.





![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.001.png)

- Com os dois servidores “running” ou seja em execução, o que demonstra a cor verde em seus nomes, será necessário criar o banco de dados para importarmos o SCHEME já criado e disponibilizado em forma de arquivo dentro da pasta **Site** com o nome de **food\_db.** Para isto , devemos clicar no botão Admin do MySQL e seremos direcionados para a página de administrador do nosso servidor de banco de dados.
- Após estarmos com o Admin do MySQL aberto, devemos clicar em novo no canto esquerdo

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.002.png)
















- Assim, devemos inserir o nome do nosso banco (food\_db) e apertar em criar. É necessário que o nome do banco seja o sugerido, se não, haverá necessidade de alterar algumas informações no código desenvolvido.

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.003.png)

- Com o banco criado, você será direcionado diretamente a ele após a criação e ele já estará selecionado. É só clicar em importar no menu superior 

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.004.png)

- Nesta parte devemos selecionar o arquivo food\_db.sql que está dentro da pasta do site que já foi movida para htdocs e clicar em importar. Se todos os passos foram feitos de maneira correta, nosso banco de dados está pronto.










![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.005.png)




























- Assim, com o site na pasta htdocs e o nosso banco de dados importado é só acessar o localhost que o site será aberto.


1. Resultados

`	`Analisando os resultados obtidos, eu considero que foi um resultado satisfatório, consegui chegar ao objetivo que era criar um site com manutenção de produtos e usuários de maneira simples. Abaixo segue o print de algumas páginas do site.







**Home**

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.006.png)

**Cardápio**

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.007.png),

Página de Cadastro e Login

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.008.png)

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.009.png)

Login ADMIN (localhost/admin/admin\_login.php)

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.010.png)

Dashboard Admin

![](Aspose.Words.cc51b3e6-e3e2-49b8-88cc-41da08b2b795.011.png)


1. Vídeo apresentação

`	`Segue o link da apresentação do site por completo: <https://youtu.be/vimYO46zWVw>
