/*
This is the Jenkinsfile that every repository using CI should have to trigger a release.
This should be placed in your repository at `.jenkins/release.Jenkinsfile`
The items under params can change if needed.  Note that the changes
will be applied to all projects in this repository.
*/

def params = [
        'ciVersion'     : 'main',                       // Version of the devops-jenkins-libraries that you want to use
        'configLocation': '.jenkins/config.yaml'        // Location of your repo config file that contains specific build information
]

library "devops-jenkins-libraries@${params.ciVersion}"  // Load the version of the library as defined in params.ciVersion

releaseCI params                                        // Call the groovy scripts that will trigger the release