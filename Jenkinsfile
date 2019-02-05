def workspace;
node
{
    stage('checkout')
        {
            checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/ParveenTeotia/github-fp.git']]])
            workspace =pwd()
        }
    stage('static code analysis')    
        {
            echo "static code analysis"
        }
    stage('Build Code')    
        {
            echo "Build Code"
        }
    stage('Unit Testing')    
        {
            echo "Unit Testing"
        }
    stage('Delivery Phase')    
        {
            echo "Delivery Phase"
        }
        
}
