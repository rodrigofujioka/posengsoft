# Engenharia de Software Arquitetura de Software e DevOps 

<a href="http://www.rodrigofujioka.com/" target="_blank"><img src="https://github.com/rodrigofujioka/javabasico/blob/master/resources/javaspion.png" alt="Javaspion" /></a>
</p>
     
Código de exemplo para práticas na pós de engenharia e qualidade de software

 Maven, JDK11, SpringBoot , SpringData. 


# Forma de enviar o projeto  

Titulo: [EngSoftANO]

* [EngSoftANO Swagger] :  Link para baixar
** Criar modelo com Swagger para o que foi solicitado em sala de aula. 

* [EngSoftANO Mensageria] :  Link para baixar
** Implementar projeto com utilização de Mensageria conforme exemplos em sala de aula ou no contexto da sua fábrica. 

* [EngSoftANO Docker] :  Link para baixar
** Criar imagem e publicar no dockerhub conforme conteúdo visto em sala de aula ou no contexto da sua fábrica. 

* [EngSoftANO SONARJENKINS] :  Link para baixar
** Preparar cenário utilizando Jenkins e Sonar no contexto do que foi visto em sala de aula. Pode usar docker-composer

* [EngSoftANO DAS] :  Link para baixar 
** Documento de Arquitetura de Software, no contexto da sua fábrica de software

* [EngSoftANO TDD_CLEAN_CODE] :  Link para baixar 
** Corrigir o código deste repositório, conforme as correções apontados pelo SONAR, Cobertura de código Testes Unitários deve ser superior a 70% 

## Ex: O modelo exato e para qual e-mail foi enviado para o representante de turma ou para o grupo da turma.
 


### RODAR SONAR
docker run --name sonar -it -p9000:9000 rodrigofujioka/sonar:7.9_lts

sudo su sonar

service sonar start

### RODAR JENKINS
docker run --name jenkins -it -p8080:8080 -p50000:50000 rodrigofujioka/jenkins:jdk11

service jenkins start   

fujioka

fujioka


* Meu instagram: [@rodrigofujioka](https://www.instagram.com/rodrigofujioka) 
* Meu facebook: [@rodrigofujioka](https://www.facebook.com/rodrigofujioka)

Repositório Java Básico : https://github.com/rodrigofujioka/poo
Repositório Programação Web: https://github.com/rodrigofujioka/papw 

- [Intellij Idea](https://www.jetbrains.com/idea/) 
- [Spring Tools](https://spring.io/tools)  
- [JDK](https://jdk.java.net/java-se-ri/11)

- ```Outras ferramentas como NetBeans ou VS Code podem ser utilizadas)```

## Cursos recomendados

#### GIT
- [GIT para iniciantes](https://www.udemy.com/git-e-github-para-iniciantes/)
- [GIT - DevMedia](https://www.devmedia.com.br/guia/git-e-github/37585)

#### Java
- [DevMedia - Java](https://www.devmedia.com.br/guia/programador-java/37809)
- [Loiane - Java](https://loiane.training/curso/java-basico)


## Preparação do ambiente


1 - Configurar o ambiente Java, na ordem informada. 

1.0 - Você pode fazer todas as configurações com o [SDKMAN](https://sdkman.io/) .

<p align="center">	
<a href="https://sdkman.io/" target="_blank"><img src="https://sdkman.io/assets/img/sdk-man-small-pattern.svg" alt="SDK MAN" width="350" height="350"/></a>	
</p>

1.1 - Baixar e instalar o JDK  -> 
         [Oracle JDK](https://www.oracle.com/technetwork/pt/java/javase/downloads/index.html)
         [Open JDK](https://openjdk.java.net/install/index.html)         

1.2 - Baixar e extrair binarios do Maven -> 
         [Maven](https://maven.apache.org/download.cgi)
         
1.3 - Configurar Classpath (Java e Maven) -> 



1.4 - Baixar e instalar ferramentas de desenvolvimento.

1.4.1 - Aulas ministradas com [Intellij Idea](https://www.jetbrains.com/idea/) Idea ou [Spring Tools](https://spring.io/tools)  .

1.4.2 - Pode ser utilizada qualquer outra ferramenta, no entanto, dúvidas sobre 
utilização apenas sobre as IDE's do itens #1.4.1

1.5 - Criar conta no github 
