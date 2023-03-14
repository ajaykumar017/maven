pipeline {
agent any
stages{
stage ('Git Checkout'){
steps{
git branch: 'main', url: 'https://github.com/ajaykumar017/maven.git'
}
}
   }
        }
stage('Continous Integration') {
            steps {
                echo 'Integration'
    }
}
stage('Continous Deployemeny') {
            steps {
                echo 'Deploying'
     }
}
stage('Continous Delivery') {
            steps {
                echo 'Delivering'
}
}
}
post {
always {
echo 'Always'
}
}
}
}
}
