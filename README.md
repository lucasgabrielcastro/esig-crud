# esig-crud
Projeto de seleção para estágio em desenvolvimento Java.

Aplicação desenvolvida utilizando JavaServer Faces (JSF), que permite cadastrar, atualizar, remover e mostrar registros.
Dados persistem em um banco de dados (MySQL).


A) Criação de Web App Utilizando JSF
  Aplicação Web criada seguindo as especificações; um programa CRUD com com um banco de dados para persistência de dados.
  
  MySQL foi utilizado como banco de dados, 

B) Persistência em banco de dados

G) Primefaces
  Alguns elementos do PrimeFaces

J) Heroku


---------Instruções para rodar em um ambiente local--------------

1) DOWNLOADS
   1.1) Baixe este repositório em ZIP (esig-crud-master.zip), descompacte-o em um diretório qualquer
   1.2) Apache Tomcat 9.0 neste link https://tomcat.apache.org/download-90.cgi
   1.3) Eclipse IDE https://www.eclipse.org/downloads/
      1.3.1) Instale a versão para JavaEE do Eclipse.
   1.4) Baixe e Instale o MySQL Community Server e o MySQL Workbench
   1.5) Execute o servidor do MySQL e abra o MySQL Workbench
      1.5.1) No MySQL Workbench va em localhost e clique em File > Open SQL Script > selecione ambos os scripts na pasta
            sql-scripts na pasta do projeto e execute-os.
      
2) Execute o Eclipse IDE > File > Open Projects from File System
  2.1) na janela, ao lado do campo Import Source, clique em Directory, e procure onde esig-crud-master foi descompactado, e selecione a pasta. Após, clique em Finish
  2.2) No Project Explorer do Eclipse, clique com o botão direito do mouse e selecione New > Other > Server. Depois clique em Next.
    2.2.1) Selecione Tomcat v9.0 Server
    2.2.2) Adicione esig-crud-master a coluna CONFIGURED, depois FINISH.

    
3) No projeto selecione WebContent > index.html com o botão direito > Run As > Run on Server > Selecione a instância do Tomcat que foi criada nos passos 2.2 - 2.2.2

4) Um browser vai abrir no Eclipse, onde o aplicativo estará executando.

5) Após o passo 4, a aplicação estará acessível de qualquer browser, basta digitar localhost:8080

  
      
