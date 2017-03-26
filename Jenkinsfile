pipeline {
  agent any
  stages {
    stage ('Programming') {
      steps {
        echo """Languages :
     Java, Groovy, Scala, HTML/CSS/JavaScript...
Libraries & Framework :
     Java EE, Hibernate, ElasticSearch, GWT, Angular, Dropwizard, JUnit4 / 5
Servers :
     Wildfly/JBoss EAP, Tomcat, TomEE, Apache HTTPd, Nginx
     """
      }
    }
    stage ('Build & Automation') {
      steps {
        echo """Jenkins (Pipeline, Job DSL plugin,...)
Maven, SonarQube, Nexus
Docker, Vagrant"""
      }
    }
    stage ("Source Control Management") {
      steps {
        echo """Git, GitHub, Gerrit
Subversion"""
      }
    }
    stage ('System') {
        steps {
          echo """Linux (Fedora/RHEL)
Windows"""
        }
    }
  }
}
