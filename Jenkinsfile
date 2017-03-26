pipeline {
  agent any
  stages {
    stage ('SiteConseil') {
      steps {
        echo "Web developer (ASP / PHP)"
      }
    }
    stage ('Airbus France') {
      steps {
        echo """Technical Support on A380 Quality SAP Tools
Functional specifications of Quality Assurance SAP Tools
        """
      }
    }
    stage ('Infotel') {
      steps {
        echo """JavaEE Developer and Tech Lead of an up to 8 developers team
Initiated and maintained the Software Factory (Hudson then Jenkins, Sonar)
        """
      }
    }
    stage ('Mipih') {
        steps {
          parallel(
            'Nov. 15 🡒 Today' : {
              echo """Trying to improve everyday life of 50+ developers working on project PGIH (ERP)
Software Factory manager : Jenkins with docker swarm provisioned agents (1500+ jobs, Job DSL, pipeline), SonarQube, Nexus.
Development of an internal tool that facilitates the dependency management, release and packaging of the PGIH product (100+ ears)
Development, Maintenance and Support on the base PGIH project internal framework (JavaEE,GWT)
              """
            },
            'Sep. 12 🡒 Oct. 15' : {
              echo """JavaEE Technical Architect then ScrumMaster / Developer after the company transition to AGILE.
Distributed team.
Design & Development, on PGIH project, of :
Security subsytem
JMS based Messenging subsystem.
Batch Jobs Scheduler based on Jenkins (plugin development)
Licensing management subsystem based on a custom JBoss EAP extension and a License management tool (AngularJS,Neo4J,Fluent-HTTP)
              """
            }

          )
        }
    }
  }
}
