pipeline {
agent any
stages {
stage('Build') {
steps {
bat "mvn clean compile"
}
}
stage('Test' {
steps {
bat "mvn tests"
}
}
stage('Package') {
steps {
bat "mvn package"
}
}
}
}