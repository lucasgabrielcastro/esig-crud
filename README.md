# esig-crud
Projeto de seleção para estágio em desenvolvimento Java.<br/>

Aplicação desenvolvida utilizando JavaServer Faces (JSF), que permite cadastrar, atualizar, remover e mostrar registros.
Dados persistem em um banco de dados (MySQL).<br/>


A) Criação de Web App Utilizando JSF
  Aplicação Web criada seguindo as especificações; um programa CRUD com com um banco de dados para persistência de dados, e MySQL foi utilizado como banco de dados.

B) Persistência em banco de dados<br/>

G) Primefaces
  Alguns elementos da aplicação<br/>
  i.e. tabela e botões.


---------Instruções para rodar em um ambiente local--------------

1) DOWNLOADS
   1.1) Baixe este repositório em ZIP (esig-crud-master.zip), descompacte-o em um diretório qualquer<br/>
   1.2) Apache Tomcat 9.0 neste link https://tomcat.apache.org/download-90.cgi<br/>
   1.3) Eclipse IDE https://www.eclipse.org/downloads/<br/>
      1.3.1) Instale a versão para JavaEE do Eclipse.<br/>
   1.4) Baixe e Instale o MySQL Community Server e o MySQL Workbench<br/>
   1.5) Execute o servidor do MySQL e abra o MySQL Workbench<br/>
      1.5.1) No MySQL Workbench va em localhost e clique em File > Open SQL Script > selecione ambos os scripts na pasta
            sql-scripts na pasta do projeto e execute-os.<br/>
      
2) Execute o Eclipse IDE > File > Open Projects from File System<br/>
  2.1) na janela, ao lado do campo Import Source, clique em Directory, e procure onde esig-crud-master foi descompactado, e selecione a pasta. Após, clique em Finish<br/>
  2.2) No Project Explorer do Eclipse, clique com o botão direito do mouse e selecione New > Other > Server. Depois clique em Next.<br/>
    2.2.1) Selecione Tomcat v9.0 Server<br/>
    2.2.2) Adicione esig-crud-master a coluna CONFIGURED, depois FINISH.<br/>

    
3) No projeto selecione WebContent > index.html com o botão direito > Run As > Run on Server > Selecione a instância do Tomcat que foi criada nos passos 2.2 - 2.2.2<br/>

4) Um browser vai abrir no Eclipse, onde o aplicativo estará executando.<br/>

5) Após o passo 4, a aplicação estará acessível de qualquer browser, basta digitar http://localhost:8080/esig-crud-master/faces/list-students.xhtml

  <br/>
      
