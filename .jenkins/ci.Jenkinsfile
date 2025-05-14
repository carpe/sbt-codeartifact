def params = [
    'ciVersion': 'main',                                // Version of the devops-jenkins-libraries that you want to use
    'configLocation': '.jenkins/config.yaml'            // Location of your repo config file that contains specific build information
]

library "devops-jenkins-libraries@${params.ciVersion}"  // Load the version of the library as defined in params.ciVersion

centralizedCI params                                    // Call the groovy scripts that will run the build