pipeline { 
agent any 
stages { 
stage('Clone Repository') { 
steps { 
git 
ci.git' 
} 
} 
url: 'https://github.com/kanlily/jenkins-website
stage('Build Website') { 
steps { 
sh './hello.sh' 
} 
} 
stage('HTML Validation') { 
steps { 
echo 'Running HTML Validation...' 
sh 'tidy -q -e index.html || echo "HTML issues detected!"